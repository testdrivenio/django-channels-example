# Django Channels Tutorial

## Want to learn how to build this?

Check out the [tutorial](https://testdriven.io/blog/django-channels/).

## Want to use this project?

1. Fork/Clone

1. Create and activate a virtual environment:

    ```sh
    $ python3 -m venv venv && source venv/bin/activate
    ```

1. Install the requirements:

    ```sh
    (venv)$ pip install -r requirements.txt
    ```

1. Apply the migrations:

    ```sh
    (venv)$ python manage.py migrate
    ```

1. Start a Redis server for backing storage:

    ```sh
    (venv)$ docker run -p 6379:6379 -d redis:5
    ```

1. Run the server:

    ```sh
    (venv)$ python manage.py runserver
    ```

1. By default, only authenticated users can chat. To create a test user:

    ```sh
    (venv)$ python manage.py createsuperuser
    ```

1. Log in using your newly created user at [http://localhost:8000/admin/](http://localhost:8000/admin/).

1. Navigate to [http://localhost:8000/chat/](http://localhost:8000/chat/).
