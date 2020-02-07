# Word Frequency From Web Page

## Quick Start

### Virtual Python Environment

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
# run redis
$ redis server

# worker process
$ python worker.py

# run the app
$ python app.py
```