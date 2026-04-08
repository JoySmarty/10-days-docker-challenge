# Day 3 – Building My First Docker Image 🐳

## Overview
Today, I moved from just running containers to actually building my own Docker image using a Dockerfile.

## What I Learned
- What a Dockerfile is
- How to build a custom Docker image
- How to serve a web page using Nginx inside a container
- How Docker copies files into a container
- How to debug issues during image build

## What I Did
- Created a simple HTML file
- Wrote a Dockerfile using Nginx as the base image
- Built a custom Docker image
- Ran the container and accessed it via the browser

## Dockerfile Used
```dockerfile
FROM nginx
COPY index.html /usr/share/nginx
