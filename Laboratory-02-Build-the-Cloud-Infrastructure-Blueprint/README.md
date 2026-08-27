
# Laboratory Activity 2: Build the Cloud Infrastructure Blueprint

## Mission Overview
This laboratory activity simulates the planning phase of a cloud deployment. As a cloud engineer, I investigated a Linux cloud environment, identified infrastructure components, compared major cloud providers, and designed a simple architecture — all to produce technical documentation for a proposed cloud migration.

## Objectives
- Explain the major components of cloud infrastructure.
- Inspect hardware and software resources in a Linux cloud environment.
- Differentiate compute, storage, networking, and identity resources.
- Document relationships between infrastructure components.
- Create professional technical documentation using Markdown.
- Build a structured GitHub Cloud Computing Portfolio.

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
