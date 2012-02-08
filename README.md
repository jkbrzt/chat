A primitive chat app created to experiment with Flask, Redis, Gevent & Server-Sent Events.

    pip install flask redis gevent gunicorn

    gunicorn --debug -t 99999 app:app

