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
- ### Авторы:
- Николай Гиржу.
