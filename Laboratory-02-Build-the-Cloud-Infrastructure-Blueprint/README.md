
# Laboratory Activity 2: Build the Cloud Infrastructure Blueprint

## Mission Overview
Congratulations! My onboarding has been successfully completed, and my Cloud Computing Portfolio has been approved by my supervisor.

CloudNova Technologies has assigned me to my first official project. Before deploying cloud services, I need to understand the infrastructure that supports modern cloud computing. My mission is to investigate the components of cloud infrastructure and identify how compute, storage, networking, and identity services work together.

Using the KillerCoda Playground, Linux tools, official cloud documentation, and my GitHub Cloud Computing Portfolio, I will complete a series of engineering tasks that simulate the planning phase of a cloud deployment. I will also document my findings as if I were preparing technical documentation for a client.

Objectives
At the end of this laboratory activity, I should be able to:

Explain the major components of cloud infrastructure.
Investigate the hardware and software resources available in a Linux environment.
Differentiate compute, storage, networking, and identity resources.
Interpret the relationship between cloud infrastructure components.
Create professional technical documentation using Markdown.
Continue building a structured GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components
- *Compute* — Virtual CPUs and memory that execute workloads.
- *Storage* — Block, object, and file storage for data persistence.
- *Networking* — Virtual networks, IP addressing, and connectivity.
- *Identity & Access Management* — Authentication, authorization, and security controls.

## Tools Used
- KillerCoda Cloud Playground (Linux terminal)
- GitHub (version control & portfolio hosting)
- Web browser (cloud provider documentation research)
- Markdown editor (documentation)
- Diagram tool (architecture design)

## Linux Commands Executed
```bash
lsb_release -a          # Display OS details
uname -r                # Show kernel version
cat /proc/cpuinfo       # View CPU information
nproc                   # Count CPU cores
free -h                 # Show memory usage
df -h                   # Show disk usage
mount                   # List mounted file systems
hostname                # Display system name
ip addr show            # Display network interfaces & IPs
