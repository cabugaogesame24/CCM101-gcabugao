# Laboratory 07: Cloud Operations Engineer

## Mission Overview
This activity focuses on server and application observability, working as a Cloud Operations Engineer at CloudNova Technologies ahead of a high‑traffic client launch. Using KillerCoda Playground and Docker, I measured host baseline performance, deployed an Nginx web server, generated both normal and error test traffic, reviewed application logs, and tracked live container resource usage. All work is documented in Markdown and stored in my GitHub Cloud Computing Portfolio.

## Objectives
- Check host CPU, memory, and disk usage with Linux commands.
- Launch an Nginx web server container via Docker.
- Send test requests and locate a 404 error response.
- Extract and examine application access logs.
- Monitor real‑time container CPU, memory, and network activity.
- Save all records in Markdown and push to GitHub.

## Monitoring Commands Executed
| Command | Purpose |
|---|---|
| free -h | Show total and used system memory. |
| df -h / | Check available space on the root disk. |
| top | View running processes and CPU load. |
| docker run -d --name clientwebsite -p 8080:80 nginx | Start Nginx container on port 8080. |
| curl http://localhost:8080 | Send normal web request. |
| curl http://localhost:8080/hidden-admin-page | Request missing page to get 404 error. |
| docker logs clientwebsite | View recorded request logs. |
| docker stats clientwebsite | Show live container resource consumption. |

## Skills Learned
- Linux command‑line system checks
- Deploying and naming Docker containers
- Simulating user web traffic
- Reading and understanding container logs
- Monitoring real‑time performance metrics
- Writing organized Markdown reports
- Managing portfolio on GitHub
