FROM ubuntu:19.04
RUN apt-get update
RUN apt-get install -y build-essential git

ADD https://dl.google.com/go/go1.12.2.linux-amd64.tar.gz go1.12.2.linux-amd64.tar.gz
RUN tar -xvf go1.12.2.linux-amd64.tar.gz
RUN mv go /usr/local
ENV GOHOME=/go
ENV PATH="/usr/local/go/bin:${PATH}" 