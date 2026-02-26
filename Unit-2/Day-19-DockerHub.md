Day 19 - DockerHub

Date: 28-02-2026

Objective: To understand DockerHub and how to push and pull images from a remote registry.

Introduction: DockerHub is a cloud-based registry service used to store and share Docker images.

It allows developers to upload their custom images and download official images created by others.

What is a Docker Registry?
A Docker Registry is a storage system for Docker images.

Examples:
- DockerHub (public registry)
- Private registry

Commands Practiced:
docker login  
Logs into DockerHub account.


docker tag image_name username/image_name:tag  
Tags image for DockerHub.



docker push username/image_name:tag  
Pushes image to DockerHub.



docker pull username/image_name:tag  
Downloads image from DockerHub.

ractical Activity:

- Created DockerHub account
- Logged in using docker login
- Tagged custom nginx image
- Pushed image to DockerHub
- Pulled image on another system

Importance in DevOps:


- Enables image sharing
- Used in CI/CD pipelines
- Supports versioning of images
- Allows team collaboration


Conclusion: Today I learned how DockerHub works and practiced pushing and pulling Docker images from a remote registry.

