# fuse-7-online-demos
Sample Red Hat Fuse 7 Online integrations to demo its capabilities

## Pre-requisites:

- [Red Hat Fuse Online version 7.11](https://access.redhat.com/documentation/en-us/red_hat_fuse/7.11/html/installing_and_operating_fuse_online_on_openshift_container_platform/index) is installed and running
- [Red Hat AMQ 7 broker](https://access.redhat.com/documentation/en-us/red_hat_amq_broker) or [Apache ActiveMQ Artemis](https://activemq.apache.org/components/artemis/) is installed and running
    > :warning: The _Red Hat Fuse Online_ integrations in this repo have been tested with _Red Hat AMQ 7.10 Broker_.
- The [Sample JSON Validation RESTful API](https://github.com/jeanNyil/redhat-ceq-demos/tree/main/camel-quarkus-jsonvalidation-api) is deployed and running.

## Use-cases

- [RESTFul API consumption and AMQP messaging](./restfutapi-and-messaging)
