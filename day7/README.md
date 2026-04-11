# Day 7 – Environment Variables in Docker 🐳

## What I learned
- How to pass environment variables into containers
- Why environment variables are important in real applications
- How to inspect environment variables inside a container

## What I did
- Built a Docker image using nginx
- Ran a container with environment variables
- Verified the variables inside the container

## Commands used
docker build -t env-app .
docker run -d -p 8085:80 --name env-container -e ENV=PROD env-app
docker exec -it env-container env

## Outcome
Successfully passed and inspected environment variables inside a container 🚀
