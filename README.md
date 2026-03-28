# AWS ECS Docker Deployment Project

## Project Overview
This project demonstrates the deployment of a containerized Node.js application using AWS services like ECS, ECR, EC2, and CloudWatch.

## Tech Stack
- AWS EC2 (Virtual Server for setup and SSH access)
- AWS ECS (Elastic Container Service)
- AWS ECR (Elastic Container Registry)
- Docker
- Git and GitHub
- AWS CloudWatch (Monitoring)
- Node.js (Application - Frontend and Backend)

## Architecture
User → EC2 (SSH Access) → ECS Service → Docker Container → Logs in CloudWatch

## Workflow
1. Connected to EC2 instance using SSH  
2. Installed Docker and configured AWS CLI  
3. Cloned the application repository from GitHub  
4. Built Docker image of the Node.js application  
5. Pushed Docker image to AWS ECR  
6. Created ECS cluster and service to run the container  
7. ECS pulled the image from ECR and deployed the container  
8. Logs monitored using AWS CloudWatch  

## Screenshots

### ECS Service
![ECS](screenshots/ecs.png)

### ECR Repository
![ECR](screenshots/ecr.png)

### CloudWatch Logs
![Logs](screenshots/cloudwatch.png)

## Features
- Containerized deployment using Docker  
- Managed container orchestration using ECS  
- Centralized logging with CloudWatch  
- Secure remote access using EC2 and SSH  

## Learnings
- Hands-on experience with Docker and AWS services  
- Understanding of container deployment using ECS  
- Image management using ECR  
- Monitoring and debugging using CloudWatch  

## Base Application
This project uses a Node.js application for both frontend and backend, originally created by:
https://github.com/LondheShubham153/node-todo-cicd

I have used this application as a base and implemented:
- Docker containerization  
- Image management using ECR  
- Deployment using ECS  
- Monitoring using CloudWatch  

## Author
Sapna Kumari
