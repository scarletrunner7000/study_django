# study_django

Writing your first Django app.


## commands

```
docker-compose run web django-admin.py startproject mysite .
docker-compose run web python manage.py startapp polls

docker-compose exec web python manage.py makemigrations polls
docker-compose exec web python manage.py sqlmigrate polls 0001
docker-compose exec web python manage.py check
docker-compose exec web python manage.py migrate

docker-compose exec web python manage.py shell
docker-compose exec web python manage.py createsuperuser

docker-compose exec db psql -h db -p 5432 -U postgres # acces to postgres
```

