Day 15 - Dockerfile
Date:
24-02-2026

Objective:
To understand Dockerfile structure and build custom Docker images.
Introduction:

A Dockerfile is a text file that contains instructions to build a Docker image automatically.
It allows us to define the base image, dependencies, configurations, and commands required to run an application.
Basic Dockerfile Instructions:

1. FROM  
Defines the base image.

Example:
FROM nginx



2. COPY  
Copies files from local system to container.

Example:
COPY index.html /usr/share/nginx/html


3. RUN  
Executes command during image build.


4. EXPOSE  
Specifies port number.


Example:
EXPOSE 80



5. CMD  
Defines default command to run container.

Practical Activity:
Created a Dockerfile for custom nginx page.

Example:
FROM nginx  
COPY index.html /usr/share/nginx/html  
Built image using:
docker build -t custom-nginx:v1 .
Ran container:
docker run -d -p 8080:80 custom-nginx:v1
Accessed application in browser using:

http://localhost:8080

Importance in DevOps:

- Enables automated image creation
- Supports CI/CD pipelines
- Ensures reproducible builds

Conclusion:
Today I created a custom Docker image using a Dockerfile and deployed it using Docker commands.

