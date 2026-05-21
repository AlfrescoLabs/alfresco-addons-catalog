---
title: "Alfresco Model Extractor"
description: "Go CLI tool that extracts Alfresco XML content models from an existing addon JAR or AMP and repackages them into a standalone model-only JAR, useful when upgrading Alfresco and dropping an addon that still has dependent content."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alfresco-model-extractor"]
compatibility: ["ACS 7.x","ACS 23.x","ACS 25.x"]
license: "Apache-2.0"
keywords: ["content-model","migration","upgrade","cli","go","amp","jar"]
download_url: "https://github.com/aborroy/alfresco-model-extractor/releases"
vendor: "Angel Borroy"
vendor_type: "community"
about: "A developer utility for Alfresco upgrades where an old addon is no longer supported but its content model is still needed.\n\n- Scans a JAR or AMP for Alfresco XML content model files\n- Auto-generates `module.properties` and `module-context.xml`\n- Outputs a deployable JAR with the standard `alfresco/module/<name>/model/` structure\n- Pre-compiled binaries for macOS (Intel & Apple Silicon), Linux, and Windows\n\n```sh\n./alfresco-model-extractor -zip original-addon.amp -output original-addon-models.jar\n```"
about_url: "https://github.com/aborroy/alfresco-model-extractor"
draft: false
---
