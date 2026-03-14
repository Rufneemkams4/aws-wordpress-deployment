# aws-wordpress-deployment
Deploying WordPress on AWS EC2 using Linux, Apache, MySQL, PHP

# AWS WordPress Deployment Project

## Overview

This project demonstrates deploying a WordPress website on a Linux server hosted on AWS EC2. The goal was to practice cloud infrastructure deployment and Linux web server administration.

## Technologies Used

AWS EC2
Linux
Apache
MySQL
PHP
SSH

## Skills Demonstrated

- Cloud server deployment
- Linux server configuration
- Web server setup
- Database configuration
- Troubleshooting services
- SSH remote administration

## Deployment Steps

Launch EC2 instance.

Connect via SSH:

ssh ec2-user@server-ip

Update packages:

sudo yum update

Install Apache:

sudo yum install httpd

Start Apache:

sudo systemctl start httpd

Enable Apache:

sudo systemctl enable httpd

Install MySQL:

sudo yum install mysql-server

Install PHP:

sudo yum install php php-mysql

Deploy WordPress files.

## Service Management

Check Apache:

systemctl status httpd

Restart service:

systemctl restart httpd

## Troubleshooting Practice

Verified service status
Checked configuration files
Verified permissions
Restarted services

## Lessons Learned

This project helped me understand how cloud servers are deployed and managed and how Linux services support web infrastructure.

## Career Relevance

This project demonstrates skills used in:

- Systems Administration
- Cloud Infrastructure roles
- DevOps support roles
- IT Operations
