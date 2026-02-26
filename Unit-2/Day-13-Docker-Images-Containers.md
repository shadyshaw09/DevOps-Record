Day 13 - Docker Images and Containers
Date:
22-02-2026

Objective:
To understand Docker images and containers and how they are used.

Introduction:
In Docker, an Image is a lightweight, standalone package that contains everything needed to run an application.
A Container is a running instance of a Docker image.

Docker Image:
- Read-only template
- Contains application code and dependencies
- Used to create containers

Command practiced:
docker images

Docker Container:
- Running instance of an image
- Can be started, stopped, and removed
- Isolated from other containers



Commands practiced:
docker run image_name  
docker ps  
docker ps -a  
docker stop container_id  
docker rm container_id  

Practical Activity:
- Pulled nginx image using:
docker pull nginx

Ran container using:
docker run -d -p 8080:80 nginx



Checked running containers:
docker ps



Stopped container:
docker stop container\_id

Difference Between Image and Container:



Image:
Blueprint of application



Container:
Running application instance

Importance in DevOps:
- Images ensure consistency
- Containers allow scalable deployment
- Used in CI/CD pipelines

Conclusion:
Today I learned the difference between Docker images and containers and practiced running and managing containers.

