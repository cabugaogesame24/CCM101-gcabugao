# Laboratory 09 — The Cloud Automation Engineer

## Mission Overview
I stepped into the role of a Cloud Automation Engineer to remove human error from routine tasks. A client lost important data because staff forgot to run backups, so my goal was to build a Bash script that automatically compresses and stores application files, then schedule it to run every night at 2:00 AM using Cron — so the process happens without anyone starting it manually.

## Objectives
- Grasp basic Bash scripting structure including variables and commands
- Write and save executable scripts using the nano text editor
- Change file permissions with chmod to make scripts runnable
- Understand and configure Cron scheduling syntax
- Document scripts and schedules in Markdown
- Complete the final chapter of my GitHub Cloud Computing Portfolio

## Commands Executed
mkdir app-data
echo "This is critical client data." > app-data/data.txt
nano backup.sh
./backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
crontab -l
env EDITOR=nano crontab -e
crontab -l

## Skills Learned
- Writing functional Bash scripts with variables and timestamps
- Understanding the shebang line and script execution flow
- Using chmod to control file access and run permissions
- Setting up recurring tasks with crontab syntax
- Building repeatable automation that scales across many servers
