# Day 8 – Dockerizing an Application 🐳

## What I learned
- How to structure an application for Docker
- How to copy entire directories into a container
- How real applications are packaged using Docker

## What I did
- Created an app folder with HTML
- Built a Docker image using that folder
- Ran the container and accessed it in the browser

## Commands used
docker build -t day8-app .
docker run -d -p 8086:80 --name day8-container day8-app

## Outcome
Successfully dockerized a structured application 🚀
