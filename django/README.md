# [Vidly](https://afternoon-beach-16819.herokuapp.com)

A very small and lightweight django site for movies rental services.
The site include two apps excluding admin, movie and api.

# Dependencies

* Django
* Gunicorn
* materialize
* Whitenoise
* Tastypie
* Sqlite3

# How to Deploy

* Install all the required dependencies
* Run ``python3 manage.py runserver``
* Run ``django-admin createsuperuser`` to create an admin account
* Before uploading to the server use ``python3 manage.py collectstatic``
* After uploading to the server add the running url to the allowed host section in settings.py
