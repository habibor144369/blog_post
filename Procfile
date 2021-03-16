release: python manage.py migrate
release: python manage.py createsuperuser
web: gunicorn mysite.wsgi --log-file -