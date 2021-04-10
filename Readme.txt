1. django-admin startproject TODO_APP
   run inside django_projects

2. python manage.py runserver
   run where manage.py is

3. python manage.py migrate
   creates a default database with default tables

SuperUser: The most powerful user with permissions to create, read, update and delete data in the Django admin, 
            which includes model records and other users.

4. python manage.py createsuperuser

*for this project all users have their password = username

5. python manage.py runserver
   Again, and now you can login


Superuser: Username: Sampriti pwd: Sampriti
Users: Username: Meghna pwd: Singh.123

6. Startapp: python manage.py startapp tasks 
   tasks is the app_name

7. Add 'tasks' to installed apps list in settings.py

8. Setup Httpresponses in views.py
   Eg.
      from django.http import HttpResponse
      def index(request):
           return HttpResponse('Hello World')

9. Create urls.py in tasks
   add the routings there

bleh bleh check video

10. create templates 

11. All data and their structures are defined in models.py

12. Create a model
    run: python manage.py makemigrations
         python manage.py migrate

13. Add the models to admin.py and register them
