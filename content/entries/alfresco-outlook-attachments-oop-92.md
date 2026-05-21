---
title: "Alfresco Outlook Attachments Extractor (Out-of-Process)"
description: "Out-of-process Spring Boot application using the Alfresco Java SDK Events API to extract attachments from uploaded EML/MSG files and store them in a separate folder."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alfresco-outlook-attachments-oop"]
compatibility: ["ACS 7.x"]
license: "LGPL-3.0"
keywords: ["repository","email","outlook","attachments","oop","event-sdk","spring-boot"]
download_url: "https://github.com/aborroy/alfresco-outlook-attachments-oop"
vendor: "Angel Borroy"
vendor_type: "community"
about: "The out-of-process counterpart to [alfresco-outlook-attachments](https://github.com/aborroy/alfresco-outlook-attachments), implemented using the Alfresco Java SDK Events API instead of a classic in-process behaviour.\n\n- Listens for node-created events via ActiveMQ\n- Extracts attachments from EML/MSG files and stores them in a separate folder\n- Runs as a standalone Spring Boot app or Docker container\n- Configured via `application.properties` (ActiveMQ URL, ACS URL, credentials)"
about_url: "https://github.com/aborroy/alfresco-outlook-attachments-oop"
draft: false
---
