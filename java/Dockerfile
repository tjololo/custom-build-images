FROM alpine:3.5
LABEL net.tjololo.output.image="tjololo/base-java"
LABEL net.tjololo.maintainer="tjololo"

ENV LANG C.UTF-8

ENV JAVA_ALPINE_VERSION 8.121.13-r0

RUN set -x \
    && apk add --no-cache openjdk8="$JAVA_ALPINE_VERSION"
