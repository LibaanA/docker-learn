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

## Docker – Key Concepts and Skills Gained

Docker is a containerisation platform that enables applications and their dependencies to be packaged into lightweight, portable and consistent environments. Through hands-on practice, I developed an understanding of Docker's core concepts and how they support modern DevOps workflows.

The key skills and concepts I gained include:

- Containers and Images: Understanding how Docker images act as reusable blueprints and how containers are created as running instances of those images.

- Dockerfiles: Learning to create custom Docker images using instructions such as `FROM`, `RUN`, `COPY` and `CMD` to define application environments and dependencies.

- Docker CLI Commands: Gaining practical experience managing containers and images using commands including `docker run`, `docker ps`, `docker images`, `docker stop` and `docker exec`.

- Container Networking and Port Mapping: Configuring network connections, exposing application ports and enabling communication between services running in separate containers.

- Persistent Data Storage: Implementing Docker volumes to ensure
