# Ansible-Task
Ansible Roles Task


Welcome to the Automated Docker and Nginx Setup project! 🚀 This repository contains Ansible roles to streamline the process of setting up Docker and running an Nginx container on your Ubuntu VM.

🛠️ Features:
Docker Setup: This role ensures your Ubuntu VM is ready to run Docker. It handles everything from updating package indices to installing Docker, including the necessary prerequisites and configurations.

Nginx Container Deployment: Once Docker is installed, this role takes over to pull the latest Nginx image from Docker Hub and starts an Nginx container. It maps port 3000 on your host to port 80 in the container, so you can easily access your web server.
