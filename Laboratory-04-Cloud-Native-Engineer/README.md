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

## Skills Learned

| Skill | What I Learned |
|---|---|
| Docker CLI | How to perform basic container operations using commands. |
| Container Deployment | How to launch an application using an image. |
| Port Mapping | How a host port can connect to a service inside a container. |
| Container Management | How to check, stop, and remove containers. |
| Technical Documentation | How to record commands and results using Markdown. |

## Challenges Encountered

| Challenge | How I Handled It |
|---|---|
| Understanding Docker commands | I reviewed what each command was intended to accomplish before running it. |
| Port mapping | I checked the 8080:80 configuration to understand how the host connects to Nginx. |
| Container management | I followed the lifecycle sequence carefully from checking the container to removing it. |
