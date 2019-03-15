# django-cheat-sheet

Diango useful commands

## Django admin
commond | Summary
django-admin startproject <project-name> | create new project
django-admin compilemessages | compile project message (required in order to reload I18N messages)


## Manage.py

python manage.py startapp <name> | create app inside the project
python manage.py runserver  <port> | run application server
python manage.py createsuperuser | create super-user
python manage.py makemigrations <app> | generate migrations for app
python manage.py sqlmigrate <app> <migration-number> | display sql which will be generated for migration
python manage.py migrate | apply non-executed migrations
python manage.py shell | run shell for application
python manage.py test <app> | run the tests for application


