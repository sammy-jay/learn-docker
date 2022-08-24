# Learn Docker

Docker is an open platform for developing, shipping, and running applications.

Docker uses a client-server architecture. The Docker _client_ talks to the Docker _daemon_, which does the heavy lifting of building, running and distributing your Docker containers.

## The Docker daemon

The docker daemon (`dockerd`) listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes. A daemon can also communicate with other Docker daemons to manage Docker services.

## The Docker client

The docker client (`docker`) is the primary way that many Docker users interact with Docker. When you use commands such as `docker run`, the client sends these commands to the Docker daemon, which carries them out.

## Docker Desktop

A PC Software that allows you to build and share containerized applications and microservices.

## Docker registeries

A Docker registry stores Docker images

## Docker objects

Docker objects include the following

- Images : contains read only instructions for creating a Docker file
- Containers : runnable instance of an image
- Networks
- Volumes
- Plugins
