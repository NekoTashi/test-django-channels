Django Channels Tutorial
========================

Start an instance of Redis:
    - `$ docker run -p 6379:6379 -d redis:2.8`

To run tests:
    - `$ python manage.py test chat.tests`

Concepts
--------

- A **channel** is a mailbox that you can send messages.
- A **group** is a group of related channels.
