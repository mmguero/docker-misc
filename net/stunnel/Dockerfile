FROM vimagick/stunnel:latest

LABEL maintainer="mero.mero.guero@gmail.com"
LABEL org.opencontainers.image.authors='mero.mero.guero@gmail.com'
LABEL org.opencontainers.image.url='https://github.com/mmguero/docker/tree/master/net/stunnel'
LABEL org.opencontainers.image.source='https://github.com/mmguero/docker'
LABEL org.opencontainers.image.title='mmguero/stunnel'
LABEL org.opencontainers.image.description='Dockerized stunnel'

RUN sed -i '/cert =.*/i CAfile = /etc/stunnel/ca.crt' /entrypoint.sh
