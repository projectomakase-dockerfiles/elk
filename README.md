# Elastic Search, Logstash and Kibana Docker Image #

This repository contains the Dockerfile and resources for creating an ELK stack that is configured to work with Wildfly logs.

### Image ###

The image **extends** the `willdurand/elk:latest` and adds a custom logstash.conf file.

### Availability ###

The Dockerfile is available in the master branch and is built in Docker HUB as `projectomakase/elk:latest`.

### Usage ###

To boot in standalone mode

    docker run -d -p 80 -p 5043 projectomakase/elk