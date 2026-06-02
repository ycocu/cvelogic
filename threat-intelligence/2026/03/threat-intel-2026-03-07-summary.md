# Daily Threat Intelligence — March 07, 2026

**Digest window (UTC):** 2026-03-07
**Generated:** 2026-06-02T07:34:35Z

## Threat brief

Openssl — exploitation likelihood rose sharply (EPSS 17% → 32% · rising (+14%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Openssl — exploitation likelihood rose sharply (EPSS 17% → 32% · rising (+14%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2014-3571
**openssl openssl DoS**
- **Signals:** EPSS
- **Asset:** openssl openssl
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 78
- **EPSS 17.4% (2026-03-04) → 31.6% (2026-03-07), Δ +14.2%**

> OpenSSL before 0.9.8zd, 1.0.0 before 1.0.0p, and 1.0.1 before 1.0.1k allows remote attackers to cause a denial of service (NULL pointer dereference and application crash) via a crafted DTLS message that is processed with a different read operation for the handshake header than fo…

### CVE-2026-30860
**tencent weknora RCE**
- **Signals:** CVSS
- **Asset:** tencent weknora
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-09T17:35:41.243
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-07)

> WeKnora is an LLM-powered framework designed for deep document understanding and semantic retrieval. Prior to version 0.2.12, a remote code execution (RCE) vulnerability exists in the application's database query functionality. The validation system fails to recursively inspect c…

### CVE-2026-30861
**tencent weknora RCE**
- **Signals:** CVSS
- **Asset:** tencent weknora
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-09T17:35:56.647
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-07)

> WeKnora is an LLM-powered framework designed for deep document understanding and semantic retrieval. From version 0.2.5 to before version 0.2.10, an unauthenticated remote code execution (RCE) vulnerability exists in the MCP stdio configuration validation. The application allows …

### CVE-2026-25070
**seekswan zikestor_sks8310-8x_firmware RCE**
- **Signals:** CVSS
- **Asset:** seekswan zikestor_sks8310-8x_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-12T15:11:20.980
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-07)

> XikeStor SKS8310-8X Network Switch firmware versions 1.04.B07 and prior contain an OS command injection vulnerability in the /goform/PingTestSet endpoint that allows unauthenticated remote attackers to execute arbitrary operating system commands. Attackers can inject malicious co…

### CVE-2026-29191
**zitadel zitadel cross-site scripting**
- **Signals:** CVSS
- **Asset:** zitadel zitadel
- **Attack:** cross-site scripting
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T17:55:39.263
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-07)

> ZITADEL is an open source identity management platform. From version 4.0.0 to 4.11.1, a vulnerability in Zitadel's login V2 interface was discovered that allowed a possible account takeover via XSS in /saml-post Endpoint. This issue has been patched in version 4.12.0.

### CVE-2026-30832
**charm soft_serve**
- **Signals:** CVSS
- **Asset:** charm soft_serve
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T20:36:30.093
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-07)

> Soft Serve is a self-hostable Git server for the command line. From version 0.6.0 to before version 0.11.4, an authenticated SSH user can force the server to make HTTP requests to internal/private IP addresses by running repo import with a crafted --lfs-endpoint URL. The initial …

### CVE-2026-30863
**parseplatform parse-server**
- **Signals:** CVSS
- **Asset:** parseplatform parse-server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T16:50:58.427
- **CWE:** CWE-287
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-07)

> Parse Server is an open source backend that can be deployed to any infrastructure that can run Node.js. Prior to versions 8.6.10 and 9.5.0-alpha.11, the Google, Apple, and Facebook authentication adapters use JWT verification to validate identity tokens. When the adapter's audien…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-07*
