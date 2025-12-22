---
title: "Alfresco Node Vault"
description: "A Spring Boot application designed for long-term storage of Alfresco nodes. Unlike traditional archiving solutions, Alfresco Node Vault completely removes nodes from Alfresco and its database, freeing resources while maintaining document accessibility.\n\nThe application can archive nodes on-demand through a behavior or using a scheduled job.\n\nNodes metadata are archived on MongoDB while binaries can be stored either on GridFS or on AWS S3, ensuring efficiency and scalability.\n\nThe application can also act as a proxy to allow applications using REST APIs to retrieve nodes that no longer exist in Alfresco, ensuring operational continuity without the need to modify legacy client applications.\n\nFurthermore, documents can also be automatically restored in Alfresco if required.\n\nBy implementing Alfresco Node Vault, organizations can:\n\n- Maintain high performance in their active Alfresco repository\n- Keep all historical documents accessible when needed\n- Significantly reduce backup and maintenance windows\n- Lower infrastructure costs by optimizing resource usage\n- Simplify upgrade processes by reducing the volume of live data\n\nThis approach bridges the gap between complete document purging (often unacceptable for business or compliance reasons) and the indefinite retention of all documents in the active repository (unsustainable from a performance perspective)."
screenshots: ["_No response_"]
compatibility: ["ACS 7.x","ACS 23.1","ACS 23.2","ACS 23.3","ACS 23.4","ACS 23.x","ACS 25.1","ACS 25.2","ACS 25.x"]
license: "GPL-3.0-or-later"
keywords: ["Archival"]
download_url: "https://github.com/saidone75/alfresco-node-vault"
vendor: "https://saidone.org"
about: "_No response_"
about_url: "https://github.com/saidone75/alfresco-node-vault"
draft: false
---

