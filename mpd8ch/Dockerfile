FROM alpine:3.19

RUN apk add --no-cache mpd alsa-lib alsa-utils

COPY mpd.conf /etc/mpd.conf

CMD ["mpd","--no-daemon","/etc/mpd.conf"]
