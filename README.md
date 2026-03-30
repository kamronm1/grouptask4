This project demonstrates how to set up an automated process for deploying a Java application to Docker Hub using GitHub Actions. You will create a simple Java application, compile it, and package it into a Docker image using a Dockerfile and the Amazon Corretto latest base image from Docker Hub.

Next, you will connect the project to a GitHub repository and configure a workflow with GitHub Actions that automatically builds and deploys the Docker image whenever you push code changes. The workflow securely logs into Docker Hub using stored secrets, DOCKER_USERNAME and DOCKER_PASSWORD, builds the image with a version tag, and uploads it to your Docker Hub account.

Once everything is set up, you can use Docker commands to pull and run the image on any machine that supports Docker. This process creates a CI CD pipeline that automates builds and deployments, reduces manual work, and helps ensure your application is delivered consistently.
