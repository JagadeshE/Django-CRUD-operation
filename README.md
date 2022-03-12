# Django-CRUD-operation
Create Web Application With CRUD 


1. Create Virtual Environment

2. Activate virtualen

$source virtualenv/bin/activate

3. Install Django 
4. Configure External Database (Postgreesql (DB: django,admin,admin@123))
5. Create Django project
6. Create Directory  employee_crud
$ django-admin startproject employee
7. Create django app inside django project
$ python manage.py startapp emmployee_db
8. Configure app in project
settings.py -> add app name in INSTALLED APPS
9. Create models, views,forms,urls
10. Configure static files in and configure static files in settings.py
11. Add css,js (bootstrap, custom css,js) in static folder
12. Create templates add html files inside employee_db app folder
13. Call bootstraps in base.html file.
14. Run below commands for migrate and run django server
$ python manage.py makemigrations --> Create new fields in database
$ python manage.py migrate
$ python manage.py runserver
