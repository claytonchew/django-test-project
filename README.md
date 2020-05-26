# Django Test Project

This is my test project for a multi-user blog with Django as the backend and Bootstrap for the frontend.

<img src="https://github.com/claytonchew/img/raw/master/django-blog-screenshot.png" width="500px" />

I've also made a Flask version [here](https://github.com/claytonchew/flask-test-project).


## Running this app in Development Mode

1. Setup your python environment:

   * python version 3.7+
   * install `requirements.txt`

2. Initialise / migrate sqlite database

   ```bash
   python manage.py migrate
   ```

3. Create a super user and follow the instructions

    ```bash
    python manage.py createsuperuser
    ```

4. Lastly, run the server on local

   ```bash
   python manage.py runserver
   ```

5. Access

    * Blog Site: http://localhost:8000/
    * Admin Site: http://localhost:8000/admin