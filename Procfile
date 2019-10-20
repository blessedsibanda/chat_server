web: daphne channels_intro.asgi:channel_layer --port $PORT --bind 0.0.0.0 -v2 --chdir django --log-file -
worker: python django/manage.py runworker -v2 