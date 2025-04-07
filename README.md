# Node.js Docker CI/CD Pipeline

This project demonstrates a basic CI/CD pipeline for a Node.js application using GitHub Actions and Docker.

## Tech Stack

- Node.js
- Docker
- GitHub Actions

## CI/CD Workflow

The GitHub Actions workflow is located at `.github/workflows/main.yml`. It performs the following steps:

1. **Checkout code**
2. **Build Docker image**
3. **Push image to DockerHub**

The pipeline triggers automatically on every push to the `main` branch.

## DockerHub

Docker images are pushed to:  
`https://hub.docker.com/repository/docker/gouriob/your-image-name`

> Replace `your-image-name` with the actual image name you're using.




