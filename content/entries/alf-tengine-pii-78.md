---
title: "Alfresco TEngine PII Redaction"
description: "Alfresco Transform Engine that detects and redacts Personally Identifiable Information (PII) in PDF documents using Microsoft Presidio, producing a sanitized PDF or structured PII metadata."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alf-tengine-pii"]
compatibility: ["ACS 25.x"]
license: "LGPL-3.0"
keywords: ["transformer","pdf","pii","redaction","presidio","privacy","compliance"]
download_url: "https://github.com/aborroy/alf-tengine-pii"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Integrates [Microsoft Presidio](https://github.com/microsoft/presidio) into an Alfresco T-Engine to redact PII from PDFs or extract it as metadata.\n\n**Two transform modes:**\n- `application/pdf` → `application/pdf`: produces a redacted PDF with configurable label and score threshold\n- `application/pdf` → `alfresco-metadata-extract`: returns structured JSON with entity counts, scores, and values, mappable to Alfresco content model properties (`pii:hasPII`, `pii:entities`, `pii:countPerson`, etc.)\n\n**Configurable via** `pii_engine_config.json`:\n- `entities`: list of PII types (PERSON, PHONE_NUMBER, EMAIL_ADDRESS, CREDIT_CARD, …)\n- `scoreThreshold`: confidence threshold (0.0–1.0)\n- `label`: replacement text for redacted content\n\nDeployable as a **local T-Engine** (Community: `localTransform.pdf-pii.url`) or **async T-Engine** (Enterprise: queue `pii-engine-queue`)."
about_url: "https://github.com/aborroy/alf-tengine-pii"
draft: false
---
