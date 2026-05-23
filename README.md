# WB Shop API

Интернет-магазин на Django REST Framework (учебный проект для стажировки Wildberries).

## Возможности

- Регистрация и JWT-авторизация
- Просмотр товаров
- Корзина (добавление, удаление, изменение количества)
- Оформление заказа с проверкой баланса и остатков
- Админ-панель для управления товарами и заказами

## Стек технологий

- Python 3.12.5
- Django 4.2
- Django REST Framework
- JWT-аутентификация
- PostgreSQL (в Docker)
- Docker / Docker Compose

## Как запустить проект

1. Клонировать репозиторий
2. Создать файл `.env` с настройками
3. Запустить `docker-compose up --build`

Или без Docker:

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
