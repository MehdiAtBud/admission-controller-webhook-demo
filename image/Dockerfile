FROM golang:1.18-alpine as build

RUN apk update
RUN apk upgrade
RUN apk add bash

COPY ./webhook-server /
ENTRYPOINT ["/webhook-server"]
