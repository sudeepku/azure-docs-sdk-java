---
title: Azure Event Hubs Kafka Spring cloud starter client library for Java
keywords: Azure, java, SDK, API, azure-spring-cloud-starter-eventhubs-kafka, springcloud
author: maggiepint
ms.author: magpint
ms.date: 03/23/2021
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: java
ms.service: springcloud
---

# Azure Event Hubs Kafka Spring cloud starter client library for Java - Version 2.3.0 

This starter for Apache Kafka with Azure Event Hubs helps developers to finish the auto-configuration of Event Hubs with Kafka protocol.  

[Package (Maven)][package] | [API reference documentation][refdocs] | [Product documentation][docs] | [Samples][sample]

## Getting started

### Prerequisites
- [Environment checklist][environment_checklist]

### Include the package
[//]: # ({x-version-update-start;com.azure.spring:azure-spring-cloud-starter-eventhubs-kafka;current})
```xml
<dependency>
    <groupId>com.azure.spring</groupId>
    <artifactId>azure-spring-cloud-starter-eventhubs-kafka</artifactId>
    <version>2.3.0</version>
</dependency>
```
[//]: # ({x-version-update-end})

## Key concepts
Event Hubs provides a Kafka endpoint that can be used by your existing Kafka based applications as an alternative to running your own Kafka cluster. Event Hubs supports Apache Kafka protocol 1.0 and later, and works with your existing Kafka applications, including MirrorMaker.

## Examples
Please refer to this [sample project][sample] illustrating how to use this starter.

## Troubleshooting
### Enable client logging
Azure SDKs for Java offers a consistent logging story to help aid in troubleshooting application errors and expedite their resolution. The logs produced will capture the flow of an application before reaching the terminal state to help locate the root issue. View the [logging][logging] wiki for guidance about enabling logging.

### Enable Spring logging
Spring allow all the supported logging systems to set logger levels set in the Spring Environment (for example, in application.properties) by using `logging.level.<logger-name>=<level>` where level is one of TRACE, DEBUG, INFO, WARN, ERROR, FATAL, or OFF. The root logger can be configured by using logging.level.root.

The following example shows potential logging settings in `application.properties`:

```properties
logging.level.root=WARN
logging.level.org.springframework.web=DEBUG
logging.level.org.hibernate=ERROR
```

For more information about setting logging in spring, please refer to the [official doc][logging_doc].
 

## Next steps

The following section provide a sample project illustrating how to use the starter.
### More sample code
- [Eventhubs Kafka Sample][sample]

## Contributing
This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

Please follow [instructions here][contributing_md] to build from source or contribute.

<!-- Link -->
[package]: https://mvnrepository.com/artifact/com.microsoft.azure/spring-cloud-starter-azure-eventhubs-kafka
[refdocs]: https://azure.github.io/azure-sdk-for-java/springcloud.html#azure-spring-cloud-autoconfigure
[docs]: https://docs.microsoft.com/azure/developer/java/spring-framework/configure-spring-cloud-stream-binder-java-app-kafka-azure-event-hub
[sample]: https://github.com/Azure/azure-sdk-for-java/tree/azure-spring-cloud-starter-eventhubs-kafka_2.3.0/sdk/spring/azure-spring-boot-samples/azure-spring-cloud-sample-eventhubs-kafka
[logging]: https://github.com/Azure/azure-sdk-for-java/wiki/Logging-with-Azure-SDK#use-logback-logging-framework-in-a-spring-boot-application
[logging_doc]: https://docs.spring.io/spring-boot/docs/current/reference/html/spring-boot-features.html#boot-features-logging
[contributing_md]: https://github.com/Azure/azure-sdk-for-java/tree/azure-spring-cloud-starter-eventhubs-kafka_2.3.0/sdk/spring/CONTRIBUTING.md
[environment_checklist]: https://github.com/Azure/azure-sdk-for-java/blob/azure-spring-cloud-starter-eventhubs-kafka_2.3.0/sdk/spring/ENVIRONMENT_CHECKLIST.md#ready-to-run-checklist


