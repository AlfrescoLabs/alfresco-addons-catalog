---
title: "Alfresco Script Root Objects"
description: "Repository JAR that exposes multiple JavaScript Root Objects for Alfresco Content Services, enabling safe access to system properties, Base64 encoding, modern renditions, and Hyland Automate process integration from repository scripts."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alfresco-script-root-object"]
compatibility: ["ACS 25.x"]
license: "Unknown"
keywords: ["repository","javascript","root-object","scripting","rendition","hyland-automate"]
download_url: "https://github.com/aborroy/alfresco-script-root-object"
vendor: "Angel Borroy"
vendor_type: "community"
about: "A single JAR that adds these root objects to Alfresco Repo JavaScript (rules, web scripts, workflows):\n\n| Root Object | Purpose |\n|---|---|\n| `sysAdmin` | Safe access to selected `SysAdminParams` methods |\n| `globalProperties` | Read values from `alfresco-global.properties` |\n| `packagesScript` | Controlled escape-hatch to inspect Spring context and class methods |\n| `base64` | Streamed Base64 encode/decode for content and bytes |\n| `renditionService2` | Exposes the missing `renditionService2` root object for modern renditions |\n| `hylandProcess` | Start Hyland Automate processes via OAuth2-secured REST |\n\nDeploy as a Docker overlay or copy JAR to `WEB-INF/lib`."
about_url: "https://github.com/aborroy/alfresco-script-root-object"
draft: false
---
