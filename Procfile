web: studyhub.wsgi:application --log-file - --log-level debug=True
heroku ps:scale web=1
python manage.py migrate