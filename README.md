# Polls Application

This application is a polls app built with Django. It has a polls view as well as an admin page. These [Django Directions](https://github.com/TrinityTerry/django-directions) are instructions I compiled to create this application

## Installations
1. [Install Python](https://github.com/TrinityTerry/django-directions/blob/master/contents/installations.md#install-python-1)
1. Clone Repo
    ```shell
    $ git clone https://github.com/TrinityTerry/django-polls.git
    ```
1. Open Project
    ```shell
    $ cd django-polls/
    ```
1. [Install Django]()
1. Create Virtual Environemnt
    ```shell
    $ python3 -m venv ~/.virtualenvs/djangodev
    ```
1. Start Virtual Enviromnent
    ```shell
    $ source ~/.virtualenvs/djangodev/bin/activate
    ```

    *If the above command does not work due to the __source__ keyword, try using this dot notation command to activate the Virtual Environment*

    ```shell
    $ . ~/.virtualenvs/djangodev/bin/activate
   ```
1. Create Database
    ```shell
    $ python manage.py migrate
    ```
1. Start Server
    ```shell
    python manage.py runserver
    ```
    - Go to [http://localhost:8000/polls/](http://localhost:8000/polls/)
1. To add polls
    - Run this command to create an admin then follow the prompts
    ```shell
    python manage.py createsuperuser
    ```
    - Go to development server url http://localhost:8000/admin/
    - Login using credentials made
    - Select Questions under the poll section
    - click Add question in the top right
    - Fill out the form to create a question

