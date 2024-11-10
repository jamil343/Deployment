
# Simple Full-Stack Web Application with CI/CD

## Overview

This project is a simple full-stack application with a React frontend and a Node.js backend, containerized with Docker, and deployed using a CI/CD pipeline with GitHub Actions on a Contabo VPS.

## Tech Stack

- **Frontend**: React
- **Backend**: Node.js with Express
- **Containerization**: Docker
- **CI/CD**: GitHub Actions
- **Deployment**: Contabo VPS

## Setup Instructions

### Prerequisites

1. Docker and Docker Compose
2. Node.js and npm
3. GitHub repository with GitHub Actions enabled

### Local Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Build and run the application using Docker Compose:

   ```bash
   docker-compose up --build
   ```

3. Access the frontend at `http://localhost:3000` and backend API at `http://localhost:5000/api`.

### Deployment on Contabo VPS

1. Set up Docker and Docker Compose on the VPS.
2. Ensure SSH access to the VPS is configured and credentials are added to GitHub secrets.
3. Push to `main` branch to trigger the CI/CD pipeline, which will deploy the app on the VPS.

---

### Troubleshooting Guide

- **Docker Issues**: Ensure Docker is running and properly configured.
- **GitHub Actions Failures**: Check GitHub logs for more details on errors.
- **Deployment Errors**: Confirm SSH credentials and permissions are correct.

## Repository

[GitHub Repository Link](https://github.com/your-repo-url)

## Deployment

Access the live application at: `http://your-contabo-ip-address`
