# docker-101

Installing docker

https://docs.docker.com/engine/installation/

- Running nginx server - `docker run nginx`
- Running nginx server in background - `docker run -d nginx`
- Logging in to docker container - `docker run -it nginx /bin/bash`
- List running docker containers - `docker ps`
- List all docker containers - `docker ps -all`
- List all docker images - `docker images`
- Remove docker image - `docker rmi image_name`
- Port mapping - `docker run -p host_port:container_port image_name`
