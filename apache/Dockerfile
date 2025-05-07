FROM ubuntu:20.04
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update 
RUN apt install -y apache2 
RUN apt install -y apache2-utils 
RUN apt install -y git php
RUN apt clean 
WORKDIR /var/www/html
RUN mkdir app
WORKDIR /var/www/html/app
RUN git clone https://github.com/KikoVaquero/Practica4-DevSecOps/ .
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]
