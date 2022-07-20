Books Api
===
Abstract:Api de libros usando Django RestFramework
## Papar Information
- Title:  `Library`
- Authors:  `jocnn`

## Install & Dependence
- asgiref==3.5.2
- black==22.6.0
- click==8.1.3
- Django==4.0.6
- djangorestframework==3.13.1
- gunicorn==20.1.0
- mypy-extensions==0.4.3
- pathspec==0.9.0
- platformdirs==2.5.2
- pytz==2022.1
- sqlparse==0.4.2
- tomli==2.0.1
- whitenoise==6.0.0

## Use
- for run server
  ```
  (.venv) > python manage.py runserver
  ```
- for test
  ```
  (.venv) > python manage.py test
  ```
- for deployment
  ```
  https://abcde-library.herokuapp.com/
  https://abcde-library.herokuapp.com/api/
  ```

## Directory Hierarchy
```
|—— .gitignore
|—— .venv
|    |—— bin
|        |—— Activate.ps1
|        |—— activate
|        |—— activate.csh
|        |—— activate.fish
|        |—— black
|        |—— blackd
|        |—— django-admin
|        |—— gunicorn
|        |—— pip
|        |—— pip3
|        |—— pip3.10
|        |—— sqlformat
|    |—— include
|—— Procfile
|—— apis
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— admin.cpython-310.pyc
|        |—— apps.cpython-310.pyc
|        |—— models.cpython-310.pyc
|        |—— serializers.cpython-310.pyc
|        |—— tests.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— views.cpython-310.pyc
|    |—— admin.py
|    |—— apps.py
|    |—— migrations
|        |—— __init__.py
|        |—— __pycache__
|            |—— __init__.cpython-310.pyc
|    |—— models.py
|    |—— serializers.py
|    |—— tests.py
|    |—— urls.py
|    |—— views.py
|—— books
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— admin.cpython-310.pyc
|        |—— apps.cpython-310.pyc
|        |—— models.cpython-310.pyc
|        |—— tests.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— views.cpython-310.pyc
|    |—— admin.py
|    |—— apps.py
|    |—— migrations
|        |—— 0001_initial.py
|        |—— __init__.py
|        |—— __pycache__
|            |—— 0001_initial.cpython-310.pyc
|            |—— __init__.cpython-310.pyc
|    |—— models.py
|    |—— templates
|        |—— books
|            |—— book_list.html
|    |—— tests.py
|    |—— urls.py
|    |—— views.py
|—— db.sqlite3
|—— django_project
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— settings.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— wsgi.cpython-310.pyc
|    |—— asgi.py
|    |—— settings.py
|    |—— urls.py
|    |—— wsgi.py
|—— manage.py
|—— requirements.txt
|—— runtime.txt
|—— screenshots
|    |—— book_api_restframework_0.png
|    |—— book_api_restframework_1.png
|—— static
|—— staticfiles
|    |—— staticfiles.json
```

### Screenshots

BookApi:  localhost:8000/     |   https://abcde-library.herokuapp.com/
===
![Image text](https://github.com/jocnn/django_rest_books/blob/main/screenshots/book_api_restframework_0.png)

BookApi:  localhost:8000/api  |   https://abcde-library.herokuapp.com/api/
===
![Image text](https://github.com/jocnn/django_rest_books/blob/main/screenshots/book_api_restframework_1.png)