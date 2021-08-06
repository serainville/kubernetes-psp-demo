FROM alpine

RUN addgroup -g 433 -S aqua && adduser -h /home/aqua -g "aqua user" -s /sbin/nologin -G aqua -S -u 431 aqua && \
    apk add libcap

ADD ../scripts/script.sh ./script.sh

USER aqua

ENTRYPOINT [ "./script.sh" ]