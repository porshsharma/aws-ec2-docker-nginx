# Docker Nginx Deployment on AWS EC2

A containerized Nginx web server deployed on an AWS EC2 cloud virtual machine as part of my Cloud Computing Internship.

## Project Overview

The objective of this project was to install Docker on an AWS EC2 Ubuntu VM, run an Nginx container and expose it to the internet.

## Technologies Used

- Amazon EC2
- Ubuntu
- Docker
- Nginx
- Linux
- AWS Security Groups

## Architecture

Internet
↓
AWS EC2
↓
Ubuntu
↓
Docker
↓
Nginx Container
↓
Port 80

## Workflow

1. Created an AWS EC2 instance.
2. Installed Docker on Ubuntu.
3. Started and verified the Docker service.
4. Pulled the official Nginx image.
5. Created an Nginx Docker container.
6. Mapped EC2 port 80 to container port 80.
7. Configured HTTP access through the security group.
8. Tested the Nginx webpage using the EC2 public IP.

## Docker Image

nginx:latest

## Container Name

cloud-vm-nginx

## Port Mapping

80:80

## Docker Command

docker run -d --name cloud-vm-nginx -p 80:80 nginx

## Verify Container

docker ps

## Live Project

http://3.109.108.123

## What I Learned

- Docker installation
- Docker images and containers
- Nginx deployment
- Port mapping
- Container networking
- AWS EC2 deployment
- Cloud-based containerization

## Screenshots

The project evidence collage contains screenshots of the EC2 instance, security group, Docker installation, Nginx image, running container and public Nginx webpage.

## Project Status

Completed
