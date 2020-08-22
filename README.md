### Lint and run unit tests locally
```
docker-compose run app --rm sh -c "python manage.py test && flake8" 
```