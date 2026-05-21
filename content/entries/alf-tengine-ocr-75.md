---
title: "Alfresco OCR Transform Engine"
description: "Alfresco Transform Engine that converts PDF files to searchable, text-layer PDFs using OCR (ocrmypdf / Tesseract). Compatible with ACS 7.0+ as a local or async T-Engine."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alf-tengine-ocr"]
compatibility: ["ACS 7.x","ACS 23.x","ACS 25.x"]
license: "GPL-2.0"
keywords: ["transformer","ocr","pdf","tesseract","text-layer"]
download_url: "https://github.com/aborroy/alf-tengine-ocr"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Runs [ocrmypdf](https://ocrmypdf.readthedocs.io) (a Tesseract wrapper) inside an Alfresco Transform Engine to produce OCR'd PDFs.\n\n- Original PDF kept as version 1.0; OCR'd version saved as 1.1\n- Includes a companion **embed-metadata** Repository add-on that adds the OCR action to Alfresco Share folder rules\n- Configurable `ocrmypdf` arguments (e.g. `--skip-text`, `--force-ocr`, language)\n- Deployable as a **local T-Engine** (Community) or **async T-Engine via ActiveMQ** (Enterprise)\n- Community: add `localTransform.ocr.url=http://transform-ocr:8090/` to Alfresco JAVA_OPTS\n- Enterprise: register URL + queue (`ocr-engine-queue`) with the Transform Router"
about_url: "https://github.com/aborroy/alf-tengine-ocr"
draft: false
---
