## Work env preparation

### Fedora 41

Prepare development environment:

    $ pip install pipenv
    $ pipenv install

Run the server:

    $ make runserver

Alternatively, you can enter the sandbox and run commands manually:

    $ pipenv shell
    (wedding-webpage) [user@host wedding-webpage]$ python manage.py runserver
