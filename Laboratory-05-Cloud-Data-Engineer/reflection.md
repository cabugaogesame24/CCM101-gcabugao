# Reflection

This laboratory activity helped me understand why object storage is useful for storing a large number of files. Object storage is better for storing millions of photos because it is made for files like images, videos, and backups. It stores these files as objects inside a bucket. It is also useful when an application needs to store more and more files over time.

Docker made it easier for me to deploy MinIO because I did not need to install and set up everything manually. I only had to use the given Docker command with the required ports, name, and environment variables. Docker then created the MinIO container and allowed it to run properly. This made the setup faster and easier compared to doing the installation step by step.

I also learned what a bucket means in cloud storage. A bucket is a place where objects or files are stored and organized. In this activity, I created a bucket named client-photos. I then uploaded a sample file to the bucket to check if the MinIO storage was working correctly.

For large companies, I think they can protect their object storage data by keeping multiple copies of their files. They can also store the copies on different servers or locations. Backups and data replication can help make sure that files are still available even if one server has a problem or crashes. This helps reduce the chance of losing important data.

As I worked on this activity, I became more familiar with using the Linux command line. I was able to follow the commands, run Docker, and check the MinIO container using docker ps. I also learned that small commands can be used to check and manage services. Because of this activity, I feel more comfortable using the command line for basic cloud and Docker tasks.
