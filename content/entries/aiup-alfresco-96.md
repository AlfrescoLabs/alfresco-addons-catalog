---
title: "AIUP Alfresco – AI-Assisted Extension Development"
description: "Claude Code plugin and portable prompt pack that packages the full Alfresco extension development workflow as slash commands, skills, and agents, supporting in-process, out-of-process, Share, and mixed extension types."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/aiup-alfresco"]
compatibility: ["ACS 25.x","ACS 26.x"]
license: "Apache-2.0"
keywords: ["developer-tools","ai","claude-code","sdk","scaffolding","codegen","extension"]
download_url: "https://github.com/aborroy/aiup-alfresco"
vendor: "Angel Borroy"
vendor_type: "community"
about: "A [Claude Code](https://claude.com/claude-code) plugin that drives the entire Alfresco extension development lifecycle via slash commands.\n\nInstall: `claude plugin install aborroy/aiup-alfresco`\n\n| Command | Purpose |\n|---|---|\n| `/requirements` | Gather requirements and decide architecture |\n| `/scaffold` | Generate `pom.xml`, module descriptors, Spring Boot skeleton |\n| `/content-model` | Generate content model XML and Java constants |\n| `/behaviours` / `/actions` | Scaffold behaviour policies and action executors |\n| `/events` | Generate Spring Boot OOP event listener |\n| `/web-scripts` | Generate Web Script descriptors and controllers |\n| `/docker-compose` | Generate full ACS stack `compose.yaml` |\n| `/test` | Generate integration tests |\n\nAlso portable outside Claude via `./scripts/aiup-command.sh render` for Codex, OpenClaw, and other agents."
about_url: "https://github.com/aborroy/aiup-alfresco"
draft: false
---
