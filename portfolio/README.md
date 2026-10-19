# Portfolio

Личный сайт-портфолио backend-разработчика. Демонстрация навыков:
Docker, Nginx, CI/CD, работа с API.

## Локальный запуск

    cp .env.example .env
    docker compose up -d

Сайт: http://localhost:8080

## Проверка

    curl http://localhost:8080/health   # -> ok

## Структура

- `front/` — статика (позже переедет на Astro)
- `nginx/` — конфиги reverse proxy
- `.github/workflows/` — CI/CD пайплайн

## Roadmap

- [x] v0.1 — Начальная версия, сделанная на коленке с запозданием. Всем спасибо!