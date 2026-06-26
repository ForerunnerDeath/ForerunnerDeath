# Привет, я Иван 👋

## 🧰 Стек

![Python](https://img.shields.io/badge/Python-3776AB?style=flat\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat\&logo=fastapi\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat\&logo=redis\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat\&logo=docker\&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat\&logo=playwright\&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat\&logo=pytest\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat\&logo=git\&logoColor=white)

Основные технологии, с которыми сейчас работаю:

* Python, FastAPI, REST API
* PostgreSQL, SQLAlchemy, Alembic
* Redis queues и background workers
* Docker / Docker Compose
* Playwright, httpx, BeautifulSoup
* pytest, Git

## 🚀 Главный проект

### [freelance-monitor](https://github.com/ForerunnerDeath/freelance-monitor)

`freelance-monitor` - backend/automation-сервис для мониторинга заказов с фриланс-площадок.

Проект собирает заказы из источников, фильтрует их по степени интересности, сохраняет в PostgreSQL, отправляет подходящие заказы в Telegram через Redis-очередь и предоставляет FastAPI API для просмотра заказов и статистики.

Что внутри:

* парсинг заказов с FL.ru;
* авторизованный источник Profi.ru через Playwright и Docker/VNC login flow;
* фильтрация заказов по статусам `matched`, `risky`, `rejected`;
* PostgreSQL + SQLAlchemy ORM;
* миграции Alembic;
* FastAPI REST API;
* Redis queue для Telegram-уведомлений;
* отдельный Telegram worker с retry/backoff;
* Docker Compose запуск всей системы;
* pytest-тесты для фильтров и API;
* README и подготовка проекта к GitHub.

## 🎯 Что мне интересно

* Python backend-разработка
* Automation tools
* Парсинг и интеграции с внешними сервисами
* Внутренние инструменты для малого бизнеса и команд
* Telegram bots и уведомления
* API-сервисы, Dashboards и мини-CRM
* Задачи, где код решает конкретную практическую проблему

## Сейчас

Открыт к различным предложениям.
