create a virtual environment
python -m venv venv
.\venv\Scripts\activate
pip install django


Create a Django Project:

django-admin startproject ats_resume
cd ats_resume


Create a Django App:

python manage.py startapp users

Add the App to INSTALLED_APPS in settings.py:

INSTALLED_APPS = [
    ...
    'users',
]
