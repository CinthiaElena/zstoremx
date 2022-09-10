release: python manage.py migrate --noinput
web: gunicorn ecommerce_project.wsgi:application --log-file -