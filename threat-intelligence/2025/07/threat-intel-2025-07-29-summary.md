# Daily Threat Intelligence — July 29, 2025

**Digest window (UTC):** 2025-07-29
**Generated:** 2026-06-02T07:33:08Z

## Threat brief

5 new critical disclosures — review patch status on exposed services.

## Executive summary

- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2025-54381
**bentoml bentoml SSRF**
- **Signals:** CVSS
- **Asset:** bentoml bentoml
- **Attack:** SSRF
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-05T15:41:26.900
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-07-29)

> BentoML is a Python library for building online serving systems optimized for AI apps and model inference. In versions 1.4.0 until 1.4.19, the file upload processing system contains an SSRF vulnerability that allows unauthenticated remote attackers to force the server to make arb…

### CVE-2025-44136
**maptiler tileserver_php cross-site scripting**
- **Signals:** CVSS
- **Asset:** maptiler tileserver_php
- **Attack:** cross-site scripting
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-06T20:47:45.487
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-29)

> MapTiler Tileserver-php v2.0 is vulnerable to Cross Site Scripting (XSS). The GET parameter "layer" is reflected in an error message without html encoding. This leads to XSS and allows an unauthenticated attacker to execute arbitrary HTML or JavaScript code on a victim's browser.

### CVE-2025-40600
**sonicwall sonicos**
- **Signals:** CVSS
- **Asset:** sonicwall sonicos
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-11T14:59:40.867
- **CWE:** CWE-134
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-29)

> Use of Externally-Controlled Format String vulnerability in the SonicOS SSL VPN interface allows a remote unauthenticated attacker to cause service disruption.

### CVE-2025-46059
**langchain-ai v0.3.51 was discovered to contain an indirect prompt injection vulnerability in the GmailToolkit component.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-29)

> langchain-ai v0.3.51 was discovered to contain an indirect prompt injection vulnerability in the GmailToolkit component. This vulnerability allows attackers to execute arbitrary code and compromise the application via a crafted email message. NOTE: this is disputed by the Supplie…

### CVE-2025-50738
**usememos memos**
- **Signals:** CVSS
- **Asset:** usememos memos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-08-22T16:15:43.973
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-29)

> The Memos application, up to version v0.24.3, allows for the embedding of markdown images with arbitrary URLs. When a user views a memo containing such an image, their browser automatically fetches the image URL without explicit user consent or interaction beyond viewing the memo…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-29*
