# softuni-jenkins
#
docker build -t simple-flask-app . &&
docker container run -it -p 80:80 simple-flask-app:latest
