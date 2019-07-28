FROM ubuntu:latest
RUN rm /etc/apt/sources.list
COPY /my-docker-builder/sources.list /etc/apt/

RUN apt update && apt upgrade -y && apt install net-tools redis-tools iputils-ping -y

# RUN apt install htop terminator -y
RUN apt clean

CMD /bin/bash
