# index

Run a Container:

bash
Copy code
docker run IMAGE [COMMAND]
List Containers:

bash
Copy code
docker ps [-a]
Stop Container:

bash
Copy code
docker stop CONTAINER_ID
Remove Container:

bash
Copy code
docker rm CONTAINER_ID
Inspect Container:

bash
Copy code
docker inspect CONTAINER_ID
Managing Images:
List Images:

bash
Copy code
docker images
Pull Image:

bash
Copy code
docker pull IMAGE[:TAG]
Remove Image:

bash
Copy code
docker rmi IMAGE_ID
Tag Image:

bash
Copy code
docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]
Managing Networks:
List Networks:

bash
Copy code
docker network ls
Create Network:

bash
Copy code
docker network create NETWORK_NAME
Inspect Network:

bash
Copy code
docker network inspect NETWORK_ID
Connect Container to Network:

bash
Copy code
docker network connect NETWORK_ID CONTAINER_ID
Managing Volumes:
List Volumes:

bash
Copy code
docker volume ls
Create Volume:

bash
Copy code
docker volume create VOLUME_NAME
Remove Volume:

bash
Copy code
docker volume rm VOLUME_NAME
Docker System Management:
System Info:

bash
Copy code
docker info
Clean Up:

bash
Copy code
docker system prune
View Logs:

bash
Copy code
docker logs CONTAINER_ID
Docker Swarm (if applicable):
Initialize Swarm:

bash
Copy code
docker swarm init
Join Swarm:

bash
Copy code
docker swarm join --token TOKEN MANAGER_IP:PORT
List Nodes:

bash
Copy code
docker node ls
Deploy Service:

bash
Copy code
docker service create --name SERVICE_NAME IMAGE
Manage Services:

bash
Copy code
docker service ls
Docker Compose (Bonus):
Docker Compose:
bash
Copy code
docker-compose [OPTIONS] COMMAND [ARGS...]
