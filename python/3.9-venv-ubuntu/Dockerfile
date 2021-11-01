FROM cesarila/ubuntu-base:latest

USER root
RUN apt-get update && \
    apt-get install -y software-properties-common && \
    rm -rf /var/lib/apt/lists/*
RUN add-apt-repository -y -u ppa:deadsnakes/ppa && \
    apt install -y python3.9-venv && \
    rm -rf /var/lib/apt/lists/*
RUN update-alternatives --install /usr/bin/python python /usr/bin/python3.9 1
USER nobody