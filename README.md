# c2-recipe-app-api-2
Course code for: Build a Backend REST API with Python &amp; Django - Advanced: Take the course here: https://londonapp.dev/c2

docker-compose up
si vamos a 127.0.0.1:8000 aparece la instancia de django
docker compose down
 sirven para reiniciar los contenedores

docker-compose build
ejecuta el Dockerfile y carga las dependencias definidas

correr pruebas
docker-compose run --rm app sh -c "python manage.py test"
