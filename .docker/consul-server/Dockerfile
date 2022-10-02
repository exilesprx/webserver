FROM hashicorp/consul:1.13.2 AS source

LABEL maintainer="Exilesprx"


FROM source AS build

ARG CONFIG=default.json

COPY ${CONFIG} /consul/config/default.json

EXPOSE 8500
EXPOSE 8600/udp