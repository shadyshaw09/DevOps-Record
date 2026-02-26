Day 18 - Docker Compose
Date: 27-02-2026

Objective: To understand Docker Compose and how to manage multi-container applications.

Introduction: Docker Compose is a tool used to define and manage multi-container Docker applications using a YAML file.
Instead of running multiple docker run commands, we define services in a docker-compose.yml file.

Why Docker Compose is Needed:

- Simplifies multi-container setup
- Manages networks automatically
- Manages volumes easily
- Starts all services with one command

docker-compose.yml Structure:
Example:

version: '3'
services:
web:
image: nginx
ports:
"8080:80"

Important Docker Compose Commands:

docker-compose up  
Starts services



docker-compose up -d  

Starts in detached mode



docker-compose down  

Stops and removes services



docker-compose ps  

Lists running services

Practical Activity:

- Created docker-compose.yml file

- Defined nginx service

- Started service using docker-compose up

- Accessed application on localhost:8080

Importance in DevOps:



- Used for microservices

- Simplifies deployment

- Integrates with CI/CD pipelines

- Used in production environments


Conclusion:



Today I learned how Docker Compose simplifies managing multi-container applications using a YAML configuration file.

