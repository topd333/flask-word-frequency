# Word Frequency From Web Page

## Quick Start

### First Steps

```sh
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

### Set up Migrations

```sh
$ python manage.py db init
$ python manage.py db migrate
$ python manage.py db upgrade
```

### Run

Run each in a different terminal window...

```sh
# redis
$ redis server

# worker process
$ python worker.py

# the app
$ python app.py
```