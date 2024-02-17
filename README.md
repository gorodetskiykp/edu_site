# edu_site
Учебный проект на Django

## git - управление версиями
|Команда|Описание|
|---|---|
|git clone https://github.com/gorodetskiykp/edu_site.git|Склонировать проект из GitHub на локальный ПК|
|git add .|Добавить изменения в отслеживание|
|git commit -m ""|Фиксация изменений|
|git push|Залить зафиксированный код в GitHub|
|git pull|Забрать изменения с GitHub|

# Django

## Управление проектом
- pip install django
- django-admin startproject edu

## Структура проекта
- edu/edu - каталог управления проектом
  - settings.py - настройки проекта
    - DEBUG - ключ разработки
    - INSTALLED_APPS - приложение
    - TEMPLATES - html-шаблоны
    - DATABASES - база данных
  - urls.py - роутер/маршрутизатор
- edu/manage.py - команда управления проектом
