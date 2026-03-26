# Docker React & Fullstack Examples

A collection of Dockerized applications ranging from simple React projects to full MERN stacks.

## Project Structure

- `hello-docker/`: Introduction to Docker and basic image creation.
- `react-docker/`: Basic React application structure with Docker.
- `next-docker/`: Next.js application with Docker configuration.
- `mern-docker/`: Full-stack MERN application orchestrated with Docker Compose.
- `vite-project/`: Modern React setup with Vite and Docker.

## Key Concepts
- **Dockerfile**: Defines the environment and build process for each service.
- **Docker Compose**: Orchestrates multi-container applications (e.g., MERN).
- **Multi-stage Builds**: Optimizing image size for production.

## Getting Started

To run a specific project:
1.  Navigate to the directory:
    ```bash
    cd mern-docker
    ```
2.  Start the containers:
    ```bash
    docker-compose up --build
    ```

## Prerequisites
- Docker & Docker Compose installed locally.