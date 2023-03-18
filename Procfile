web: gunicorn studyhub.wsgi:application --log-file - --log-level debug=True
heroku ps:scale web=1
heroku run python3 manage.py migrate 