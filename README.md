# Secure CI/CD Pipeline with AWS, Docker, and Jenkins
This project implements an automated CI/CD pipeline using Docker, Jenkins, GitHub, and AWS.  
The pipeline automates application build, testing, security vulnerability scanning, and deployment.

## Overview
The pipeline integrates Docker containerization, Jenkins automation, and Snyk security scanning to create a secure DevOps workflow for deploying a Node.js application.

## CI/CD Pipeline
GitHub > Jenkins Pipeline > Build > Test > Security Scan (Snyk) > Docker Image > Deploy

## Technologies
- Jenkins  
- Docker  
- Docker Compose  
- AWS  
- Node.js  
- GitHub  
- CI/CD  
- Snyk 

## Repository Structure
Project2-Compose
├── docker-compose.yml
├── docker-compose-stable.yml
├── Dockerfile.node16-snyk
├── Dockerfile.node16-snyk-slim
├── jenkins-casc.yaml
└── README.md


## Run the Project
Start the Jenkins CI/CD environment:
docker-compose up -d

Access Jenkins:
http://localhost:8080 


## Author
Sithumini Jayasinghe  
Master of Computing – Curtin University
