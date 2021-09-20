# Программа обучения

    https://tutorial.djangogirls.org/ru/

# Виртуальное окружение

    python -m venv myvenv C:\Users\Name\djangomen> myvenv\Scripts\activate

# Установка Django

    python -m pip install --upgrade pip pip install -r requirements.txt

# Создание структуры проекта

    django-admin.exe startproject mysite .

    1 manage.py - это скрипт, который помогает с управлением сайтом. С помощью него, можно запустить веб-сервер.
    2 settings.py - содержит настройки веб-сайта.
    3 urls.py - содержит список шаблонов, по которым ориентируется urlresolver.

# Создание БД sqlite3

    python manage.py migrate

# Запуск веб-сервера

    python manage.py runserver

# Создание приложения

    python manage.py startapp blog

# Создаём таблицы моделей в базе данных

    python manage.py makemigrations blog
    python manage.py migrate blog

# Создание суперпользователя

    python manage.py createsuperuser
    admin admin@admin.com
    edcvfr4

# Связываем с удаленным репозиторием

    git remote add origin https://github.com/Hexogon73/my-first-blog.git
    git push -u origin master

# Обновляем фаилы в директории PythonAnywhere

    cd pylucky92.pythonanywhere.com git pull

# Обновить статичные фаилы(типа css)

    cd pylucky92.pythonanywhere.com
    workon pylucky92.pythonanywhere.com
    python manage.py collectstatic
