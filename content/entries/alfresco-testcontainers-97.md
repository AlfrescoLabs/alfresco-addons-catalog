---
title: "Alfresco Testcontainers"
description: "Testcontainers integration for Alfresco that lets you spin up a full ACS stack (Repository, PostgreSQL, ActiveMQ) in JUnit 4 or JUnit 5 integration tests with a single annotation."
screenshots: ["https://opengraph.githubassets.com/1/AlfrescoLabs/alfresco-testcontainers"]
compatibility: ["ACS 23.x","ACS 25.x"]
license: "Apache-2.0"
keywords: ["testing","testcontainers","junit","integration-test","developer-tools","java"]
download_url: "https://github.com/AlfrescoLabs/alfresco-testcontainers"
vendor: "AlfrescoLabs"
vendor_type: "community"
about: "A Java library that integrates Alfresco with [Testcontainers](https://testcontainers.com) for realistic integration testing without a running ACS instance.\n\n```xml\n<dependency>\n  <groupId>org.alfresco</groupId>\n  <artifactId>alfresco-testcontainers</artifactId>\n  <version>0.8.0</version>\n  <scope>test</scope>\n</dependency>\n```\n\n- JUnit 4 (`@Rule`) and JUnit 5 (`@Container`) support\n- Access to internal containers: `getPostgreSQLContainer()`, `getActivemqContainer()`\n- Enable ActiveMQ via `withMessagingEnabled()`\n- Enterprise images supported via `DockerImageName.parse(\"quay.io/alfresco/...\")`"
about_url: "https://github.com/AlfrescoLabs/alfresco-testcontainers"
draft: false
---
