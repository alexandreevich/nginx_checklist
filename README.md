# 🚀 DevOps NGINX Roadmap Checklist

> Ориентирован на практическое использование NGINX как обратного прокси, балансировщика и для защиты приложений.

---

## 📗 Основы NGINX
- [ ] Понимать разницу между **Nginx и Apache**.
- [ ] Разобраться что такое **reverse proxy** и когда его использовать.
- [ ] Понимать что такое **upstream** и зачем нужен.
- [ ] Уметь настраивать **location-блоки**.
- [ ] Знать как подключать **SSL / TLS** с помощью `certbot`.
- [ ] Уметь настраивать редиректы (`301`, `302`).
- [ ] Понимать что такое **gzip-компрессия** и как её включить.
- [ ] Уметь настраивать **basic-auth** через `htpasswd`.

---

## 💡 Продвинутая настройка
- [ ] Понимать и применять **Load Balancing** (`round-robin`, `least_conn`, `ip_hash`).
- [ ] Настраивать **Health-check для upstream**.
- [ ] Разбираться в кэшировании: `proxy_cache`, `fastcgi_cache`.
- [ ] Понимать разницу между `proxy_pass` и `rewrite`.
- [ ] Уметь строить **rate limiting** и DDoS защиту (`limit_req_zone`, `limit_conn`).
- [ ] Уметь логировать запросы и настраивать **формат access.log**.
- [ ] Понимать как устроены **error log уровни** (`debug`, `info`, `notice`, `warn`, `error`, `crit`).
- [ ] Осваивать **conditional конфигурации** с `map` и `if`.

---

## 🔥 NGINX + DevOps практика
- [ ] Контейнеризация NGINX с `Docker`.
- [ ] Использование NGINX как **Ingress Controller в Kubernetes**.
- [ ] Автоматическое обновление SSL сертификатов через `Let's Encrypt`.
- [ ] Использование **NGINX Amplify** для мониторинга.
- [ ] Интеграция NGINX с **Prometheus / Grafana**.
- [ ] Оптимизация производительности (`worker_processes`, `worker_connections`).
- [ ] Настройка безопасных заголовков:  
      `X-Frame-Options`, `X-XSS-Protection`, `Strict-Transport-Security`, `Content-Security-Policy`.

---

## 🧠 Теория и архитектура
- [ ] Разобраться в **модульной архитектуре NGINX**.
- [ ] Понимать что такое **NGINX Plus** и его отличия от Open Source.
- [ ] Разобраться как работает **event loop** в NGINX.
- [ ] Понимать как конфигурировать NGINX для микросервисов.
- [ ] Знать как использовать **Failover и Backup серверы**.

---

✅ Сохрани себе, сделай форк и отслеживай прогресс!  
Можем вместе пошагово проходить темы, как с Java! 

---

