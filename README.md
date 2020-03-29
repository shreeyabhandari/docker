# Docker

Docker is the world's leading software container platform.Docker makes the process of application deployment very easy and efficient and resolves a lot of issues related to deploying applications.
(Frontend component, Backend workers, DB, Env|Libs Dependencies) these all need to be run from different platform on different devices. So to make it run on all available platform without an error Docker comes with a solution by providing Container.

### What is docker ###

Docker is a tool designed to make it easier to deploy and run applications by using containers.

### What is container? ###
Containers allow a developer to package up an application with all of the parts it needs such as libraries and other dependencies and ship it all out as one package.

### Docker Workflow ###

Developer = Dockerfile = describes steps to create a Docker image. Its like a receipe with all ingredients and steps necessary in making your dish.

Docker file can be used to make <b>Docker image</b>
So when you run docker image you get <b> Docker Container</b>

### Docker Container ###
(which will have applications with all its dependencies) are the run time instances of docker image which can be stored on online cloud repositeries called Docker Hub.

### Play with Docker ###
https://labs.play-with-docker.com

### Kitematic ###
UI for docker


### Docker Basic Command

##### Basic

| Command | Description |
| ------- | ----------- |
| `docker version` |gives information on docker client and server: Engine|
| `docker -v`/ `docker --version` | gives docker version |
| `docker info` | detailed info on docker installed on your system|
| `docker --help` |to get info on any other command  |
| `docker login` | to login to your computer and docker hub which can be used for pull and push|

##### Images

| Command | Description |
| ------- | ----------- |
| `docker images` | list of all images |
| `docker pull` |pull any repositories/images  |
| `docker rml` |  |

##### Containers

| Command | Description |
| ------- | ----------- |
| `docker ps` |to list all running containers  |
| `docker ps -a` | to list all containers |
| `docker run` |  |
| `docker start` |  |
| `docker stop` |  |


##### System

| Command | Description |
| ------- | ----------- |
| `docker stats` | |
| `docker system df` | |
| `docker system prune` |  | 




