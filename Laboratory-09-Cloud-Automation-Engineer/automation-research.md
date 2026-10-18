# Automation Research

## Bash Script
A Bash script is a plain-text file containing a sequence of Linux commands that the Bash shell can run automatically, instead of typing each command manually. The #!/bin/bash line at the top, called the shebang, tells the system exactly which shell program should interpret and execute the script, ensuring it runs with Bash syntax and behavior.

## Variables
Variables like $BACKUP_DIR store values so you can use a short, consistent name instead of repeating the full path every time. This makes the script easier to read, faster to update — you change the path in only one place — and less prone to typos when the same location is used multiple times.

## Cron Job
A cron job is a built-in Linux feature that runs commands or scripts automatically at set times, dates, or intervals without someone starting them manually. It is essential in cloud operations because it handles routine tasks like backups, updates, and maintenance reliably at scale across many servers, removing delays and mistakes from human schedules.
