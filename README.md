# Udacity Containers


## Description
Course projects for the Udacity Full Stack Nanodegree section on "Server Deployment, Containerization, and Testing".

## Exercise 1 - Hello World
## Exercise 2 - Flask Example


## Docker concepts
The Docker engine is an application that consists of the daemon, an API, and a client. The Docker daemon is a server that manages the images, containers, networks, and volumnes. The Docker client is the user interface for for Docker. The client communicates with the daemon through the API.

Additional parts of the Docker platform are the image, container, and the registry.

The Docker image is the set of instructions to create a container. A Docker container is a runnable instance of an image. Multiple containers can be created from the same image. Docker images can be stored and distributed in a Docker registry like DockerHub.


## Useful Docker commands
- `docker pull IMAGE_NAME` - retrieves the image from the DockerHub
- `docker run` - runs the image, can set environment variables using `-e`
- `docker images` - get a list of the images
- `docker ps` - get a list of the running containers
- `docker stop CONTAINER_ID` - stops the running container

