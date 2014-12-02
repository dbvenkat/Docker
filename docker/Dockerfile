# Version: 0.0.1
FROM ubuntu:latest
MAINTAINER Venkat S "svenkat@example.com"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hi, I am in your container' \
>/usr/share/nginx/html/index.html
EXPOSE 80
