FROM graylog/graylog:4.3.7 AS source

LABEL maintainer="Exilesprx"


FROM source AS build

VOLUME [graylog-data /usr/share/graylog/data]

EXPOSE 9090