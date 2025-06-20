# AWS EC2 Static Website Setup

## Steps Followed

1. Launched EC2 instance (Ubuntu, t2.micro, Free Tier)
2. Configured security group to allow:
   - Port 22 (SSH)
   - Port 80 (HTTP)
3. Connected to EC2 using SSH
4. Installed Nginx:
   sudo apt update
   sudo apt install nginx -y
5. Removed default web page:
   sudo rm /var/www/html/index.nginx-debian.html
6. Created custom index.html
7. Opened browser to:  
http://3.108.228.2