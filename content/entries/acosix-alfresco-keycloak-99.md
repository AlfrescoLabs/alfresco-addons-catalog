---
title: "Acosix Alfresco Keycloak"
description: "Alfresco addon providing Keycloak-based authentication and authorisation for Repository and Share, including OIDC SSO, Bearer token auth, user/group sync, and back-channel logout."
screenshots: ["https://opengraph.githubassets.com/1/Acosix/alfresco-keycloak"]
compatibility: ["ACS 6.x","ACS 7.x","ACS 23.x"]
license: "Apache-2.0"
keywords: ["security","keycloak","sso","oidc","authentication","oauth2"]
download_url: "https://github.com/Acosix/alfresco-keycloak/releases"
vendor: "Acosix GmbH"
vendor_type: "community"
about: "Custom Keycloak authentication subsystem for Repository and Share (separate from Alfresco's built-in identity-service).\n\n**Repository features:**\n- User+password login, Bearer token, and OIDC redirect authentication\n- Mapping of person properties and authorities from Keycloak access tokens\n- Back-channel logout and bulk token invalidation\n- Active user/group synchronisation against Keycloak directory (including federated directories)\n\n**Share features:**\n- OIDC SSO redirect and login dialog enhancement\n- OAuth 2.0 Token Exchange (RFC 8693) to delegate Share auth to Repository\n- Share logout triggering Keycloak single sign-out\n\nCompatible with Keycloak 6.0.1+. Version 1.2.0-rc1+ targets ACS 23.1+; earlier versions target ACS 6.0–7.4."
about_url: "https://github.com/Acosix/alfresco-keycloak"
draft: false
---
