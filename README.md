# django-learn
Project to learn django and react.

A few commands to be repeatedly used:
## 1) To create a new project
django-admin startproject <project_name>
## 2) To create a new app in the project
django-admin startapp <app_name>
## 3) To start the server
python3 manage.py runserver
## 4) Add created apps to the list of apps in settings.py
## 5) To add migrations
python3 makemigrations <app_name>

python3 manage.py migrate
## 6) When creating databases
Must specify type of the attribute in the DB.
Some types are:
a) CharField
b) ForeignKey: importing from some other model
c) BooleanField

## 7) Admin Dashboard
To create an admin user:
python3 manage.py createsuperuser

To view a database that you've created in your admin dashboard, go to admins.py inside the application directory and import the Model that you'd created. Then simply write
admin.site.register(ToDoList)
