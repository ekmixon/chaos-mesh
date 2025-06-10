FROM alpine:3.22.0

ARG HTTPS_PROXY
ARG HTTP_PROXY

RUN apk add tzdata --no-cache

COPY bin/chaos-controller-manager /usr/local/bin/chaos-controller-manager