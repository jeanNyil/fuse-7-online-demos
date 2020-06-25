# fuse-7-online-demos
Sample Red Hat Fuse 7 Online integrations to demo its capabilities

## Pre-requisites:

- [Red Hat Fuse Online version 7.6](https://access.redhat.com/documentation/en-us/red_hat_fuse/7.6/html/installing_and_operating_fuse_online_on_openshift_container_platform/index) installed and running
- [Red Hat AMQ 7 broker](https://access.redhat.com/documentation/en-us/red_hat_amq/7.6/) or [Apache ActiveMQ Artemis](https://activemq.apache.org/components/artemis/) or [Red Hat AMQ Online](https://access.redhat.com/documentation/en-us/red_hat_amq/7.6/html/installing_and_managing_amq_online_on_openshift/index) ([EnMasse](https://enmasse.io/)) installed and running
    - :warning: The _Red Hat Fuse Online_ integrations in this repo have been tested with _Red Hat AMQ 7.6 Broker_.
- The [Sample JSON Validation RESTful API](https://github.com/jeanNyil/fuse-7-springboot-demos/tree/master/sample-json-validation-api) is deployed and running.

## Use-cases

- [RESTFul API consumption and AMQP messaging](./restfutapi-and-messaging)
