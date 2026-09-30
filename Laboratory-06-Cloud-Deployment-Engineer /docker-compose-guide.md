# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the containers needed by the application. In this Compose file, `database` uses the `mariadb:10.6` image, while `app` uses the `nextcloud` image. Docker Compose manages both services together.

## How Did the Nextcloud App Container Know How to Find the Database?

The Nextcloud container uses `MYSQL_HOST=database` to find the database service. Since `database` matches the service name in the Compose file, Nextcloud can connect to MariaDB through the Docker network.

## What Is the Difference Between `docker run` and `docker-compose up -d`?

The `docker run` command starts an individual container, while `docker-compose up -d` starts the services defined in the Compose file. The `-d` option runs the containers in the background. This makes it easier to run Nextcloud and MariaDB together.
