---
title: "Alfresco TEngine XML Metadata Extractor"
description: "Custom Alfresco Transform Engine that extracts metadata from XML files and maps it to Alfresco properties, with branches for ACS 7.x–25.1.x (legacy) and ACS 25.2+ (current)."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alf-tengine-xml"]
compatibility: ["ACS 7.x","ACS 23.x","ACS 25.x"]
license: "LGPL-3.0"
keywords: ["transformer","xml","metadata","extractor"]
download_url: "https://github.com/aborroy/alf-tengine-xml"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Transforms XML files (`text/xml`, `application/xml`) to `alfresco-metadata-extract` using XPath-based mapping rules.\n\n| Branch | ACS versions | Transformer | Java |\n|--------|-------------|------------|------|\n| `main` | 25.2+ | 5.2 | 17+ |\n| `alfresco-legacy` | 7.x – 25.1.x | 3.1.0 | 11+ |\n\n- Mapping rules defined in `XmlMetadataExtractor_metadata_extract.properties`\n- **Auto-triggered** by the Repository on every XML create/update — no folder rules needed\n- Deployable as a **local T-Engine** (Community: `localTransform.xml.url`) or **async T-Engine** (Enterprise: queue `xml-engine-queue`)"
about_url: "https://github.com/aborroy/alf-tengine-xml"
draft: false
---
