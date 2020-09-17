Make sure pipenv is installed
`pipenv --version`

Make sure python version 3
`python --version`

Create an environment
`pipenv --three`

Activate the environment
`pipenv shell`

Install Django
`pipenv install django`

Create a project
`django-admin startproject djorg`

Start project
`python manage.py runserver`

Show migrations
`python manage.py showmigrations`

Apply all migrations
`python manage.py migrate`

Add models to models.py file

Add app name to settings.py file under INSTALLED_APPS

Make migrations based on the model
`python manage.py makemigrations`

Apply recent migrations
`python manage.py migrate`
