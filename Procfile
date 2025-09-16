release: python manage.py migrate
web: python manage.py collectstatic && gunicorn backend_taller.wsgi:application