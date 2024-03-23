# PartySync Back End

# front end link
https://github.com/charlie-bedell/partysync-front-end

# Getting started
git clone https://github.com/Stephen-c-Kelly/partysync-back-end.git 

create database: execute create-database by running:

psql -f create-database.sql 

if this fails, run the commands in create-database.sql in sequence.

create a virtual environment and install dependencies: run pipenv shell 

install the following onyo your virtual env using pip install:
django djangorestframework psycopg2-binary 
psycopg
django-rest-framework djangorestframework-simplejwt django-cors-headers django-environ dj-database-url django-heroku whitenoise gunicorn

If working locally, review settings.py and ensure DATABASES is pointing to host 'localhost'. You may have to comment out the references to database_url



run the server: python3 manage.py runserver

