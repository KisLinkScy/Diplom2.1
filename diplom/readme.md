# для запуска:
- pip install requirements.txt
- python manage.py makemigrations
- python manage.py migrate
- python manage.py collectstatic
- daphne diplom.asgi:application