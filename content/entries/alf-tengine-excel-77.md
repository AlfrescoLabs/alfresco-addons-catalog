---
title: "Alfresco TEngine Excel Metadata Extractor"
description: "Custom Alfresco Transform Engine that extracts metadata from Excel files and maps it to Alfresco residual properties, compatible with ACS 25.x Community and Enterprise."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alf-tengine-excel"]
compatibility: ["ACS 25.x"]
license: "LGPL-3.0"
keywords: ["transformer","excel","metadata","extractor","spreadsheet"]
download_url: "https://github.com/aborroy/alf-tengine-excel"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Transforms Excel files (`application/vnd.ms-excel` and related mimetypes) to `alfresco-metadata-extract` using configurable extraction rules.\n\n- Extracts rows from a named worksheet and maps them to the Alfresco residual property `rows`\n- Accessible from server-side JavaScript via `document.properties[\"{}rows\"]`\n- Rules configured in `ExcelMetadataExtractor_configuration.properties` (target sheet, anchor header)\n- Deployable as a **local T-Engine** (Community: `localTransform.excel.url`) or **async T-Engine** (Enterprise: queue `excel-engine-queue`)\n- Trigger via Alfresco Share folder rules: *Items are created or enter this folder → Mimetype is Microsoft Excel → Extract common metadata fields*"
about_url: "https://github.com/aborroy/alf-tengine-excel"
draft: false
---
