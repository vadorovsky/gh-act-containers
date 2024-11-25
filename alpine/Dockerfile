ARG TAG=latest
FROM docker.io/alpine:${TAG}

RUN apk add git sudo
RUN adduser -D runner
RUN echo "runner ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER runner
WORKDIR /home/runner
