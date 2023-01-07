## Install project

### Init project
``docker-compose run --rm wep-app django-admin startproject service .``

### Run migration
``docker-compose run --rm wep-app python manage.py migrate``

### Create superuser for admin panel
``docker-compose run --rm wep-app python manage.py createsuperuser``

### Run project
``docker-compose up -d``