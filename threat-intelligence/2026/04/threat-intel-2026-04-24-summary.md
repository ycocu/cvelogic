# Daily Threat Intelligence — April 24, 2026

**Digest window (UTC):** 2026-04-24
**Generated:** 2026-06-02T07:35:00Z

## Threat brief

SimpleHelp: 2 CVEs added to CISA KEV today. · Exploitation likelihood rose sharply (EPSS 33% → 81% · rising (+49%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- SimpleHelp: 2 CVEs added to CISA KEV today.
- Exploitation likelihood rose sharply (EPSS 33% → 81% · rising (+49%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **24** |


## CVEs

### CVE-2024-57726
**SimpleHelp Missing Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** simple-help simplehelp
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T19:26:52.160
- **CWE:** CWE-862
- **Risk score:** 88
- **KEV:** added 2026-04-24

> SimpleHelp remote support software v5.5.7 and before has a vulnerability that allows low-privileges technicians to create API keys with excessive permissions. These API keys can be used to escalate privileges to the server admin role.

### CVE-2025-27007
**Privilege Escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:26:14.197
- **CWE:** CWE-266
- **Risk score:** 86
- **EPSS 32.7% (2026-04-02) → 81.5% (2026-04-24), Δ +48.8%**

> Incorrect Privilege Assignment vulnerability in Brainstorm Force OttoKit suretriggers allows Privilege Escalation.This issue affects OttoKit: from n/a through <= 1.0.82.

### CVE-2026-41478
**Saltcorn is an extensible, open source, no-code database application builder.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.9
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T18:57:20.293
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-24)

> Saltcorn is an extensible, open source, no-code database application builder. Prior to 1.4.6, 1.5.6, and 1.6.0-beta.5, a SQL injection vulnerability in Saltcorn’s mobile-sync routes allows any authenticated low-privilege user with read access to at least one table to inject arbit…

### CVE-2024-49653
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:19:46.100
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 30.3% (2026-04-02) → 59.0% (2026-04-24), Δ +28.6%**

> Unrestricted Upload of File with Dangerous Type vulnerability in james-eggers Portfolleo portfolleo allows Upload a Web Shell to a Web Server.This issue affects Portfolleo: from n/a through <= 1.2.

### CVE-2024-49681
**SQL Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:19:49.413
- **CWE:** CWE-89
- **Risk score:** 85
- **EPSS 21.7% (2026-04-02) → 51.3% (2026-04-24), Δ +29.6%**

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in activity-log.com WP Sessions Time Monitoring Full Automatic activitytime allows SQL Injection.This issue affects WP Sessions Time Monitoring Full Automatic: from n/a through <= 1…

### CVE-2024-50473
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:20:01.083
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 30.6% (2026-04-02) → 61.5% (2026-04-24), Δ +30.9%**

> Unrestricted Upload of File with Dangerous Type vulnerability in Ajar Productions Ajar in5 Embed ajar-productions-in5-embed allows Upload a Web Shell to a Web Server.This issue affects Ajar in5 Embed: from n/a through <= 3.1.3.

### CVE-2024-50482
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:20:02.087
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 24.9% (2026-04-02) → 55.5% (2026-04-24), Δ +30.6%**

> Unrestricted Upload of File with Dangerous Type vulnerability in Chetan Khandla Woocommerce Product Design woo-product-design allows Upload a Web Shell to a Web Server.This issue affects Woocommerce Product Design: from n/a through <= 1.0.0.

### CVE-2024-50490
**privilege escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:20:03.093
- **CWE:** CWE-862
- **Risk score:** 86
- **EPSS 20.2% (2026-04-02) → 52.4% (2026-04-24), Δ +32.2%**

> Missing Authorization vulnerability in lowcage PegaPoll pegapoll allows Accessing Functionality Not Properly Constrained by ACLs.This issue affects PegaPoll: from n/a through <= 1.0.2.

### CVE-2024-50493
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:20:03.453
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 24.9% (2026-04-02) → 55.5% (2026-04-24), Δ +30.6%**

> Unrestricted Upload of File with Dangerous Type vulnerability in masterhomepage Automatic Translation automatic-translation allows Upload a Web Shell to a Web Server.This issue affects Automatic Translation: from n/a through <= 1.0.4.

### CVE-2024-51788
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:20:39.530
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 29.6% (2026-04-02) → 62.1% (2026-04-24), Δ +32.5%**

> Unrestricted Upload of File with Dangerous Type vulnerability in Joshua Wolfe The Novel Design Store Directory noveldesign-store-directory allows Upload a Web Shell to a Web Server.This issue affects The Novel Design Store Directory: from n/a through <= 4.3.0.

### CVE-2024-52375
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:21:02.377
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 31.4% (2026-04-05) → 60.6% (2026-04-24), Δ +29.2%**

> Unrestricted Upload of File with Dangerous Type vulnerability in Arttia Creative Datasets Manager by Arttia Creative datasets-manager-by-arttia-creative.This issue affects Datasets Manager by Arttia Creative: from n/a through <= 1.5.

### CVE-2024-52380
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:21:02.960
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 23.2% (2026-04-05) → 60.4% (2026-04-24), Δ +37.2%**

> Unrestricted Upload of File with Dangerous Type vulnerability in softpulseinfotech Picsmize picsmize allows Upload a Web Shell to a Web Server.This issue affects Picsmize: from n/a through <= 1.0.0.

### CVE-2024-57728
**SimpleHelp Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** simple-help simplehelp
- **Attack:** Path Traversal
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T19:27:00.700
- **CWE:** CWE-59
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-04-24

> SimpleHelp remote support software v5.5.7 and before allows admin users to upload arbitrary files anywhere on the file system by uploading a crafted zip file (i.e. zip slip). This can be exploited to execute arbitrary code on the host in the context of the SimpleHelp server user.

### CVE-2024-7399
**Samsung MagicINFO 9 Server Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** samsung magicinfo_9_server
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T20:23:57.990
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-04-24

> Improper limitation of a pathname to a restricted directory vulnerability in Samsung MagicINFO 9 Server version before 21.1050 allows attackers to write arbitrary file as system authority.

### CVE-2025-29635
**D-Link DIR-823X Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** dlink dir-823x_firmware
- **Attack:** Command Injection
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T19:27:15.560
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2026-04-24

> A command injection vulnerability in D-Link DIR-823X 240126 and 240802 allows an authorized attacker to execute arbitrary commands on remote devices by sending a POST request to /goform/set_prohibiting via the corresponding function, triggering remote command execution.

### CVE-2026-31668
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T20:08:54.307
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-24)

> In the Linux kernel, the following vulnerability has been resolved:

seg6: separate dst_cache for input and output paths in seg6 lwtunnel

The seg6 lwtunnel uses a single dst_cache per encap route, shared
between seg6_input_core() and seg6_output_core(). These two paths
can perfo…

### CVE-2026-31669
**linux linux_kernel Use-After-Free**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T20:09:25.553
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-24)

> In the Linux kernel, the following vulnerability has been resolved:

mptcp: fix slab-use-after-free in __inet_lookup_established

The ehash table lookups are lockless and rely on
SLAB_TYPESAFE_BY_RCU to guarantee socket memory stability
during RCU read-side critical sections. Bot…

### CVE-2026-39920
**BridgeHead FileStore versions prior to 24A (released in early 2024) expose the Apache Axis2 administration module on network-accessible e...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T17:55:55.317
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-24)

> BridgeHead FileStore versions prior to 24A (released in early 2024) expose the Apache Axis2 administration module on network-accessible endpoints with default credentials that allows unauthenticated remote attackers to execute arbitrary OS commands. Attackers can authenticate to …

### CVE-2026-41248
**Clerk JavaScript is the official JavaScript repository for Clerk authentication.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T20:56:50.103
- **CWE:** CWE-436
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-24)

> Clerk JavaScript is the official JavaScript repository for Clerk authentication. createRouteMatcher in @clerk/nextjs, @clerk/nuxt, and @clerk/astro can be bypassed by certain crafted requests, allowing them to skip middleware gating and reach downstream handlers. This vulnerabili…

### CVE-2026-41327
**Dgraph is an open source distributed GraphQL database.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T18:57:20.293
- **CWE:** CWE-943
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-24)

> Dgraph is an open source distributed GraphQL database. Prior to 25.3.3, a vulnerability has been found in Dgraph that gives an unauthenticated attacker full read access to every piece of data in the database. This affects Dgraph's default configuration where ACL is not enabled. T…

### CVE-2026-41328
**Dgraph is an open source distributed GraphQL database.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T18:57:20.293
- **CWE:** CWE-943
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-24)

> Dgraph is an open source distributed GraphQL database. Prior to 25.3.3, a vulnerability has been found in Dgraph that gives an unauthenticated attacker full read access to every piece of data in the database. This affects Dgraph's default configuration where ACL is not enabled. T…

### CVE-2026-41428
**Budibase is an open-source low-code platform.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T18:57:20.293
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-24)

> Budibase is an open-source low-code platform. Prior to 3.35.4, the authenticated middleware uses unanchored regular expressions to match public (no-auth) endpoint patterns against ctx.request.url. Since ctx.request.url in Koa includes the query string, an attacker can access any …

### CVE-2026-41492
**Dgraph is an open source distributed GraphQL database.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T18:57:20.293
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-24)

> Dgraph is an open source distributed GraphQL database. Prior to 25.3.3, Dgraphl exposes the process command line through the unauthenticated /debug/vars endpoint on Alpha. Because the admin token is commonly supplied via the --security "token=..." startup flag, an unauthenticated…

### CVE-2026-6911
**Missing JWT signature verification in AWS Ops Wheel allows unauthenticated attackers to forge JWT tokens and gain unintended administrati...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-24T17:56:41.280
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-24)

> Missing JWT signature verification in AWS Ops Wheel allows unauthenticated attackers to forge JWT tokens and gain unintended administrative access to the application, including the ability to read, modify, and delete all application data across tenants and manage Cognito user acc…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-24*
