FROM alpine:edge

WORKDIR /tmp

RUN apk update
RUN apk add linux-headers musl-dev util-linux-dev bash
RUN apk add attr-dev acl-dev e2fsprogs-dev zlib-dev lzo-dev zstd-dev
RUN apk add autoconf automake make gcc tar gzip

COPY ./test-build .
