FROM alpine

RUN apk add libcap

ADD ../scripts/script.sh ./script.sh

USER 2000

ENTRYPOINT [ "./script.sh" ]