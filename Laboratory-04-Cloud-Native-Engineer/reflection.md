## Mission Reflection

| Question | Answer |
|---|---|
| *How does booting a Docker container compare to installing an OS on a VM?* | A Docker container does not need to start a separate Guest OS, so its setup is generally much quicker. A VM includes its own operating system, which requires more resources and time to initialize. |
| **Why is -p 8080:80 necessary?** | The option establishes port mapping between the host and the container. Port 8080 is the host-side port, while 80 is the port used by Nginx inside the container. This makes the Nginx page reachable through localhost:8080. |
| **What happens to data inside the container when you run docker rm?** | docker rm deletes the specified container. Any information that exists only within that container will not remain available after the container has been removed. |
| *How does containerization change DevOps collaboration?* | Containers give teams a consistent application environment that can be used during development and deployment. This can make it easier for developers and operations teams to work with the same packaged application environment. |
| *How is your GitHub portfolio evolving as you complete more cloud computing activities?* | My portfolio is gradually becoming a record of the cloud technologies and practical tasks I have studied. This activity adds documentation about containers, Docker commands, Nginx, and container lifecycle management, along with screenshots as evidence of the work. |
