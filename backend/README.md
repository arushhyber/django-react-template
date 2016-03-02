## Installation

1. `mkvirtualenv {{ project_name }}`
1. `django-admin.py startproject --template=https://github.com/scottwoodall/react-demo/archive/master.zip {{ project_name }}`
1. `cd {{ project_name }}`
1. `pip install -r backend/requirements/devl.pip`
1. `createdb {{ project_name }}`
1. `python manage.py migrate`
1. Load some test data: `python manage.py loadtestdata users.EmailUser:100`
1. Create your account: `python manage.py createsuperuser`
1. `python manage.py runserver`