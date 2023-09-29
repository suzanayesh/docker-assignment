# docker-assignment

Create a docker image that hosts a static-website using Nginx reverse proxy.


The task is to create a simple index.html file (put in it whatever you want). Then package it inside a docker image that serves html using Nginx web server.

The docker image must be published to Docker Hub (not Github Registry).

Deliverable: A link to a public GitHub repository that contains at least the following 4 files:
Dockerfile
docker-compose.yml # development docker compose file that builds the image and runs the container for development
docker-compose-prod.yml # The production docker compose file that can be run in AWS EC2 for example
GitHub workflow file that builds and publishes the docker image to Docker Hub

![image](https://github.com/suzanayesh/docker-assignment/assets/100838193/6d051e48-5d43-4c5d-b9c3-ded196d29c29)
docker build -t suzanma/docker_assignment:latest .
docker push suzanma/docker_assignment:latest

![image](https://github.com/suzanayesh/docker-assignment/assets/100838193/36eee419-80f0-4bfa-aabf-ca88224d8630)

