# Installing

 - clone this repo
 - Make dir in your repo named "database"
 - Install docker & docker-compose to your system
 - Run docker-compose build
 - Run docker-compose up
 - Run docker-compose exec web ./manage.py migrate
 - Run docker-compose exec web ./manage.py createsuperuser & create superuser

Go to your browser: http://localhost:7080/admin
