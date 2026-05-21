---
title: "Alfresco Auditable Aspect Disable"
description: "Alfresco Repository module that prevents cm:modified and cm:modifier from being updated when a specific aspect is added to a node, keeping audit metadata unchanged."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/auditable-aspect-disable"]
compatibility: ["ACS 6.x","ACS 7.x"]
license: "LGPL-3.0"
keywords: ["repository","auditable","aspect","behaviour","metadata"]
download_url: "https://github.com/aborroy/auditable-aspect-disable"
vendor: "Angel Borroy"
vendor_type: "community"
about: "By default Alfresco updates `cm:modified` and `cm:modifier` on every node change. This module disables that AUDITABLE behaviour when a configurable triggering aspect is added.\n\n- Triggering aspect configured in `alfresco-global.properties`:\n  ```\n  triggering.aspect.qname={http://www.alfresco.org/model/content/1.0}templatable\n  ```\n- After adding the specified aspect, `cm:modified` / `cm:modifier` remain unchanged\n- Deployed as a standard JAR to `platform/modules`"
about_url: "https://github.com/aborroy/auditable-aspect-disable"
draft: false
---
