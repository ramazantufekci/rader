FROM ubuntu:latest

MAINTAINER Ramazan TÜFEKÇİ <rader@radyobilge.com>

RUN apt-get update

RUN echo hostname

RUN apt-get install -y nginx

ADD ["./index.html","/var/www/html"]

EXPOSE 80

ENTRYPOINT nginx -g 'daemon off;'
