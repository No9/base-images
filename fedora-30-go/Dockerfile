FROM fedora:30
RUN curl https://dl.google.com/go/go1.12.6.linux-amd64.tar.gz > go1.12.6.linux-amd64.tar.gz
RUN tar -xvf go1.12.6.linux-amd64.tar.gz
RUN mv go /usr/local

ENV GOROOT=/usr/local/go
ENV PATH="/usr/local/go/bin:${PATH}"