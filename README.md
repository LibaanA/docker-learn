This is a Containers Challenge I have participated in

### Containerised Flask Application with Docker, Redis & Nginx

A hands-on DevOps project demonstrating containerisation, multi-container orchestration, service networking, application scaling and reverse proxy configuration using Docker and Docker Compose.

The small project was developed to strengthen my practical understanding of container-based application architecture and DevOps engineering.

## Overview

The objective of this project is to deploy a Python Flask application within a containerised environment and integrate it with Redis and Nginx.

The application includes a page visit counter backed by Redis, allowing multiple Flask instances to access a shared counter.

Docker Compose is used to manage the services and scale the Flask application to three instances.

### Important features used

- Containerisation: Package the Flask application and its dependencies into a Docker image.
- Multi-container architecture: Run Flask, Redis and Nginx as interconnected services.
- Application scaling: Use Docker Compose to create three Flask application instances.
- Reverse proxy: Configure Nginx to route incoming HTTP requests to the application service.
- Shared state: Use Redis to maintain a consistent visit counter across Flask instances.
- Persistent storage: Configure a Docker named volume for Redis data.
