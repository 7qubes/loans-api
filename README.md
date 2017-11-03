# Loans API Code Challenge
This is an RESTful API through which a big bank can easily issue new loans and find out what the value and volume of outstanding debt are.

## Main Technologies:
Python 3, Flask-RESTful, SQLite 3, TDD

## Documentation:
https://documenter.getpostman.com/view/3076044/loans-api/77h6P84

## Getting Started:
<pre>
1. python virtualenv activation:
    source venv/bin/activate

2. run api on http://127.0.0.1:8000:
    pipenv run gunicorn app.main:app
</pre>

## Runing tests file
<pre>
1. simply run:
    nosetests
</pre>
