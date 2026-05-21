---
title: "Alfresco TEngine Convert to Markdown"
description: "AI-powered Alfresco Transform Engine that converts PDF files to clean, richly-described Markdown using Docling, with optional LLaVA multimodal image captioning via Ollama."
screenshots: ["https://opengraph.githubassets.com/1/aborroy/alf-tengine-convert2md"]
compatibility: ["ACS 25.x","ACS 26.x"]
license: "Apache-2.0"
keywords: ["transformer","pdf","markdown","ai","docling","ollama"]
download_url: "https://github.com/aborroy/alf-tengine-convert2md"
vendor: "Angel Borroy"
vendor_type: "community"
about: "Transforms `application/pdf` → `text/markdown` using [Docling](https://pypi.org/project/docling/).\n\n| Capability | Details |\n|---|---|\n| PDF to Markdown | Extracts text and layout, turning each page into structured Markdown |\n| Image handling | `placeholder`, `embedded` (base64), `referenced` (PNG), or `described` (LLaVA caption) |\n| Multilingual captions | English, Spanish, French, German, Italian, Portuguese when using `described` mode |\n| Alfresco‑ready | Implements the Alfresco Transform Core SPI (`TransformEngine` & `CustomTransformer`) |\n| Containerised | Multi‑stage Docker build (Java 17 + Python 3.11), published to Docker Hub as `angelborroy/alf-tengine-convert2md` |\n| ACS 26.1 ready | Ready-to-use `docker-compose-261.yaml` included |\n\n> Image captioning (`image=described`) requires a local [Ollama](https://ollama.ai) daemon with `llava` pulled."
about_url: "https://github.com/aborroy/alf-tengine-convert2md"
draft: false
---
