This is for backend

### Build the dockerfile
docker build -t my-nodejs-app .  
### Run the container image
docker run -d -t my-nodejs-app sleep infinity
### Get into the running container
docker exec -it <container_id> /bin/bash 
### Stop the container
docker stop <container_id>
