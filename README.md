# Queue Management System Deployment

## Introduction
This document describes the deployment of the Queue Management System (QMS) in local environment.

## Prerequisites
Make sure you have the following installed:
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Deployment
1. Clone the repository
    ```bash
    git clone https://github.com/new-kafka/deployment
    ```

2. Pull the latest images
    you can pull the latest images from Github Container Registry by running the following command:
    ```bash
    docker login ghcr.io -u <username> -p <token>
    docker-compose pull
    ```

3. Start the services
    ```bash
    docker-compose up -d
    ```


