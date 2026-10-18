# Firewall Configuration Documentation

## Commands Used

### Command to allow SSH
sudo ufw allow ssh
This command permanently opens port 22 so administrators can securely connect and manage the server remotely via SSH.

## Set Default Deny Policy
sudo ufw default deny incoming
sudo ufw default allow outgoing
These rules set the firewall to automatically block all unsolicited incoming traffic while letting the server freely make connections outward for updates and services.

## Allow Port 8080
sudo ufw allow 8080/tcp
This specifically permits legitimate TCP traffic on port 8080 so users can access the web application without opening extra unnecessary ports.

## What Happens if UFW Is Enabled Before Allowing SSH?

If you enable the firewall before allowing SSH, you will immediately lose your remote connection and get locked out of the server because port 22 will be blocked before you can grant access.
