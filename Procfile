release: sh -c 'python manage.py migrate --run-syncdb && python manage.py loaddata */fixtures/*.json'
web: gunicorn project_django.wsgi --log-file -
