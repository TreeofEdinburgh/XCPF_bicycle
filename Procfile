web: gunicorn config.wsgi:application
worker: celery worker --app=medusa.taskapp --loglevel=info
