# Unit 2 Practicals
# DevOps – Unit 2

## Overview

This unit demonstrates practical implementation of Docker containerization including building images, running containers, working with databases, using GitHub Container Registry, and managing Docker images with Docker Hub.

---

# Practical 02

## Aim

Demonstrate how to build a Docker image using Ubuntu and execute an echo command when the container runs.

## Steps

1. Create a project directory.
2. Create a Dockerfile.
3. Use Ubuntu as the base image.
4. Install required packages (php and nano).
5. Build the Docker image.
6. Run the container.
7. Verify PHP installation.

## Result

A Docker image was successfully created using Ubuntu and the container executed an echo command when run.

---

# Practical 03

## Aim

Create and run a MySQL container and access the database inside the container.

## Steps

1. Create a Dockerfile using MySQL 8.x.
2. Set environment variables for root password and database.
3. Build the Docker image.
4. Run the container.
5. Access the container using docker exec.
6. Display databases and switch to mydatabase.

## Result

A MySQL container was successfully created and the database was accessed inside the container.

---

# Practical 05

## Aim

Work with GitHub Container Registry (GHCR) by building and pushing Docker images.

## Steps

1. Create project directory.
2. Create index.html and Dockerfile.
3. Build Docker image.
4. Login to GHCR.
5. Push image to GitHub Container Registry.
6. Remove image locally.
7. Pull image from GHCR.

## Result

The Docker image was successfully pushed to GitHub Container Registry and pulled back to the local machine.

---

# Task 05

## Aim

Demonstrate how to pull a Docker image, tag it, push it to Docker Hub, install software inside a running container, verify installation, and save the container changes using Docker commit.

## Steps

1. Pull Alpine Linux image.
2. Tag the image.
3. Login to Docker Hub.
4. Push image to Docker Hub.
5. Run container interactively.
6. Update package index.
7. Install PHP.
8. Verify PHP installation.
9. Exit container.
10. Commit container changes to a new image.

## Result

The Alpine image was pulled, modified by installing PHP, and saved as a new Docker image using Docker commit.
