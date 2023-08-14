# Custom Django project template

### Install with poetry
- `python3.10 -m virtualenv .venv`
- `pip install -U poetry`
- `poetry install`

### Configuration
- Migrations:
  - `python manage.py makemigrations`
  - `python manage.py migrate`
- Create/Edit .env file: `cp .env-example .env`
- Create user: `python manage.py createsuperuser`
- Change user's password: `python manage.py changepassword info@example.com`
- Rename `my_project` folder and `my_project` references to your project name 

### Usage
- Run Django Server: `python manage.py runserver`
- Django Admin URL: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
- Login to Django Admin with User/Pass fe: `info@example.com`/`info@example.com`
- API URL: http://127.0.0.1:8000/api/docs#/