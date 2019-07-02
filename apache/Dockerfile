FROM ubuntu:latest

MAINTAINER Toe Hlaing Win <toe.h.win@frontiir.net> 

RUN apt-get update

RUN apt-get install net-tools

RUN apt-get install -y apache2

RUN apt-get clean

EXPOSE 8080

CMD ["apache2ctl", "-D", "FOREGROUND"]
