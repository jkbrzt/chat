A primitive chat app created to experiment with Flask, Redis, Gevent & Server-Sent Events.

## installation
    pip install flask redis gevent gunicorn

## running the app
    start the redis server
    redis-server
    gunicorn --debug --worker-class=gevent -t 99999 app:app
