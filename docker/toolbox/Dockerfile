FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python pip && \
    pip install awscli
RUN apk --purge -v del pip
CMD tail -f /dev/null
