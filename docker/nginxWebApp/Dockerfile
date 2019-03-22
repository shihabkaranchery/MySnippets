FROM nginx:latest

ADD index.html /www/
ADD nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80
EXPOSE 443

# to get the local IP address of the image
# sudo docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' e6de5ada422c
