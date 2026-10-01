# Проекты и технологии

Справочный список для составления резюме/сопроводительных писем под
конкретную вакансию. По каждому проекту — только реально использованные
технологии.

## vacancy-radar
Go-сервис: опрашивает hh.ru по ключевым словам подписки и уведомляет
пользователей о новых вакансиях в Telegram.
**Технологии:** Go, net/http, go-chi, JWT (golang-jwt), bcrypt, PostgreSQL
(pgx/v5), SQL-миграции, конкурентность (goroutines, worker pool), Docker,
GitHub Actions CI, модульные тесты (httptest, race detector).

## crypto-etl-pipeline
Часовой ETL-пайплайн: данные топ-100 криптовалют с CoinGecko API в
Postgres-витрину, аналитика, алерты в Telegram при аномалиях цены.
**Технологии:** Python, Apache Airflow, PostgreSQL, psycopg2, SQL (оконные
функции: LAG, DENSE_RANK, AVG OVER), Telegram Bot API, Docker Compose.

## Platezh
Десктоп-приложение для учёта платных услуг в больнице: роли
кассир/экономист/админ, договоры с оплатами и историей, печать в Excel.
**Технологии:** C#, .NET 8, WPF, Microsoft SQL Server (ADO.NET, транзакции),
ClosedXML, реляционная схема БД (11 таблиц).

## WorkBy (приватный репозиторий)
Фриланс-платформа: тендеры, заказы, сделки с эскроу, отзывы, AI-помощник
для составления предложений.
**Backend:** Python, FastAPI, SQLAlchemy 2.0 (async), PostgreSQL, Redis,
Alembic, JWT, Telegram-бот, email-уведомления (aiosmtplib), генерация PDF
(reportlab), интеграция с Anthropic Claude API.
**Frontend:** Next.js, React, TypeScript, Tailwind CSS.

## tg-bot-parser-wb-reviews
Telegram-бот для сбора отзывов и вопросов о товаре с Wildberries, экспорт
в Excel.
**Технологии:** Python, aiogram 3, aiohttp, aiosqlite, openpyxl, Docker,
работа с внутренним API маркетплейса.

## MyGomel
Django-сайт с интерактивной картой городских объектов (Leaflet) и
автогеокодированием адресов.
**Технологии:** Python, Django, MySQL, Leaflet.js, Nominatim/OpenStreetMap
API, Gunicorn, деплой на Vercel.

## ClipFlow
Telegram-бот для скачивания видео с Twitch/YouTube с разбиением больших
файлов на части.
**Технологии:** Python, asyncio, Pyrogram, yt-dlp, ffmpeg.

## byn-fx-extension
Расширение для Chrome: конвертация цен в BYN в другие валюты на лету.
**Технологии:** JavaScript, Chrome Extension (Manifest V3), chrome.storage,
интеграция с API Нацбанка РБ.

## my-custom-theme-goskb
Тема WordPress для сайта больницы — дипломный проект, внедрён в
продакшн и работает как основной сайт учреждения.
**Технологии:** PHP, WordPress, Advanced Custom Fields (ACF).

## restaurant-site (приватный репозиторий)
Учебная вёрстка лендинга.
**Технологии:** HTML, CSS, JavaScript, jQuery.

## LunaMeet (командный хакатон-проект, InnoHackathon)
Сервис городских мероприятий — одна из частей командной разработки (4
участника).
**Технологии:** Python, Django, SQLite, кастомная модель пользователя.
