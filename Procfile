web: newrelic-admin run-program gunicorn -b "0.0.0.0:$PORT" server:app
celery: celery -A tasks worker --loglevel=info
# web: honcho -f ProcfileFree start