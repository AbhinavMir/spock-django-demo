On the temrinal navigate to the dganjo_auth directory
    cd django_auth

To start running the local server:
1) create a virtual environment called .venv with the following command
    python -m venv .venv

2) Run the local server
    python manage.py runserver

Open your browser and type the url:
    http://127.0.0.1:8000

This will get you to the login page. 
I have already created one superuser.
username: chrysoulas.k
password: spock123

NOTE: to quit the server at any time, go to the terminal and so Contol+C


If you want to create additional superusers, quit the server, and type 
    python manage.py createsuperuser

Then follow the prompts on the terminal to create the new superuser account.

