Day 14 - Docker Basic Commands
Date: 23-02-2026

Objective:
To practice essential Docker commands used for managing images and containers.

Introduction:
Docker provides various commands to manage images, containers, networks, and volumes. Today we practiced commonly used Docker CLI commands.

Docker Commands Practiced:

1. docker pull nginx  
Downloads image from DockerHub.
2. docker images  
Lists all downloaded images.
3. docker run nginx  
Runs a container from an image.
4. docker run -d -p 8080:80 nginx  
Runs container in detached mode with port mapping.
5. docker ps  
Shows running containers.
6. docker ps -a  
Shows all containers (running and stopped).
7. docker stop container\_id  
Stops a running container.
8. docker start container\_id  
Starts a stopped container.
9. docker rm container\_id  
Removes a container.
10. docker rmi image\_name  
Removes a Docker image.

Practical Performed in Class:

- Pulled nginx image
- Ran container with port mapping
- Accessed application in browser using localhost:8080
- Stopped and removed container

Importance in DevOps:

- Helps in container lifecycle management
- Used in automation scripts
- Essential for deployment workflows

Conclusion:
Today I practiced essential Docker commands for image and container management.

