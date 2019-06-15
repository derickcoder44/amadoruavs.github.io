FROM alpine:latest

RUN apk --no-cache update && apk --no-cache upgrade
RUN apk --no-cache add ruby ruby-bundler
RUN rm -rf /var/cache/apk/*
