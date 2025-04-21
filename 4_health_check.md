# ⚙️ Стандартный вариант в NGINX Open Source:
В обычном NGINX (без коммерческой лицензии) health-check напрямую не встроен.
Он "полагается" на сам факт ошибки соединения или HTTP кода ответа.

Например: если backend не отвечает, NGINX переключается на другой сервер из upstream.
Это базовая защита, но не полноценный Health Check.

## 1️⃣ Для Open Source:
```
upstream my_app_servers {
    server 10.0.0.101:8080 max_fails=3 fail_timeout=30s;
    server 10.0.0.102:8080 max_fails=3 fail_timeout=30s;
}
```
Используют max_fails и fail_timeout: Если backend 3 раза подряд не отвечает — его временно исключат из пула на 30 секунд.
