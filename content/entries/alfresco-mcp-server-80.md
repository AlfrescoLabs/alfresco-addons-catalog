---
title: "Alfresco MCP Server"
description: "Minimal Model Context Protocol (MCP) server for Alfresco that exposes repository tools via the Alfresco REST API, with support for stdio, SSE, and HTTP transports."
screenshots: ["https://opengraph.githubassets.com/1/AlfrescoLabs/alfresco-mcp-server"]
compatibility: ["ACS 23.x","ACS 25.x","ACS 26.x"]
license: "Apache-2.0"
keywords: ["mcp","ai","llm","rest-api","python","docker"]
download_url: "https://github.com/AlfrescoLabs/alfresco-mcp-server"
vendor: "AlfrescoLabs"
vendor_type: "community"
about: "A [FastMCP](https://github.com/jlowin/fastmcp)-based MCP server that connects AI assistants and LLM toolchains to an Alfresco repository via the REST API.\n\n- **Ticket-based authentication** against the Alfresco REST API\n- **Three transport modes**: `stdio` (default, for local AI clients), `http` (streamable-http), and `sse`\n- **Docker-ready**: single image, transport mode selectable via `TRANSPORT_MODE` env var\n- **Multi-arch image** published to Docker Hub as `angelborroy/alfresco-mcp-server`\n- Test with [MCP Inspector](https://github.com/modelcontextprotocol/inspector) out of the box\n\n| Variable | Default | Purpose |\n|----------|---------|-------|\n| `ALFRESCO_HOST` | `http://localhost:8080` | Alfresco base URL |\n| `TRANSPORT_MODE` | `stdio` | `stdio` / `http` / `sse` |\n| `HTTP` | `8003` | Port for http/sse modes |"
about_url: "https://github.com/AlfrescoLabs/alfresco-mcp-server"
draft: false
---
