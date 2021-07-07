FROM ubuntu:20.04
RUN apt-get update \
    && apt-get install --no-install-recommends --no-install-suggests -y \
        aptitude iputils-ping net-tools man vim openssh-server python \
    && rm -rf /var/lib/apt/lists/*
RUN mkdir /var/run/sshd
RUN mkdir /root/.ssh
