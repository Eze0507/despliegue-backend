release: python manage.py migrate --no-input && python manage.py collectstatic --no-input --verbosity 2
web: gunicorn backend_taller.wsgi:application