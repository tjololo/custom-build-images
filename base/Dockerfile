FROM docker.io/alpine:3.5
LABEL net.tjololo.output.image="tjololo/alpine-base"
LABEL net.tjololo.maintainer="tjololo"
RUN adduser -S 1001

ADD dumb-init_1.2.0_amd64 /usr/local/bin/dumb-init
RUN chmod +x /usr/local/bin/dumb-init

ENTRYPOINT ["/usr/local/bin/dumb-init", "--"]