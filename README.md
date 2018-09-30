Django Channels Tutorial
========================

- https://channels.readthedocs.io/en/latest/tutorial/index.html

Getting Started
---------------

- To start a HTTP Server and WebSocket Server:
    - `$ python manage.py runserver`
- Start an instance of Redis:
    - `$ docker run -p 6379:6379 -d redis:2.8`
- Choose a chat room you like in:
    - `http://127.0.0.1:8000/chat/`
- If you put `lobby`, you will be redirected to:
    - `http://127.0.0.1:8000/chat/lobby/`

Tests
-----

- To run tests:
    - `$ python manage.py test chat.tests`

Concepts
--------

- A **channel** is a mailbox that you can send messages.
- A **group** is a group of related channels.
