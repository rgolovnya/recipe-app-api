# Recipe app API




To start project, run:

```
cd <project-dir>
docker-compose build
docker-compose up
```
The API will then available at http://127.0.0.1:8000 .

To test project, run:
```
docker-compose run app sh -c "python manage.py test"
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

other commands
```
docker build .
docker-compose build
docker-compose run app sh -c "django-admin.py startproject app ."
docker-compose run app sh -c "python manage.py startapp core"
docker-compose run --rm app sh -c "python manage.py startapp user"
docker-compose run --rm app sh -c "python manage.py startapp recipe"
docker-compose run --rm app sh -c "python manage.py makemigrations"

docker-compose run --rm app sh -c "python manage.py makemigrations core"
```