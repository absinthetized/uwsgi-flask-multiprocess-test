# uwsgi-flask-multiprocess-test
just a dumb test to understand uwsgi-flask multiprocess behaviour

- run in virtualenv
- pip install requirements
- run via: ../bin/uwsgi --ini uwsgi.ini

Customize the app.py file as you want and edit the thread/process number in the uwsgi.ini file to view how the system responds/scales
