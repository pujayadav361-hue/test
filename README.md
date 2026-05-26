# My AWS Small Application

This is a simple HTML application hosted on AWS EC2 Linux server.

## Files
- index.html

## Technologies Used
- AWS EC2
- Apache HTTP Server
- Git
- GitHub

## How to Run

Install Apache:

sudo yum install httpd -y

Start service:

sudo systemctl start httpd

Copy application:

sudo cp index.html /var/www/html/

Open in browser:

http://SERVER_PUBLICIP
