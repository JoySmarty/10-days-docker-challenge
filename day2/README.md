# Day 2 – Running & Managing Containers 🐳

## What I learned
- How to run real containers using Docker
- How port mapping works
- Container lifecycle (run, stop, start, remove)

## What I did
- Ran an Nginx container
- Accessed it via browser (localhost:8080)
- Stopped and restarted the container
- Fixed port conflict issue
- Removed the container

## Commands used
docker run -d -p 8080:80 --name my-nginx nginx
docker ps
docker stop my-nginx
docker start my-nginx
docker rm my-nginx

## Outcome
Successfully ran and managed a real containerized web server 🎉
