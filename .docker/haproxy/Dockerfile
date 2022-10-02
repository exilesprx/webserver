FROM haproxy:2.4.19-bullseye AS source

LABEL maintainer="Exilesprx"


FROM source AS build

COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

EXPOSE 1936
EXPOSE 80
EXPOSE 443