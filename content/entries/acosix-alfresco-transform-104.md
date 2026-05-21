---
title: "Acosix Alfresco Transform"
description: "Custom T-Engine base and specific transformer implementations for Alfresco, built without Spring Boot and with a flexible properties-based configuration mechanism."
screenshots: ["https://opengraph.githubassets.com/1/Acosix/alfresco-transform"]
compatibility: ["ACS 6.x","ACS 7.x","ACS 23.x"]
license: "Apache-2.0"
keywords: ["transformer","t-engine","onlyoffice","pdf","html","email"]
download_url: "https://github.com/Acosix/alfresco-transform/releases"
vendor: "Acosix GmbH"
vendor_type: "community"
about: "An alternative T-Engine base and specific transformers, intentionally avoiding Spring Boot overhead and Alfresco's monolithic JSON config file.\n\n**Included transformers:**\n- **OnlyOffice transformer** — converts MS Office formats to PDF/images via OnlyOffice Conversion API (higher quality than LibreOffice for Office formats)\n- **Misc transformer** — Chrome/Chromium DevTools-based HTML/SVG to PDF/PNG/JPEG; RFC 822 email to HTML/PDF/images\n\n**Base features:**\n- Properties-based multi-tiered configuration (core defaults → transformer defaults → config file → system properties)\n- Shared File Store support, test page, transformation log endpoint, readiness/liveness probes"
about_url: "https://github.com/Acosix/alfresco-transform"
draft: false
---
