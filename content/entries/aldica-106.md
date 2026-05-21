---
title: "aldica – Alternative Distributed Caching for Alfresco"
description: "Distributed caching and data grid module for Alfresco Community Edition using Apache Ignite, enabling horizontal scaling and significantly improved cache capacity via off-heap and disk-based storage."
screenshots: ["https://opengraph.githubassets.com/1/aldica/aldica"]
compatibility: ["ACS 6.x","ACS 7.x"]
license: "MPL-2.0"
keywords: ["caching","clustering","distributed","ignite","performance","scalability"]
download_url: "https://github.com/aldica/aldica/releases"
vendor: "aldica"
vendor_type: "community"
about: "Replaces Alfresco Community's default in-process caching with an [Apache Ignite](https://ignite.apache.org)-based distributed cache, enabling:\n\n- **Horizontal scaling** — multiple ACS/Share instances share cache state and exchange invalidation messages\n- **Off-heap and disk-based caching** — dramatically larger cache without GC pressure\n- **Improved single-node performance** — even without clustering, off-heap caching reduces JVM heap pressure\n\nRequires [Acosix Alfresco Utility](https://github.com/Acosix/alfresco-utility). Not supported on Alfresco Enterprise Edition (which has its own proprietary clustering)."
about_url: "https://github.com/aldica/aldica"
draft: false
---
