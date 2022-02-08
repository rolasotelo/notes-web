# NOTES App
Flask app for taking notes, with data persistence and authentication

```shell
$ pipenv shell
$ pipenv install
# setup .env file
# Now create and run migration
$ flask db init
$ flask db migrate
$ flask db upgrade
# Run project
$ flask run
```