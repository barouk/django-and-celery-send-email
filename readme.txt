1-create venv and install requirements.txt
2-install rabbitmq server
2-python manage.py migrate


3-cd proj celery -A proj worker -l INFO

4-create superuser in django

5-python manage.py runserver