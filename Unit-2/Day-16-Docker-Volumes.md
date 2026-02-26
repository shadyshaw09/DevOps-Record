Day 16 - Docker Volumes
Date:25-02-2026

Objective:
To understand Docker volumes and persistent storage in containers.

Introduction:
By default, data inside a Docker container is temporary. When a container is removed, all its data is lost.
Docker Volumes are used to store data permanently outside the container.

Why Volumes Are Important:
- Persist data even if container is deleted
- Share data between containers
- Improve performance
- Manage database storage

Types of Storage in Docker:
1. Volumes
2. Bind Mounts
3. tmpfs Mounts

Docker Volume Commands Practiced:
docker volume create myvolume  
Creates a new volume
docker volume ls  
Lists all volumes
docker volume inspect myvolume  
Displays volume details
docker volume rm myvolume  
Removes a volume

Running Container with Volume:
docker run -d -v myvolume:/data nginx
This mounts the volume inside the container.

Practical Activity:
- Created a Docker volume
- Attached volume to container
- Verified persistent data storage

Importance in DevOps:
- Used for database containers
- Ensures data persistence
- Essential for production deployments

Conclusion:
Today I learned how Docker volumes provide persistent storage and prevent data loss in containers.

