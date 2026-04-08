# Day 4 – Docker Volumes 🐳

## What I learned
- Containers are ephemeral (data is lost when removed)
- Docker volumes allow persistent storage
- How to mount local directories into containers

## What I did
- Ran an Nginx container with a volume
- Linked my local folder to the container
- Created and edited an HTML file
- Saw live updates in the browser

## Command used
docker run -d -p 8083:80 --name my-volume-nginx -v ${PWD}:/usr/share/nginx/html nginx

## Outcome
Successfully used Docker volumes to persist and update data in real-time 🚀
