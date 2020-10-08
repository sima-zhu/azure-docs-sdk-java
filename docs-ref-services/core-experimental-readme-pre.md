---
title: Azure Core Experimental shared library for Java
keywords: Azure, java, SDK, API, azure-core-experimental, core
author: maggiepint
ms.author: magpint
ms.date: 10/06/2020
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: java
ms.service: core
---

# Azure Core Experimental shared library for Java - Version 1.0.0-beta.6 


[![Build Documentation](https://img.shields.io/badge/documentation-published-blue.svg)](https://azure.github.io/azure-sdk-for-java)

Azure Core Experimental contains types that are being evaluated and might eventually become part of Azure Core, this library will always stay in a preview version and might allow breaking changes.

## Getting started

### Prerequisites

- A [Java Development Kit (JDK)][jdk_link], version 8 or later.

### Include the package

[//]: # ({x-version-update-start;com.azure:azure-core-experimental;current})
```xml
<dependency>
    <groupId>com.azure</groupId>
    <artifactId>azure-core-experimental</artifactId>
    <version>1.0.0-beta.6</version>
</dependency>
```
[//]: # ({x-version-update-end})

## Key concepts

Azure Core experimental is reserved for features that are actively being prototyped and may be merged into Azure Core
in the future.

## Examples

## Troubleshooting

### Enabling Logging

Azure SDKs for Java offer a consistent logging story to help aid in troubleshooting application errors and expedite
their resolution. The logs produced will capture the flow of an application before reaching the terminal state to help
locate the root issue. View the [logging][logging] wiki for guidance about enabling logging.

## Next steps

## Contributing

If you would like to become an active contributor to this project please follow the instructions provided in [Microsoft
Azure Projects Contribution Guidelines](http://azure.github.io/guidelines.html).

1. Fork it
1. Create your feature branch (`git checkout -b my-new-feature`)
1. Commit your changes (`git commit -am 'Add some feature'`)
1. Push to the branch (`git push origin my-new-feature`)
1. Create new Pull Request

<!-- Links -->
[logging]: https://github.com/Azure/azure-sdk-for-java/wiki/Logging-with-Azure-SDK
[jdk_link]: https://docs.microsoft.com/java/azure/jdk/?view=azure-java-stable

![Impressions](https://azure-sdk-impressions.azurewebsites.net/api/impressions/azure-sdk-for-java%2Fsdk%2Fcore%2Fazure-core-experimental%2FREADME.png)
