---
page_type: sample
languages:
- java
products:
- azure
description: "Azure Cosmos DB is a globally distributed multi-model database. One of the supported APIs is the Cassandra API. This sample shows how to use Spring Data for Apache Cassandra with Azure Cosmos DB awareness features."
urlFragment: azure-cosmos-cassandra-extensions-java-spring-boot-sample-v4
---

# Project Name

(short, 1-3 sentenced, description of the project)

## Features

This project framework provides the following features:

* Feature 1
* Feature 2
* ...

## Getting Started

### Prerequisites

(ideally very short, if any)

- OS
- Library version
- ...

### Packaging and Integration Testing

```bash
mvn clean package integration-test -DargLine="\
'-Dazure.cosmos.cassandra.global-endpoint=<account-name>cassandra.cosmos.azure.com:10350' \
'-Dazure.cosmos.cassandra.username=<username>' \
'-Dazure.cosmos.cassandra.password=<password>' \
'-Dazure.cosmos.cassandra.preferred-regions=<region-name>[,...]' \
'-Dazure.cosmos.cassandra.truststore-path=<truststore-path>'" \
'-Dazure.cosmos.cassandra.truststore-password=<truststore-password>'"
```

### Quickstart
(Add steps to get up and running quickly)

1. git clone [repository clone url]
2. cd [respository name]
3. ...


## Demo

A demo app is included to show how to use the project.

To run the demo, follow these steps:

(Add steps to start up the demo)

1.
2.
3.

## Resources

(Any additional resources or related projects)

- Link to supporting information
- Link to similar sample
- ...
