FROM node:8-alpine

USER root

ENV USER root

WORKDIR /music

RUN apk add --no-cache make g++ python && \
    npm i -g --unsafe-perm yun-playlist-downloader

ENTRYPOINT ["yun"]
