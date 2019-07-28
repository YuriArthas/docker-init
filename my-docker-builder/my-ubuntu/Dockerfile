FROM ubuntu:latest
RUN rm /etc/apt/sources.list
COPY sources.list /etc/apt/

RUN apt update && apt upgrade -y && apt install net-tools redis-tools iputils-ping -y
RUN apt clean

CMD /bin/bash
