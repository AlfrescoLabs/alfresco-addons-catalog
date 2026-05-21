---
title: "Alfresco Model Namespace-Prefix Mapping"
description: "Alfresco Repository WebScript that returns a JSON map of every deployed content model's namespace URI to its prefix, useful for debugging and tooling."
screenshots: ["https://opengraph.githubassets.com/1/AlfrescoLabs/model-ns-prefix-mapping"]
compatibility: ["ACS 7.x","ACS 23.x","ACS 25.x"]
license: "Apache-2.0"
keywords: ["repository","content-model","namespace","webscript","developer-tools"]
download_url: "https://github.com/AlfrescoLabs/model-ns-prefix-mapping/releases"
vendor: "AlfrescoLabs"
vendor_type: "community"
about: "A lightweight Repository add-on that exposes a single Admin WebScript:\n\n```\nGET /alfresco/s/model/ns-prefix-map\n```\n\nReturns a JSON object mapping every registered namespace URI to its prefix (e.g. `\"http://www.alfresco.org/model/content/1.0\": \"cm\"`). Requires Administrator credentials. Useful for content model debugging, migration tooling, and custom metadata extraction."
about_url: "https://github.com/AlfrescoLabs/model-ns-prefix-mapping"
draft: false
---
