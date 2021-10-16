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
```

other commands
```
docker build .
docker-compose build
docker-compose run app sh -c "django-admin.py startproject app ."
docker-compose run app sh -c "python manage.py startapp core"
```