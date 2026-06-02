# Daily Threat Intelligence — January 05, 2026

**Digest window (UTC):** 2026-01-05
**Generated:** 2026-06-02T07:34:07Z

## Threat brief

Btglobalservices Bt Consumer Webhelper — exploitation likelihood rose sharply (EPSS 14% → 33% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Btglobalservices Bt Consumer Webhelper — exploitation likelihood rose sharply (EPSS 14% → 33% · rising (+18%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 8 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2007-2983
**btglobalservices bt_consumer_webhelper Buffer Overflow**
- **Signals:** EPSS
- **Asset:** btglobalservices bt_consumer_webhelper
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 14.4% (2025-04-25) → 32.6% (2026-01-05), Δ +18.2%**

> Multiple buffer overflows in the British Telecommunications Consumer webhelper ActiveX control before 2.0.0.8 in btwebcontrol.dll allow remote attackers to execute arbitrary code via unspecified vectors.

### CVE-2009-1329
**mini-stream shadow_stream_recorder Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mini-stream shadow_stream_recorder
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 10.3% (2025-09-06) → 28.2% (2026-01-05), Δ +17.9%**

> Stack-based buffer overflow in Mini-stream Shadow Stream Recorder 3.0.1.7 allows remote attackers to execute arbitrary code via a long URI in a playlist (.m3u) file.

### CVE-2025-59157
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T15:02:21.787
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-05)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.420.7, the Git Repository field during project creation is vulnerable to command injection. User input is not properly sanitized, allowing attackers to …

### CVE-2009-1351
**heikki_ylinen apollo Buffer Overflow**
- **Signals:** EPSS
- **Asset:** heikki_ylinen apollo
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 7.9% (2025-11-07) → 23.3% (2026-01-05), Δ +15.5%**

> Heap-based buffer overflow in Apollo 37zz allows remote attackers to cause a denial of service (application crash) and possibly execute arbitrary code via a long URI in a playlist (.m3u) file.

### CVE-2009-1352
**dawningsoft powerchm Buffer Overflow**
- **Signals:** EPSS
- **Asset:** dawningsoft powerchm
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 7.4% (2025-11-07) → 23.3% (2026-01-05), Δ +15.9%**

> Stack-based buffer overflow in Dawningsoft PowerCHM 5.7 allows remote attackers to cause a denial of service (application crash) and possibly execute arbitrary code via an HTML file with a link to a long URL, as demonstrated by a .rar URL.

### CVE-2009-1356
**elecard elecard_avc_hd_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** elecard elecard_avc_hd_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 5.0% (2025-03-30) → 15.1% (2026-01-05), Δ +10.0%**

> Stack-based buffer overflow in Elecard AVC HD Player allows remote attackers to execute arbitrary code via a long MP3 filename in a playlist (.xpl) file.

### CVE-2009-1449
**coolplayer coolplayer Buffer Overflow**
- **Signals:** EPSS
- **Asset:** coolplayer coolplayer
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 7.3% (2025-09-16) → 23.2% (2026-01-05), Δ +15.8%**

> Stack-based buffer overflow in PortableApps CoolPlayer Portable (aka CoolPlayer+ Portable) 2.19.1 allows remote attackers to execute arbitrary code via a skin file (skin.ini) with a large PlaylistSkin parameter.  NOTE: this may overlap CVE-2008-5735.

### CVE-2009-1759
**rahul ctorrent Buffer Overflow**
- **Signals:** EPSS
- **Asset:** rahul dtorrent
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 32.6% (2025-04-25) → 46.8% (2026-01-05), Δ +14.3%**

> Stack-based buffer overflow in the btFiles::BuildFromMI function (trunk/btfiles.cpp) in Enhanced CTorrent (aka dTorrent) 3.3.2 and probably earlier, and CTorrent 1.3.4, allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a Torrent …

### CVE-2018-8097
**python-eve eve**
- **Signals:** EPSS
- **Asset:** python-eve eve
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:13:15.170
- **CWE:** CWE-94
- **Risk score:** 83
- **EPSS 8.8% (2025-11-21) → 19.1% (2026-01-05), Δ +10.3%**

> io/mongo/parser.py in Eve (aka pyeve) before 0.7.5 allows remote attackers to execute arbitrary code via Code Injection in the where parameter.

### CVE-2025-27807
**samsung exynos_1080_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** samsung exynos_990_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T14:14:39.700
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-05)

> An issue was discovered in Samsung Mobile Processor, Wearable Processor, and Modem Exynos 980, 990, 850, 1080, 2100, 1280, 2200, 1330, 1380, 1480, 2400, 1580, 9110, W920, W930, W1000, Modem 5123, Modem 5300, Modem 5400. The lack of a length check leads to out-of-bounds writes via…

### CVE-2025-59156
**coollabs coolify RCE**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T15:03:44.317
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-05)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.420.7, a Remote Code Execution (RCE)*vulnerability exists in Coolify's application deployment workflow. This flaw allows a low-privileged member to inje…

### CVE-2025-59158
**coollabs coolify XSS**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** XSS
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T15:08:33.550
- **CWE:** CWE-116
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-05)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Coolify versions prior to and including v4.0.0-beta.420.6 are vulnerable to a stored cross-site scripting (XSS) attack in the project creation workflow. An authenticated user with …

### CVE-2025-64419
**coollabs coolify**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T14:38:09.697
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-05)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.445, parameters coming from docker-compose.yaml are not sanitized when used in commands. If a victim user creates an application from an attacker reposi…

### CVE-2025-64420
**coollabs coolify privilege escalation**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T14:31:59.247
- **CWE:** CWE-522
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-05)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. In Coolify versions prior to and including v4.0.0-beta.434, low privileged users are able to see the private key of the root user on the Coolify instance. This allows them to ssh t…

### CVE-2025-64424
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T18:37:11.620
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-05)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. In Coolify versions up to and including v4.0.0-beta.434, a command injection vulnerability exists in the git source input fields of a resource, allowing a low privileged user (memb…

### CVE-2025-67397
**passy passy**
- **Signals:** CVSS
- **Asset:** passy passy
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T21:12:00.927
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-05)

> An issue in Passy v.1.6.3 allows a remote authenticated attacker to execute arbitrary commands via a crafted HTTP request using a specific payload injection.

### CVE-2025-68428
**parall jspdf Path Traversal**
- **Signals:** CVSS
- **Asset:** parall jspdf
- **Attack:** Path Traversal
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-16T18:34:24.440
- **CWE:** CWE-35
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-05)

> jsPDF is a library to generate PDFs in JavaScript. Prior to version 4.0.0, user control of the first argument of the loadFile method in the node.js build allows local file inclusion/path traversal. If given the possibility to pass unsanitized paths to the loadFile method, a user …

### CVE-2026-0625
**Multiple D-Link DSL/DIR/DNS devices contain an authentication bypass and improper access control vulnerability in the dnscfg.cgi endpoint...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T00:16:49.257
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-05)

> Multiple D-Link DSL/DIR/DNS devices contain an authentication bypass and improper access control vulnerability in the dnscfg.cgi endpoint that allows an unauthenticated attacker to access DNS configuration functionality. By directly requesting this endpoint, an attacker can modif…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-05*
