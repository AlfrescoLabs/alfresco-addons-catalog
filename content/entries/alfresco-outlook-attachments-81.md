---
title: "Alfresco Outlook Attachments Extractor"
description: "Alfresco Repository add-on that automatically extracts attachment files from uploaded Outlook message files (EML, MSG) and stores them in the same or a separate folder."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alfresco-outlook-attachments"]
compatibility: ["ACS 7.x"]
license: "LGPL-3.0"
keywords: ["repository","email","outlook","attachments","eml","msg"]
download_url: "https://github.com/aborroy/alfresco-outlook-attachments"
vendor: "Angel Borroy"
vendor_type: "community"
about: "On upload of an EML or MSG file, the add-on extracts all attached files and stores them alongside the original or in a dedicated sub-folder.\n\n- Configurable via `alfresco-global.properties`:\n  - `extract.attachments.mimetype.list`: mimetypes to process (default: `message/rfc822`, `application/vnd.ms-outlook`)\n  - `imap.attachments.mode`: `SAME` (same folder) or `SEPARATE` (sub-folder)\n  - `imap.attachments.folder.suffix`: sub-folder name suffix (default: `-attachment`)\n- Deployed as a standard JAR to `WEB-INF/lib`"
about_url: "https://github.com/aborroy/alfresco-outlook-attachments"
draft: false
---
