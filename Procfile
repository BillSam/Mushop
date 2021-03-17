web: python manage.py collectstatic --no-input; gunicorn myapp.wsgi --log-file - --log-level debug
release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input


web: python manage.py collectstatic --no-input; web: gunicorn backend.wsgi --log-file - --log-level debug