 # Docker Deployment
 
 ## Checkpoint 3: Docker Verification

| Command | Explanation |
|---|---|
| docker --version | Confirms that Docker is available and identifies the installed version. |
| docker info | Provides details about the Docker installation and environment. |

## Checkpoint 4: Nginx Deployment

| Command | Explanation |
|---|---|
| `docker pull nginx` | Gets the official Nginx image needed for the deployment. |
| `docker run -d -p 8080:80 --name nginx-server nginx` | Starts Nginx in the background and connects host port 8080 with container port 80. |
| `curl http://localhost:8080` | Sends a request to check whether the Nginx server responds. |


## Checkpoint 5: Container Lifecycle

| Command | Explanation |
|---|---|
| `docker ps` | Checks which containers are currently running. |
| `docker stop nginx-server` | Changes the Nginx container from running to stopped. |
| `docker ps` | Checks the list again to confirm that Nginx is no longer running. |
| `docker rm nginx-server` | Permanently removes the stopped Nginx container. |

