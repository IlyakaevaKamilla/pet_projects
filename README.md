# 🚀 Мои PET-проекты

> Опыт на Django, FastAPI, Docker | 3 реальных проекта в портфолио

---

## 1. 🛍️ Интернет-магазин товаров для дома

**Описание:** Полноценный проект с каталогом, корзиной, избранным и email-уведомлениями. Админ-панель с аналитикой.

### 🛠 Технологии
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-154A63?logo=SQLite&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-8620F8?logo=Bootstrap&logoColor=white)
![Django CBV](https://img.shields.io/badge/Django-Class--Based_Views-green?logo=django)
![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)


### ✨ Ключевые особенности
- 📦 Галерея изображений для каждого товара
- ❤️ Избранное с отображением статуса на всех страницах
- 🛒 Корзина с выборочной покупкой и автопересчётом
- 📧 Email-уведомления администратору и покупателю
- 📊 Админ-панель со счётчиками избранного и корзины

### 🚀 Быстрый старт
```bash
git clone git@github.com:IlyakaevaKamilla/shop--django-.git
cd shop
python -m venv venv
. venv/scripts/activate  # Windows
# source venv/bin/activate  # Mac/Linux
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
### 🔗 **[Перейти к проекту →](https://github.com/IlyakaevaKamilla/shop--django-.git)**

---
## 2. 📚 English Flashcards

**Описание:** Сервис для изучения английских слов. Пользователи создают карточки, добавляют в избранное, видят «Слова дня». Полная контейнеризация.

### 🛠 Технологии
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-154A63?logo=PostgreSQL&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2B6CEF?logo=Docker&logoColor=white)
![Django CBV](https://img.shields.io/badge/Django-Class--Based_Views-green?logo=django)
![Django Auth](https://img.shields.io/badge/Django-Auth-green?logo=django)

### ✨ Ключевые особенности
- 🔄 Слова дня — 5 рандомных слов каждый день
- 🔒 Публичные/приватные карточки с переключателем видимости
- ⭐ Избранное с доступом к чужим карточкам
- 🐋 Docker-контейнеризация (готов к деплою)
- 👤 Редактирование профиля пользователя

### 🚀 Быстрый старт (Docker)
```bash
git clone git@github.com:IlyakaevaKamilla/english-flashcards--django-.git
cd english-flashcards
# Создайте .env с переменными (пример в репозитории)
docker compose up -d --build
# Откройте http://localhost:8000
```
### 🔗 **[Перейти к проекту →](https://github.com/IlyakaevaKamilla/english-flashcards--django-.git)**

---
## 3. 🍽️ FastAPI Бронирование кафе (командный проект)

**Описание:** Асинхронный сервис для управления кафе и бронирования. Моя роль: CRUD-эндпоинты для кафе + модуль загрузки/обработки изображений.

### 🛠 Технологии
![FastAPI](https://img.shields.io/badge/FastAPI-149F92?logo=FastAPI&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D72D13?logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-242424?logo=python&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-417DAD?logo=python&logoColor=white)
![UUID](https://img.shields.io/badge/UUID-FDD74F?logo=python&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-417DAD?logo=python&logoColor=white)
![logging](https://img.shields.io/badge/logging-FDD74F?logo=python&logoColor=white)


### ✨ Мои задачи в проекте

- 📝 Разработала CRUD-эндпоинты для управления кафе (создание, просмотр, редактирование)
- 🖼️ Реализовала асинхронную загрузку изображений с валидацией (≤5 Мб, JPEG/PNG)
- 🔄 Настроила конвертацию в JPEG с обработкой прозрачности, ресайзом и сжатием (quality=85)
- 💾 Организовала обработку изображений в памяти (BytesIO) — без временных файлов
- 📤 Создала эндпоинт для отдачи медиа с правильными Content-Type/Content-Disposition
- 🔗 Интегрировала медиа с моделью кафе (внешний ключ)

### 🚀 Особенности реализации
- Вся обработка изображений асинхронная
- Код прошёл код-ревью и покрыт логированием
- Использование UUID для уникальных имён файлов

### 🔗 **[Перейти к проекту →](https://github.com/Yandex-Practicum-Students/62_63_booking_seats_team_2.git)**