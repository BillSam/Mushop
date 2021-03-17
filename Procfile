
release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input

web: gunicorn incomeexpensesapi.wsgi
web: gunicorn backend.wsgi --log-file -