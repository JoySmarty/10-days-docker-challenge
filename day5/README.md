# Day 5 – Docker Networking 🐳

## What I learned
- Containers can communicate using Docker networks
- Docker provides internal DNS (name-based communication)
- Networks isolate and connect services

## What I did
- Created a custom Docker network
- Ran two containers (frontend and backend)
- Connected both containers to the same network
- Tested communication using curl

## Commands used
docker network create my-network
docker run -d --name backend --network my-network nginx
docker run -d --name frontend --network my-network nginx
docker exec -it frontend bash
curl http://backend

## Outcome
Successfully enabled communication between containers using Docker networking 🚀
