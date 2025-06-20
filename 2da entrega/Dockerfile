FROM ubuntu:latest
RUN apt update && apt install -y nginx iproute2 ethtool iputils-ping
COPY index.html /var/www/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

