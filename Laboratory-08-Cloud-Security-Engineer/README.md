## Mission Overview
This activity puts me in the role of a Cloud Security Engineer tasked with securing an exposed Ubuntu server. I deployed a web application, audited open ports, and configured the Uncomplicated Firewall (UFW) following a Default Deny policy — allowing only SSH and legitimate web traffic — to apply defense in depth and the Principle of Least Privilege.

## Objectives
- Understand the Principle of Least Privilege and Attack Surface concepts
- Audit active network ports on a Linux server
- Configure UFW with a Default Deny policy
- Selectively allow SSH and port 8080 web traffic
- Document all steps using Markdown and GitHub

## Commands Executed
```bash
docker run -d -p 8080:80 --name secure-web-app nginx
curl localhost:8080
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status verbose
sudo ufw status numbered
curl localhost:8080
```
## Skills Learned
- How to deploy and expose a containerized web application
- How to audit and restrict open ports with UFW
- Why Default Deny is the safer starting policy for firewalls
- The importance of ordering rules — allow SSH before enabling the firewall
- Professional security documentation and maintaining a cloud computing portfolio
