==== TCTracking ====

Tracking and maintenance app for TC

Primary goals are
 - queue management

Secondary goals
 - Financial reporting(likely targeted to herders)
 - Rental tracking
 - Asset Tracking

First steps
python manage.py db init
python manage.py db migrate -m "initial migration"
python manage.py db upgrade

Code based off of Flasky project from Miguel Grinberg at https://github.com/miguelgrinberg/flasky