FROM alpine

RUN apk add libcap

ADD ../scripts/script.sh ./script.sh

ENTRYPOINT [ "./script.sh" ]