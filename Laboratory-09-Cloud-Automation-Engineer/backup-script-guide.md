# Backup Script & Cron Schedule Guide

## Full Backup Script Code
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p $BACKUP_DIR

# Compress the source directory into a tarball (.tar.gz)
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"

## What chmod +x Did

The command chmod +x backup.sh updated the file's permissions to mark it as executable, so Linux recognizes it as a program that can run directly instead of treating it as a plain text file. Without this step, the system blocks execution as a safety measure, showing "Permission denied."

## Cron Schedule

cron
0 2 * * * /root/backup.sh
The five time fields mean:

| Field | Value | Meaning |
|---|---|---|
| Minute | 0 | At minute zero |
| Hour | 2 | At 2 AM |
| Day of Month | * | Every day of the month |
| Month | * | Every month |
| Day of Week | * | Every day of the week |

The script runs automatically at 2:00 AM every single day
