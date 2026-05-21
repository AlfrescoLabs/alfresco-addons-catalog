---
title: "Acosix Alfresco Audit"
description: "Addon adding audit utilities to Alfresco: active user login tracking, incremental cleanup of alf_prop_* tables, and web scripts for querying active/inactive users."
screenshots: ["https://opengraph.githubassets.com/1/Acosix/alfresco-audit"]
compatibility: ["ACS 5.x","ACS 6.x","ACS 7.x","ACS 23.x"]
license: "Apache-2.0"
keywords: ["audit","users","compliance","cleanup","reporting"]
download_url: "https://github.com/Acosix/alfresco-audit/releases"
vendor: "Acosix GmbH"
vendor_type: "community"
about: "Extends Alfresco auditing with three practical capabilities:\n\n1. **Active user login tracking** — dedicated `acosix-audit-activeUsersLogin` audit application recording every successful authentication (password, SSO, NTLM/Kerberos); consolidated hourly into `acosix-audit-activeUsers` with automatic 14-day cleanup\n2. **Incremental alf_prop_\\* cleanup** — replaces Alfresco's brute-force cleanup job with staggered, batch-based jobs that run between 9 PM–5 AM, safe for large production systems\n3. **Active/inactive user web scripts** — `/alfresco/s/acosix/api/audit/activeUsers` and `inactiveUsers` report users seen/not seen in audit data within a configurable lookback period"
about_url: "https://github.com/Acosix/alfresco-audit"
draft: false
---
