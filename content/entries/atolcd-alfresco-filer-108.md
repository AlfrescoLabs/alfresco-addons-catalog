---
title: "Alfresco Filer"
description: "Alfresco Content Services module that automatically files documents into folder structures based on configurable rules written with a Java fluent API, driven by node type, aspects, and metadata."
screenshots: ["https://opengraph.githubassets.com/1/atolcd/alfresco-filer"]
compatibility: ["ACS 5.x","ACS 6.x"]
license: "Apache-2.0"
keywords: ["repository","filing","rules","automation","folder","classification"]
download_url: "https://github.com/atolcd/alfresco-filer/releases"
vendor: "Atol CD"
vendor_type: "community"
about: "Implements a rule-based automatic document filing engine triggered by Alfresco policies.\n\n- Rules defined via a **Java fluent API** — match on type, aspects, site, or metadata then navigate/create folder hierarchy\n- Supports **on-the-fly folder creation** and **metadata inheritance** from parent folders\n- Policy hooks: `onCreateChildAssociation`, `onAddAspect`, `onUpdateProperties`, `onMoveNode`, `onDeleteNode`\n- Empty filer segment folders are automatically deleted\n- Standard JAR + AMP packaging; JUnit 5 / Mockito test coverage"
about_url: "https://github.com/atolcd/alfresco-filer"
draft: false
---
