# Daily Threat Intelligence — April 18, 2026

**Digest window (UTC):** 2026-04-18
**Generated:** 2026-06-02T07:34:57Z

## Threat brief

Apache Tomcat — exploitation likelihood rose sharply (EPSS 37% → 67% · rising (+31%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apache Tomcat — exploitation likelihood rose sharply (EPSS 37% → 67% · rising (+31%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2002-1148
**apache tomcat**
- **Signals:** EPSS
- **Asset:** apache tomcat
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 36.7% (2025-07-27) → 67.3% (2026-04-18), Δ +30.6%**

> The default servlet (org.apache.catalina.servlets.DefaultServlet) in Tomcat 4.0.4 and 4.1.10 and earlier allows remote attackers to read source code for server files via a direct request to the servlet.

### CVE-2016-5696
**google android**
- **Signals:** EPSS
- **Asset:** google android
- **CVSS max:** 5.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 78
- **EPSS 29.2% (2026-04-01) → 52.0% (2026-04-18), Δ +22.8%**

> net/ipv4/tcp_input.c in the Linux kernel before 4.7 does not properly determine the rate of challenge ACK segments, which makes it easier for remote attackers to hijack TCP sessions via a blind in-window attack.

### CVE-2026-40492
**SAIL is a cross-platform library for loading and saving images with support for animation, metadata, and ICC profiles.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T18:55:47.120
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-18)

> SAIL is a cross-platform library for loading and saving images with support for animation, metadata, and ICC profiles. Prior to commit 36aa5c7ec8a2bb35f6fb867a1177a6f141156b02, the XWD codec resolves pixel format based on `pixmap_depth` but the byte-swap code uses `bits_per_pixel…

### CVE-2009-0114
**adobe air**
- **Signals:** EPSS
- **Asset:** adobe air
- **CVSS max:** 5.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 80
- **EPSS 22.9% (2025-11-11) → 36.2% (2026-04-18), Δ +13.4%**

> Unspecified vulnerability in the Settings Manager in Adobe Flash Player 9.x before 9.0.159.0 and 10.x before 10.0.22.87, and possibly other versions, allows remote attackers to trick a user into visiting an arbitrary URL via unknown vectors, related to "a potential Clickjacking i…

### CVE-2009-0519
**adobe air DoS**
- **Signals:** EPSS
- **Asset:** adobe air
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-20
- **Risk score:** 85
- **EPSS 29.1% (2025-11-11) → 43.7% (2026-04-18), Δ +14.6%**

> Unspecified vulnerability in Adobe Flash Player 9.x before 9.0.159.0 and 10.x before 10.0.22.87 allows remote attackers to cause a denial of service (browser crash) or possibly execute arbitrary code via a crafted Shockwave Flash (aka .swf) file.

### CVE-2011-3490
**measuresoft scadapro Buffer Overflow**
- **Signals:** EPSS
- **Asset:** measuresoft scadapro
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 19.9% (2025-10-21) → 40.6% (2026-04-18), Δ +20.6%**

> Multiple stack-based buffer overflows in service.exe in Measuresoft ScadaPro 4.0.0 and earlier allow remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long command to port 11234, as demonstrated with the TF command.

### CVE-2026-40317
**minecanton209 novumos Privilege Escalation**
- **Signals:** CVSS
- **Asset:** minecanton209 novumos
- **Attack:** Privilege Escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T14:05:07.953
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-18)

> NovumOS is a custom 32-bit operating system written in Zig and x86 Assembly. In versions prior to 0.24, Syscall 12 (JumpToUser) accepts an arbitrary entry point address from user-space registers without validation, allowing any Ring 3 user-mode process to jump to kernel addresses…

### CVE-2026-40324
**Hot Chocolate is an open-source GraphQL server.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T21:08:02.250
- **CWE:** CWE-674
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-18)

> Hot Chocolate is an open-source GraphQL server. Prior to versions 12.22.7, 13.9.16, 14.3.1, and 15.1.14, Hot Chocolate's recursive descent parser `Utf8GraphQLParser` has no recursion depth limit. A crafted GraphQL document with deeply nested selection sets, object values, list va…

### CVE-2026-40484
**ChurchCRM is an open-source church management system.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T18:59:46.333
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-18)

> ChurchCRM is an open-source church management system. In versions prior to 7.2.0, the database backup restore functionality extracts uploaded archive contents and copies files from the Images/ directory into the web-accessible document root using recursiveCopyDirectory(), which p…

### CVE-2026-40493
**SAIL is a cross-platform library for loading and saving images with support for animation, metadata, and ICC profiles.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T18:55:47.120
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-18)

> SAIL is a cross-platform library for loading and saving images with support for animation, metadata, and ICC profiles. Prior to commit c930284445ea3ff94451ccd7a57c999eca3bc979, the PSD codec computes bytes-per-pixel (`bpp`) from raw header fields `channels * depth`, but the pixel…

### CVE-2026-40494
**SAIL is a cross-platform library for loading and saving images with support for animation, metadata, and ICC profiles.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T18:55:47.120
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-18)

> SAIL is a cross-platform library for loading and saving images with support for animation, metadata, and ICC profiles. Prior to commit 45d48d1f2e8e0d73e80bc1fd5310cb57f4547302, the TGA codec's RLE decoder in `tga.c` has an asymmetric bounds check vulnerability. The run-packet pat…

### CVE-2026-40572
**minecanton209 novumos**
- **Signals:** CVSS
- **Asset:** minecanton209 novumos
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T14:13:28.607
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-04-18)

> NovumOS is a custom 32-bit operating system written in Zig and x86 Assembly. In versions prior to 0.24, Syscall 15 (MemoryMapRange) allows Ring 3 user-mode processes to map arbitrary virtual address ranges into their address space without validating against forbidden regions, inc…

### CVE-2026-40582
**ChurchCRM is an open-source church management system.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T18:59:46.333
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-18)

> ChurchCRM is an open-source church management system. In versions prior to 7.2.0, the /api/public/user/login endpoint validates only the username and password before returning the user's API key, bypassing the normal authentication flow that enforces account lockout and two-facto…

### CVE-2026-41242
**protobufjs_project protobufjs**
- **Signals:** CVSS
- **Asset:** protobufjs_project protobufjs
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T15:26:37.200
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-18)

> protobufjs compiles protobuf definitions into JavaScript (JS) functions. In versions prior to 8.0.1 and 7.5.5, attackers can inject arbitrary code in the "type" fields of protobuf definitions, which will then execute during object decoding using that definition. Versions 8.0.1 an…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-18*
