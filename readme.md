#Виртуальное окружение
python -m venv myvenv
C:\Users\Name\djangomen> myvenv\Scripts\activate

#Установка Django
python -m pip install --upgrade pip
pip install -r requirements.txt

#Создание структуры проекта
(myvenv) C:\Users\Name\djangomen> django-admin.exe startproject mysite .

1 manage.py - это другой скрипт, который помогает с управлением сайтом. С помощью него, можно запустить веб-сервер.
2 settings.py - содержит настройки веб-сайта.
3 urls.py - содержит список шаблонов, по которым ориентируется urlresolver.

#Создание БД sqlite3
python manage.py migrate