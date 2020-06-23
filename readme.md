# Containers

## What is a container

Docker and other resources partitions operating systems as oposed to resources.

What is partitioned:
- Processs namespace
- Network namespace
- File system namespace

This means that every container will have its own Process, network and file system namespaces

## Basic Docker commands

- `docker run <name_of_container>` - runs a new contaier
- `docker ps` - to see running and stopped containers
- `docker images` - to see info about images

## Pylling and running containers

- Installing Docker gives you the `client` and `daemon`
- Client makes API calls to daemon
- `docker run` starts a new container
- `Docker Hub` is the default public registry
- The daemon will pull images that it doesn't already have.

## Containers and Images

Images - Stopped containers
Containers - running images

`docker pull <name_of_image>` this command will pull an image from docker

Where to find images: `hub.docker.com/`

## Container Lifecycle

- `docker start <container>` - runs a container
- `docker stop <contianer>` - stops container
- `docker rm <contaier>` - Removes container

Wheather or not the container starts or stops, the data for the container is not lost unless you remove it.

