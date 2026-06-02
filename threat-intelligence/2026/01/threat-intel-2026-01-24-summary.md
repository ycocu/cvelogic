# Daily Threat Intelligence — January 24, 2026

**Digest window (UTC):** 2026-01-24
**Generated:** 2026-06-02T07:34:16Z

## Threat brief

Samba — exploitation likelihood rose sharply (EPSS 5.3% → 22% · rising (+17%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Samba — exploitation likelihood rose sharply (EPSS 5.3% → 22% · rising (+17%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2014-0239
**samba samba DoS**
- **Signals:** EPSS
- **Asset:** samba samba
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 78
- **EPSS 5.3% (2025-10-31) → 22.2% (2026-01-24), Δ +16.8%**

> The internal DNS server in Samba 4.x before 4.0.18 does not check the QR field in the header section of an incoming DNS message before sending a response, which allows remote attackers to cause a denial of service (CPU and bandwidth consumption) via a forged response packet that …

### CVE-2025-13952
**imaginationtech ddk Use-After-Free**
- **Signals:** CVSS
- **Asset:** imaginationtech ddk
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-28T18:33:18.030
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-24)

> A web page that contains unusual GPU shader code is loaded from the Internet into the GPU compiler process triggers a write use-after-free crash in the GPU shader compiler library. On certain platforms, when the compiler process has system privileges this could enable further exp…

### CVE-2026-22582
**salesforce marketing_cloud_engagement**
- **Signals:** CVSS
- **Asset:** salesforce marketing_cloud_engagement
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T16:13:12.287
- **CWE:** CWE-88
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-24)

> Improper Neutralization of Argument Delimiters in a Command ('Argument Injection') vulnerability in Salesforce Marketing Cloud Engagement (MicrositeUrl module) allows Web Services Protocol Manipulation. This issue affects Marketing Cloud Engagement: before January 21st, 2026.

### CVE-2025-13374
**The Kalrav AI Agent plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the kalrav_upload...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-24)

> The Kalrav AI Agent plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the kalrav_upload_file AJAX action in all versions up to, and including, 2.3.3. This makes it possible for unauthenticated attackers to upload arbitrary files o…

### CVE-2026-22583
**salesforce marketing_cloud_engagement**
- **Signals:** CVSS
- **Asset:** salesforce marketing_cloud_engagement
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T16:12:21.877
- **CWE:** CWE-88
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-24)

> Improper Neutralization of Argument Delimiters in a Command ('Argument Injection') vulnerability in Salesforce Marketing Cloud Engagement (CloudPagesUrl module) allows Web Services Protocol Manipulation. This issue affects Marketing Cloud Engagement: before January 21st, 2026.

### CVE-2026-22585
**salesforce marketing_cloud_engagement**
- **Signals:** CVSS
- **Asset:** salesforce marketing_cloud_engagement
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T16:08:29.020
- **CWE:** CWE-327
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-24)

> Use of a Broken or Risky Cryptographic Algorithm vulnerability in Salesforce Marketing Cloud Engagement (CloudPages, Forward to a Friend, Profile Center, Subscription Center, Unsub Center, View As Webpage modules) allows Web Services Protocol Manipulation. This issue affects Mark…

### CVE-2026-22586
**salesforce marketing_cloud_engagement**
- **Signals:** CVSS
- **Asset:** salesforce marketing_cloud_engagement
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T20:25:13.027
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-24)

> Hard-coded Cryptographic Key vulnerability in Salesforce Marketing Cloud Engagement (CloudPages, Forward to a Friend, Profile Center, Subscription Center, Unsub Center, View As Webpage modules) allows Web Services Protocol Manipulation. This issue affects Marketing Cloud Engageme…

### CVE-2026-24399
**chattermate chattermate**
- **Signals:** CVSS
- **Asset:** chattermate chattermate
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T16:05:57.580
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-24)

> ChatterMate is a no-code AI chatbot agent framework. In versions 1.0.8 and below, the chatbot accepts and executes malicious HTML/JavaScript payloads when supplied as chat input. Specifically, an <iframe> payload containing a javascript: URI can be processed and executed in the b…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-24*
