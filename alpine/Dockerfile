ARG TAG=latest
FROM docker.io/alpine:${TAG}

RUN apk add \
      bash \
      clang \
      curl \
      gcc \
      git \
      jq \
      make \
      sudo \
      wget
RUN adduser -D runner
RUN echo "runner ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER runner
WORKDIR /home/runner
