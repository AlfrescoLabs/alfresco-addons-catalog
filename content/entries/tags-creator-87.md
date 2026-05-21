---
title: "Alfresco Tags Creator"
description: "Alfresco Repository add-on that restricts TAG creation to members of a dedicated group (GROUP_TAG_CREATORS), enforced at the repository tier."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/tags-creator"]
compatibility: ["ACS 5.x","ACS 7.x","ACS 23.x"]
license: "GPL-2.0"
keywords: ["repository","tags","permissions","governance","group"]
download_url: "https://github.com/aborroy/tags-creator"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Restricts Alfresco TAG creation to a specific group at the repository tier — enforced even if users bypass the UI.\n\n- Looks for a group with ID `GROUP_TAG_CREATORS` (created automatically on first start)\n- Alfresco Administrators should be added to this group to retain TAG creation rights\n- Low-level permission change means the restriction cannot be circumvented via API\n- Deployed as a standard JAR to `alfresco/webapps/WEB-INF/lib`"
about_url: "https://github.com/aborroy/tags-creator"
draft: false
---
