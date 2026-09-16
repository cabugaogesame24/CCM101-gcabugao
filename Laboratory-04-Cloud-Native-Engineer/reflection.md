## Mission Reflection

Working through this lab showed me how different containers are from traditional virtual machines. Docker containers start in seconds because they share the host system’s kernel and only run what the application needs. Installing an OS on a VM takes minutes or longer, sets up a full separate system, and uses much more memory and storage. Containers are lightweight and fast to set up, while VMs are heavier and take more time to boot and configure.

Port mapping with `-p 8080:80` is needed because every container has its own isolated network. The Nginx server runs on port 80 inside the container, but that port is not directly visible from outside. Mapping port 8080 on my computer to port 80 in the container lets me reach the web server through a familiar local address while keeping the container secure and separate from other services.

When I run `docker rm`, the container is permanently deleted. Any files or data created inside that container are also removed and cannot be recovered unless I used a volume to store it separately. This taught me that containers are designed to be temporary — data should be kept outside when it needs to last.

Containerization changes how developers and IT teams work together in a big way. Developers can build and test apps locally inside containers that work exactly the same in production. This removes the common problem of "it works on my machine." Both teams share the same consistent environments, so they can move faster, fix issues sooner, and work more closely together — the core idea of DevOps.

My GitHub portfolio is growing into a clear record of what I can do. Every lab, command, and note I add shows my progress step by step. It is becoming a professional collection of skills that shows I understand cloud-native tools, documentation, and best practices — something I can share confidently.
