

# List dockers
* docker ps # activly running container
* docker ps -a # list all container
* docker rm <docker_id> # remove  docker image

# Build and Run Dockers
* sudo docker build . -t <image_name>
* sudo docker run <image_name>
    * sudo docker run -d (daemon for backgroud run) -p 80:80(host port:mapped container port) <image_name>
* to get the local IP address of the image
* sudo docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' e6de5ada422c
* sudo docker run -it ubuntu:latest /bin/bash ( ssh to docker interactive)
* sudo docker run -it --rm ubuntu:latest /bin/bash (remove docker after exiting)
* sudo docker exec -it <image_name> /bin/bash # run/ssh to container

# docker logs
* docker logs <image_name> (for display docker logs)
* docker logs -f <image_name> (live logs)
* docker logs --tail 10 <image_name> (tail number of bottom lines)

# Docker HealthCheck
* curl -I <hostname:port>
* HEALTHCHECK --interval=15s --retries=5 --timeout=30s --start-period=30s CMD curl -I -f "http://localhost:8000" || exit 1

# Linking Dockers
* docker run -it --link <image_name> <image_name> /bin/bash

# Commands
* docker stop <id> <image_name>
* docker stop $(docker ps -a -q)  - inside the $ symbol command execute before, stop all docker and list the ids
* docker rm $(docker ps -a -q)
* docker rm $(docker ps --filter status=exited -q)
* docker ps --filter status=created/running/stop/exited -q -> (-q for to getid)
* https://docs.docker.com/engine/reference/commandline/ps/
* docker inspect <image_id> - get detailed information about the container
* 
