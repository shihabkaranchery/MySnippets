


* docker ps # activly running container
* docker ps -a # list all container
* docker rm <docker_id> # remove  docker image
* sudo docker build . -t <image_name>
* sudo docker run <image_name>
    * sudo docker run -d (daemon for backgroud run) -p 80:80(host port:mapped container port) <image_name>
* to get the local IP address of the image
* sudo docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' e6de5ada422c
* sudo docker run -it ubuntu:latest /bin/bash ( ssh to docker interactive)
* sudo docker run -it --rm ubuntu:latest /bin/bash (remove docker after exiting)
* sudo docker exec -it <image_name> /bin/bash # run/ssh to container
