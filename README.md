
# Django with Docker.

It's django project to run on docker. I used to basic docker services Web and DB.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
Install docker and docker compose  
Here is offical documentation of docker  
https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce-1  

Before run the application, stop the postgresql services.

**sudo service postgresql stop**

###### Installing
```
1. clone from repository  
  https://github.com/mrakrathod/django-with-docker.git 

2.Build the docker image  
   docker build -t django_docker_img .  

3. Run the djagno application  
  docker-compose up
```
