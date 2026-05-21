---
title: "Promena – Modular Transformation System for Alfresco"
description: "Modular general-purpose transformation system built for Alfresco that delegates heavy document transformation tasks (converting, OCR, report generation) to external nodes via ActiveMQ or HTTP."
screenshots: ["https://opengraph.githubassets.com/1/BeOne-PL/promena"]
compatibility: ["ACS 6.x","ACS 7.x","ACS 23.x"]
license: "Apache-2.0"
keywords: ["transformer","activemq","distributed","ocr","conversion","microservice"]
download_url: "https://github.com/BeOne-PL/promena"
vendor: "BeOne PL"
vendor_type: "community"
about: "An Akka-based transformation framework that offloads long-running document operations from Alfresco to dedicated transformation nodes.\n\n- **Connectors**: ActiveMQ (preferred for production) or HTTP\n- **Communication**: file-based (production) or in-memory\n- **Transformers**: composable, identified by name+sub-name, distributable across nodes\n- **Load balancing**: adaptive load balancing across cluster nodes\n- Alfresco integration via a separate [promena-alfresco](https://github.com/BeOne-PL/promena-alfresco) module\n\nSee [promena-sample](https://github.com/BeOne-PL/promena-sample) for deployment and transformer examples."
about_url: "https://github.com/BeOne-PL/promena"
draft: false
---
