## Mission Overview

The fourth laboratory activity introduces cloud-native engineering by focusing on containers and Docker. The activity includes comparing containers with Virtual Machines and using Docker to run an Nginx web server.

## Objectives

| Objective | Description |
|---|---|
| Compare technologies | Identify the main differences between VMs and containers. |
| Use Docker | Work with Docker through the KillerCoda Playground. |
| Practice commands | Perform basic Docker CLI operations. |
| Deploy Nginx | Pull and run an Nginx container. |
| Manage containers | Practice checking, stopping, and removing containers. |
| Document work | Record the laboratory activities using Markdown. |

## Docker Commands Executed

| Command | Function |
|---|---|
| docker --version | Checks the Docker version. |
| docker info | Displays Docker environment details. |
| docker pull nginx | Retrieves the Nginx image. |
| docker run -d -p 8080:80 --name nginx-server nginx | Creates and starts the Nginx container. |
| curl http://localhost:8080 | Tests the Nginx service. |
| docker ps | Displays active containers. |
| docker stop nginx-server | Stops the Nginx container. |
| docker rm nginx-server | Deletes the stopped container. |

### Skills Learned

I learned how to use Docker CLI to do basic container operations with commands. I also learned how to launch an application using a container image. I understand how port mapping works so a port on the host can connect to a service inside the container. I can manage containers too — check their status, stop them, and remove them when not needed. I also learned how to write technical documentation using Markdown to record commands and results clearly.

## Challenges Encountered

When I found Docker commands hard to understand at first, I reviewed what each one was meant to do before running it. For port mapping, I checked the 8080:80 configuration to understand how the host connects to Nginx. And for container management, I followed the whole process carefully from checking the container to removing it.
