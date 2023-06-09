# # Проект «API для Yatube»
Спринт № 9. API: интерфейс взаимодействия программ
## Задание:
```
Создание REST API для Yatube.
```
### Описание
Реализация API для всех моделей приложения Yatube.
### Технологии
Python 3.9.10
Django 2.2.19
### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
```
python -m venv venv
```
```
source venv/Scripts/activate
```
 
- Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
- Выполнить миграции:
```
python manage.py makemigrations
```
```
python manage.py migrate
```
- Запустить проект:
```
python manage.py runserver
```

### Примеры запросов

Для получения токена, необходимо выполнить POST-запрос /api/v1/jwt/create/ передав поля username и password созданного пользователя.

Передайте токен в заголовке Authorization: Bearer <токен>

/api/v1/posts/ (GET, POST, PUT, PATCH, DELETE)

/api/v1/posts/{post_id}/comments/ (GET, POST, PUT, PATCH, DELETE)

/api/v1/groups/ (GET)

/api/v1/follow/ (GET, POST)

- ### Авторы:
- Николай Гиржу.
