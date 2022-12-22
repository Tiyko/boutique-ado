web: gunicorn boutique_ado.wsgi:application --log-file - --log-level debug
python manage.py collectstatic
manage.py migrate