# Daily Threat Intelligence — February 04, 2026

**Digest window (UTC):** 2026-02-04
**Generated:** 2026-06-02T07:34:21Z

## Threat brief

Fortinet FortiWeb: public exploit or PoC linked (SQL Injection) · Zohocorp Manageengine Assetexplorer — exploitation likelihood rose sharply (EPSS 4.4% → 21% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet FortiWeb: public exploit or PoC linked (SQL Injection)
- Zohocorp Manageengine Assetexplorer — exploitation likelihood rose sharply (EPSS 4.4% → 21% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 10 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **22** |


## CVEs

### CVE-2025-25257
**Fortinet FortiWeb SQL Injection Vulnerability**
- **Signals:** EXP
- **Asset:** fortinet fortiweb
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T16:49:01.030
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> An improper neutralization of special elements used in an SQL command ('SQL Injection') vulnerability [CWE-89] vulnerability in Fortinet FortiWeb 7.6.0 through 7.6.3, FortiWeb 7.4.0 through 7.4.7, FortiWeb 7.2.0 through 7.2.10, FortiWeb 7.0.0 through 7.0.10 allows an unauthentica…

### CVE-2025-32023
**redis redis RCE**
- **Signals:** EXP
- **Asset:** redis redis
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-04T20:16:03.493
- **CWE:** CWE-680
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> Redis is an open source, in-memory database that persists on disk. From 2.8 to before 8.0.3, 7.4.5, 7.2.10, and 6.2.19, an authenticated user may use a specially crafted string to trigger a stack/heap out of bounds write on hyperloglog operations, potentially leading to remote co…

### CVE-2019-19034
**zohocorp manageengine_assetexplorer privilege escalation**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_assetexplorer
- **Attack:** privilege escalation
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:34:02.193
- **CWE:** CWE-78
- **Risk score:** 82
- **EPSS 4.4% (2025-11-21) → 20.9% (2026-02-04), Δ +16.5%**

> Zoho ManageEngine Asset Explorer 6.5 does not validate the System Center Configuration Manager (SCCM) database username when dynamically generating a command to schedule scans for SCCM. This allows an attacker to execute arbitrary commands on the AssetExplorer Server with NT AUTH…

### CVE-2019-15976
**cisco data_center_network_manager privilege escalation**
- **Signals:** EPSS
- **Asset:** cisco data_center_network_manager
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:29:51.320
- **CWE:** CWE-798
- **CWE:** CWE-798
- **Risk score:** 86
- **EPSS 28.2% (2025-11-21) → 43.0% (2026-02-04), Δ +14.7%**

> Multiple vulnerabilities in the authentication mechanisms of Cisco Data Center Network Manager (DCNM) could allow an unauthenticated, remote attacker to bypass authentication and execute arbitrary actions with administrative privileges on an affected device. For more information …

### CVE-2024-23334
**aiohttp aiohttp**
- **Signals:** EXP
- **Asset:** aiohttp aiohttp
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-02-04T20:16:01.790
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> aiohttp is an asynchronous HTTP client/server framework for asyncio and Python. When using aiohttp as a web server and configuring static routes, it is necessary to specify the root path for static files. Additionally, the option 'follow_symlinks' can be used to determine whether…

### CVE-2025-1097
**A security issue was discovered in ingress-nginx https://github.com/kubernetes/ingress-nginx where the `auth-tls-match-cn` Ingress annota...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> A security issue was discovered in  ingress-nginx https://github.com/kubernetes/ingress-nginx  where the `auth-tls-match-cn` Ingress annotation can be used to inject configuration into nginx. This can lead to arbitrary code execution in the context of the ingress-nginx controller…

### CVE-2025-1098
**A security issue was discovered in ingress-nginx https://github.com/kubernetes/ingress-nginx where the `mirror-target` and `mirror-host`...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> A security issue was discovered in  ingress-nginx https://github.com/kubernetes/ingress-nginx  where the `mirror-target` and `mirror-host` Ingress annotations can be used to inject arbitrary configuration into nginx. This can lead to arbitrary code execution in the context of the…

### CVE-2025-13375
**IBM Common Cryptographic Architecture (CCA) 7.5.52 and 8.4.82 could allow an unauthenticated user to execute arbitrary commands with elev...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-250
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-04)

> IBM Common Cryptographic Architecture (CCA) 7.5.52 and 8.4.82 could allow an unauthenticated user to execute arbitrary commands with elevated privileges on the system.

### CVE-2025-1974
**A security issue was discovered in Kubernetes where under certain conditions, an unauthenticated attacker with access to the pod network...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-653
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> A security issue was discovered in Kubernetes where under certain conditions, an unauthenticated attacker with access to the pod network can achieve arbitrary code execution in the context of the ingress-nginx controller. This can lead to disclosure of Secrets accessible to the c…

### CVE-2025-24054
**Microsoft Windows NTLM Hash Disclosure Spoofing Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T21:25:23.527
- **CWE:** CWE-73
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> External control of file name or path in Windows NTLM allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-24514
**A security issue was discovered in ingress-nginx https://github.com/kubernetes/ingress-nginx where the `auth-url` Ingress annotation can...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> A security issue was discovered in  ingress-nginx https://github.com/kubernetes/ingress-nginx  where the `auth-url` Ingress annotation can be used to inject configuration into nginx. This can lead to arbitrary code execution in the context of the ingress-nginx controller, and dis…

### CVE-2025-58180
**octoprint octoprint**
- **Signals:** EXP
- **Asset:** octoprint octoprint
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-18T17:37:54.243
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> OctoPrint provides a web interface for controlling consumer 3D printers. OctoPrint versions up until and including 1.11.2 contain a vulnerability that allows an authenticated attacker to upload a file under a specially crafted filename that will allow arbitrary command execution …

### CVE-2025-62615
**agpt autogpt_platform SSRF**
- **Signals:** CVSS
- **Asset:** agpt autogpt_platform
- **Attack:** SSRF
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T19:57:15.010
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-04)

> AutoGPT is a platform that allows users to create, deploy, and manage continuous artificial intelligence agents that automate complex workflows. Prior to autogpt-platform-beta-v0.6.34, in RSSFeedBlock, the third-party library urllib.request.urlopen is used directly to access the …

### CVE-2025-62616
**agpt autogpt_platform SSRF**
- **Signals:** CVSS
- **Asset:** agpt autogpt_platform
- **Attack:** SSRF
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T20:05:19.853
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-04)

> AutoGPT is a platform that allows users to create, deploy, and manage continuous artificial intelligence agents that automate complex workflows. Prior to autogpt-platform-beta-v0.6.34, in SendDiscordFileBlock, the third-party library aiohttp.ClientSession().get is used directly t…

### CVE-2025-9074
**A vulnerability was identified in Docker Desktop that allows local running Linux containers to access the Docker Engine API via the confi...**
- **Signals:** EXP
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-668
- **Risk score:** 78
- **EXP:** ref published 2026-02-04

> A vulnerability was identified in Docker Desktop that allows local running Linux containers to access the Docker Engine API via the configured Docker subnet, at 192.168.65.7:2375 by default. This vulnerability occurs with or without Enhanced Container Isolation (ECI) enabled, and…

### CVE-2026-25505
**bambuddy bambuddy**
- **Signals:** CVSS
- **Asset:** bambuddy bambuddy
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T20:25:05.510
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-04)

> Bambuddy is a self-hosted print archive and management system for Bambu Lab 3D printers. Prior to version 0.1.7, a hardcoded secret key used for signing JWTs is checked into source code and ManyAPI routes do not check authentication. This issue has been patched in version 0.1.7.

### CVE-2026-25512
**group-office group_office RCE**
- **Signals:** CVSS
- **Asset:** group-office group_office
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:15:49.477
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-04)

> Group-Office is an enterprise customer relationship management and groupware tool. Prior to versions 6.8.150, 25.0.82, and 26.0.5, there is a remote code execution (RCE) vulnerability in Group-Office. The endpoint email/message/tnefAttachmentFromTempFile directly concatenates the…

### CVE-2026-25521
**locutus locutus**
- **Signals:** CVSS
- **Asset:** locutus locutus
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T21:20:40.797
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-04)

> Locutus brings stdlibs of other programming languages to JavaScript for educational purposes. In versions from 2.0.12 to before 2.0.39, a prototype pollution vulnerability exists in locutus. Despite a previous fix that attempted to mitigate prototype pollution by checking whether…

### CVE-2026-25526
**hubspot jinjava**
- **Signals:** CVSS
- **Asset:** hubspot jinjava
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T21:00:42.130
- **CWE:** CWE-1336
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-04)

> JinJava is a Java-based template engine based on django template syntax, adapted to render jinja templates. Prior to versions 2.7.6 and 2.8.3, JinJava is vulnerable to arbitrary Java execution via bypass through ForTag. This allows arbitrary Java class instantiation and file acce…

### CVE-2026-25539
**b3log siyuan RCE**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:10:21.850
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-04)

> SiYuan is a personal knowledge management system. Prior to version 3.5.5, the /api/file/copyFile endpoint does not validate the dest parameter, allowing authenticated users to write files to arbitrary locations on the filesystem. This can lead to Remote Code Execution (RCE) by wr…

### CVE-2026-25547
**@isaacs/brace-expansion is a hybrid CJS/ESM TypeScript fork of brace-expansion.**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1333
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-04)

> @isaacs/brace-expansion is a hybrid CJS/ESM TypeScript fork of brace-expansion. Prior to version 5.0.1, @isaacs/brace-expansion is vulnerable to a denial of service (DoS) issue caused by unbounded brace range expansion. When an attacker provides a pattern containing repeated nume…

### CVE-2026-25579
**navidrome navidrome**
- **Signals:** CVSS
- **Asset:** navidrome navidrome
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T19:01:54.600
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-04)

> Navidrome is an open source web-based music collection server and streamer. Prior to version 0.60.0, authenticated users can crash the Navidrome server by supplying an excessively large size parameter to /rest/getCoverArt or to a shared-image URL (/share/img/<token>). When proces…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-04*
