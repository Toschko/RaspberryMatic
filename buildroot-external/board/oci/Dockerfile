FROM scratch

ARG TARGETARCH
ARG tar_prefix=rootfs

ADD $tar_prefix$TARGETARCH.tar /

LABEL org.opencontainers.image.source https://github.com/jens-maus/RaspberyMatic

CMD ["/sbin/init"]
VOLUME /usr/local
EXPOSE 80 22 161 443 1900 1901 1902 5987 1999 2000 2001 2002 2010 8088 8181 9099 9292 9293 10000 23272 41999 42000 42001 42010 43438 43439 48181 48899 49292 49880
