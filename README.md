hello-world
===========

<p align="center">
  <a href="#running-locally">Running locally</a> •
  <a href="#deploying-to-Docker-Cloud">Deploying to Docker Cloud</a>
</p>

[![Deploy to Docker Cloud](https://files.cloud.docker.com/images/deploy-to-dockercloud.svg)](https://cloud.docker.com/stack/deploy/)

Sample docker image to test docker deployments

## Running locally

Build and run using Docker Compose:

	$ git clone https://github.com/docker/dockercloud-hello-world
	$ cd dockercloud-hello-world
	$ docker-compose up


## Deploying to Docker Cloud

[Install the Docker Cloud CLI](https://docs.docker.com/docker-cloud/tutorials/installing-cli/)

	$ docker login
	$ docker-cloud stack up

Hello world!
Goodbye...
Hello again !!!
