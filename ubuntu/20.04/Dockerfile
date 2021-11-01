FROM ubuntu:20.04

RUN apt-get -y update && \
    apt-get -y upgrade && \
    apt-get autoclean && \
    apt-get clean 


WORKDIR /opt
RUN chown nobody. /opt
USER nobody