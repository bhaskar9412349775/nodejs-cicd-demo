# Node.js CI/CD with GitHub Actions & Docker

This project demonstrates how to automate the build and deployment of a simple Node.js application using a CI/CD pipeline with GitHub Actions and Docker.

## Features

- Simple Node.js application
- Dockerized application
- GitHub Actions pipeline:
  - Installs dependencies
  - Builds Docker image
  - Pushes image to Docker Hub

## Technologies Used

- Node.js
- Docker
- Github
- GitHub Actions

## CI/CD Workflow

On every push to the `main` branch:

1. The code is checked out.
2. Dependencies are installed via `npm ci`.
3. A Docker image is built and tagged.
4. The image is pushed to Docker Hub.

## Docker Image

The image will be available on Docker Hub: 
 - docker pull bhaskar2001/nodejs-cicd-demo

