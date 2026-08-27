# Cloud Infrastructure Components

## Compute Resources
- *Purpose:* Executes applications, processes data, and runs workloads — the "processing power."
- *Importance in Cloud:* Allows on-demand scaling of processing capacity without buying physical hardware.
- *In KillerCoda:* The vCPU cores and CPU model reported by /proc/cpuinfo represent the virtual compute resources assigned to this cloud instance.

## Storage Resources
- *Purpose:* Stores operating system, applications, and user data persistently.
- *Importance in Cloud:* Enables durable data storage, volume attachment, and independent scaling of storage from compute.
- *In KillerCoda:* The disk partitions (/dev/sda*) and mounted file systems represent block storage attached to this virtual server.

## Networking Resources
- *Purpose:* Enables connectivity to the internet, other servers, and internal services; assigns IP addresses.
- *Importance in Cloud:* Facilitates access, security segmentation, and communication between distributed cloud components.
- *In KillerCoda:* The network interfaces and IP address shown by ip addr represent the virtual network interface and cloud network attachment.

## Operating System
- *Purpose:* Manages hardware/software resources and provides services to applications.
- *Importance in Cloud:* Linux is the dominant OS in cloud — lightweight, secure, stable, and compatible with containers and cloud tools.
- *In KillerCoda:* Ubuntu runs as the base layer — abstracting physical hardware and allowing cloud provisioning as a standardized image.
