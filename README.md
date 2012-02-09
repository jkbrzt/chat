A primitive chat app created to experiment with Flask, Redis, Gevent & Server-Sent Events.

    pip install flask redis gevent gunicorn

    gunicorn --debug --worker-class=gevent -t 99999 app:app

