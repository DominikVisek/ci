FROM dockette/alpine:3.9

MAINTAINER Milan Sulc <sulcmil@gmail.com>

ENV NODEJS_VERSION=10.14.1

RUN apk update && apk upgrade && \
    # DEPENDENCIES #############################################################
    apk add --update bash git openssh curl && \
    # NODEJS ###################################################################
    apk add --update nodejs npm && \
    # CLEAN UP #################################################################
    rm -rf /var/cache/apk/*

CMD nodejs
