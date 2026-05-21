---
title: "Alfresco mTLS Debugging Kit"
description: "A set of tools to diagnose and debug mTLS configuration issues across Alfresco services, including Admin Console add-ons for Repository and SOLR, a CLI verification app, and a keystores generation lab."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alfresco-mtls-debugging-kit"]
compatibility: ["ACS 7.x","ACS 23.x","ACS 25.x"]
license: "LGPL-3.0"
keywords: ["mtls","tls","ssl","security","debugging","solr","admin-console"]
download_url: "https://github.com/aborroy/alfresco-mtls-debugging-kit/releases"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Toolkit for troubleshooting mTLS between Alfresco Repository, SOLR, and other services.\n\n| Component | Purpose |\n|---|---|\n| `alfresco-http-java-client` | Repository Admin Console page showing Search Client mTLS details |\n| `solr-http-java-client` | SOLR Admin REST API action exposing HTTP client keystore info |\n| `mtls-conf-app` | CLI Spring Boot app to verify mTLS endpoints and keystores before ACS starts |\n| `step-ca` lab | Generate ECC/ECDSA certificates and Alfresco-compatible keystores |\n\nA ready-to-use Docker Compose stack with all addons applied is included."
about_url: "https://github.com/aborroy/alfresco-mtls-debugging-kit"
draft: false
---
