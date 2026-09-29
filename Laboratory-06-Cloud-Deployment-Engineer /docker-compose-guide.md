# Docker Compose Guide

## What Does the services: Block Do?

The services: block defines the containers needed by the application. In the Compose file, there are two services: database and app. The database service uses the mariadb:10.6 image, while the app service uses the nextcloud image. These definitions allow Docker Compose to manage both services as part of one application.

## How Did the Nextcloud App Container Know How to Find the Database?

The Nextcloud app container uses the MYSQL_HOST environment variable to identify the database service.

MYSQL_HOST=database

The value database matches the name of the database service in the Compose file. Docker Compose allows services to communicate with each other using their service names on the same network. This allows Nextcloud to locate and connect to MariaDB.

## What Is the Difference Between docker run and docker-compose up -d?

The docker run command is used to create and start an individual container using the options provided in the command. When an application needs multiple containers, each container may need to be configured and started separately.

In comparison, docker-compose up -d reads the docker-compose.yml file and starts the services defined in it. The -d option runs the containers in the background.

In this mission, Docker Compose is used to deploy Nextcloud and MariaDB together through one configuration file.
