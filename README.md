### Webserver

- common application items
- haproxy in front
- consul as the service discovery
  - hook into haproxy
  - consul allows multiple json configs, so add additional files as needed
    - ex: node name, retry joins, etc. anything specific to the app
- graylog as common logger
- prometheus as common metric


### TODO
- lint docker files
- setup docker to build images