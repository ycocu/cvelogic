# Daily Threat Intelligence — May 10, 2026

**Digest window (UTC):** 2026-05-10
**Generated:** 2026-06-02T07:03:58Z

## Threat brief

WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 25% → 36% · rising (+11%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
- Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 25% → 36% · rising (+11%)).
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

### CVE-2018-8653
**Microsoft Internet Explorer Scripting Engine Memory Corruption Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** RCE
- **CVSS max:** 7.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T14:46:20.633
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 80
- **EPSS 25.0% (2026-04-13) → 35.6% (2026-05-10), Δ +10.6%**

> A remote code execution vulnerability exists in the way that the scripting engine handles objects in memory in Internet Explorer, aka "Scripting Engine Memory Corruption Vulnerability." This affects Internet Explorer 9, Internet Explorer 11, Internet Explorer 10. This CVE ID is u…

### CVE-2026-6722
**php php**
- **Signals:** CVSS
- **Asset:** php php
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T17:48:21.643
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-05-10)

> In PHP versions 8.2.* before 8.2.31, 8.3.* before 8.3.31, 8.4.* before 8.4.21, and 8.5.* before 8.5.6, the SOAP extension's object deduplication mechanism stores pointers to PHP objects in a global map without incrementing their reference counts. When an apache:Map node contains …

### CVE-2021-47932
**WordPress TheCartPress 1.5.3.6 contains an unauthenticated privilege escalation vulnerability that allows attackers to create administrat...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:24:15.210
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-10)

> WordPress TheCartPress 1.5.3.6 contains an unauthenticated privilege escalation vulnerability that allows attackers to create administrator accounts by submitting crafted requests to the AJAX handler. Attackers can send POST requests to the tcp_register_and_login_ajax action with…

### CVE-2021-47923
**OpenCart 3.0.3.8 contains a session fixation vulnerability that allows attackers to hijack user sessions by injecting arbitrary values in...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:24:15.210
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-10)

> OpenCart 3.0.3.8 contains a session fixation vulnerability that allows attackers to hijack user sessions by injecting arbitrary values into the OCSESSID cookie. Attackers can set malicious OCSESSID cookie values that the server accepts and maintains, enabling session takeover and…

### CVE-2021-47933
**WordPress MStore API 2.0.6 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious file...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:24:15.210
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-10)

> WordPress MStore API 2.0.6 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious files by sending POST requests to the REST API endpoint. Attackers can upload PHP files with arbitrary names to the config_file endpoint to achieve…

### CVE-2021-47936
**OpenCATS 0.9.4 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary commands by uplo...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:24:15.210
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-10)

> OpenCATS 0.9.4 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary commands by uploading malicious PHP files disguised as resume attachments. Attackers can upload PHP payloads through the careers job application endpoint and e…

### CVE-2021-47940
**WordPress Plugin Download From Files version 1.48 and earlier contains an arbitrary file upload vulnerability that allows unauthenticated...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:24:15.210
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-10)

> WordPress Plugin Download From Files version 1.48 and earlier contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious files by exploiting the AJAX fileupload action. Attackers can send POST requests to the admin-ajax.php endpoint …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-10*
