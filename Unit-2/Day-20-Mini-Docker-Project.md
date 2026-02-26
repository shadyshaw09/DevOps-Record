Day 20 - Mini Docker Project
Date: 29-02-2026

Objective: To implement a mini project using Docker by deploying a custom web application.

Project Title: Deploying a Custom Nginx Web Server using Docker

Project Description:

In this project, we created a custom web page and deployed it using Docker and Nginx.
The goal was to understand Dockerfile creation, image building, container deployment, and port mapping.

Steps Performed:
1. Created a project folder.
2. Created index.html file.
3. Created Dockerfile.
4. Added following content in Dockerfile:



FROM nginx

COPY index.html /usr/share/nginx/html



5. Built Docker image using:
docker build -t custom-nginx:v1 .

6. Ran container using:
docker run -d -p 8080:80 custom-nginx:v1

7. Opened browser and accessed:
http://localhost:8080

Output:
The custom web page was successfully displayed in the browser.

Tools Used:

- Docker Desktop
- Docker CLI
- Nginx Image
- PowerShell
- Web Browser

Learning Outcomes:

- Understood Dockerfile structure
- Built custom Docker image
- Ran and managed containers
- Practiced port mapping
- Verified application deployment

Conclusion: Today I successfully completed a mini Docker project by building and deploying a custom Nginx web server. This project helped me understand real-world Docker implementation in DevOps environments.

