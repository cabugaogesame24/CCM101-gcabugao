# Mission Reflection

Checking the host server's resources is necessary even when containers run well because every container shares the host's CPU, memory, and disk. A container may work fine with few users, but when traffic rises, the host can run out of resources and all services will slow down or fail. Setting a baseline confirms the system has enough capacity to handle growth.

When a user cannot log in, docker logs shows the full request trail. It reveals if the login reached the application, if credentials were rejected, if a connection failed, or if a setting blocked access. This clear record points straight to the cause instead of guessing.

Logs and metrics serve different purposes: logs are text records of individual events — like a request or an error — that show what happened. Metrics are ongoing measurements — like CPU percentage or memory use — that show how well the system is running over time. Logs help find specific incidents; metrics show overall performance and trends.

Large companies monitor thousands of containers using tools like Prometheus and Grafana. Prometheus automatically collects performance data from every container. Grafana displays it all on shared dashboards. These tools also send alerts when limits are crossed, so teams can fix issues quickly without checking each container separately.

This activity improved my Linux troubleshooting skills. I now follow a clear order: check memory, disk, and processes first before looking at the application. I can tell if an issue comes from the host, the network, or the container. I also know when to use logs to find specific errors and when to use metrics to check overall system health.
