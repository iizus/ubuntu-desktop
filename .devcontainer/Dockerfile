FROM ubuntu

ENV TZ Asia/Tokyo
ENV DISPLAY host.docker.internal:0.0

RUN apt update
RUN apt upgrade -y

RUN apt install -y tzdata
RUN apt install -y libx11-dev