FROM openjdk:8

RUN apt-get clean
RUN apt-get update
RUN apt-get update --fix-missing
RUN apt-get upgrade -y

EXPOSE 25565

VOLUME /root/env
WORKDIR /root/env