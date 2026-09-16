 # Docker Environment
 
 ## Checkpoint 3: Doctor Verification

| Command | Explanation |
|---|---|
| docker --version | Confirms that Docker is available and identifies the installed version. |
| docker info | Provides details about the Docker installation and environment. |

| Evidence | File |
|---|---|
| Docker terminal verification | docker-version.png |

## Checkpoint 4: Nginx Deployment

| Action | Command | Explanation |
|---|---|---|
| Pull image | docker pull nginx | Gets the official Nginx image needed for the deployment. |
| Run container | docker run -d -p 8080:80 --name nginx-server nginx | Starts Nginx in the background and connects host port 8080 with container port 80. |
| Test server | curl http://localhost:8080 | Sends a request to check whether the Nginx server responds. |

| Test | Expected Result |
|---|---|
| curl http://localhost:8080 | The Nginx welcome page should be returned, including *“Welcome to nginx!”* |

| Evidence | File |
|---|---|
| Nginx test result | nginx-running.png |

## Checkpoint 5: Container Lifecycle

| Activity | Command | Explanation |
|---|---|---|
| List containers | docker ps | Checks which containers are currently running. |
| Stop container | docker stop nginx-server | Changes the Nginx container from running to stopped. |
| Verify status | docker ps | Checks the list again to confirm that Nginx is no longer running. |
| Delete container | docker rm nginx-server | Permanently removes the stopped Nginx container. |

| Evidence | File |
|---|---|
| Lifecycle command results | container-lifecycle.png |
