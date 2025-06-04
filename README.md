# AWS EC2 Instance Setup and Automation

This repository provides a step-by-step guide for launching and configuring an EC2 instance on AWS. It includes automation scripts and setup instructions to help beginners and entry-level cloud engineers understand the basics of EC2 management.

##  Project Objective

To demonstrate hands-on skills in launching, configuring, and automating an Amazon EC2 instance, including setting up a web server, managing firewall rules (security groups), and using basic scripting for automation.

## Key Features

- Launch an EC2 instance (Ubuntu/Linux)
- SSH into your instance securely using key pair
- Install Apache web server automatically
- Host a basic static webpage
- Configure security group rules (HTTP, SSH)
- Assign and use Elastic IP
- Create Amazon Machine Image (AMI)
- Automate setup using user data scripts

## Technologies Used

- AWS EC2
- Linux (Ubuntu)
- Bash scripting
- Apache Web Server
- Git & GitHub
- AWS Console
- (Optional) AWS CLI

## Repository Structure

### install apache server
- yum update -y
- yum install httpd -y
# start and enable service
- service httpd start
- chkconfig httpd on




