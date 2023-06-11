Docker
- Build image - `docker build -f Dockerfile -t nodeapi .`
- List down the images - `docker images`
- Run the image - `docker run -p 3000:3000 -d nodeapi`
- Print the output - `docker ps`
- Executing command - `docker exec -it <container id> /bin/bash`
- Shutdown the container - `docker kill <container id>`
- Deleting the image - `docker rmi <image id>`
