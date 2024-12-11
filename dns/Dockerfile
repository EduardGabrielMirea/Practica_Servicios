FROM debian:latest

RUN apt-get update && apt-get install -y bind9 bind9utils

COPY named.conf.local /etc/bind/
COPY minombreapellido.local.db /etc/bind/zones/

EXPOSE 53/udp

CMD [ "named", "-g" ]