# Daily Threat Intelligence — September 04, 2025

**Digest window (UTC):** 2025-09-04
**Generated:** 2026-06-02T07:33:21Z

## Threat brief

Android Runtime added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Android Runtime added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-48543
**Android Runtime Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** google android
- **Attack:** Use-After-Free
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T14:52:51.863
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-09-04

> In multiple locations, there is a possible way to escape chrome sandbox to attack android system_server due to a use after free. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-54914
**microsoft azure_networking privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_networking
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-20T19:21:37.337
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-04)

> Azure Networking Elevation of Privilege Vulnerability

### CVE-2025-55241
**microsoft entra_id privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft entra_id
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-09-24T19:15:37.787
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-04)

> Azure Entra ID Elevation of Privilege Vulnerability

### CVE-2025-36897
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-05T16:38:32.233
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-04)

> In unknown of cd_CnMsgCodecUserApi.cpp, there is a possible out of bounds write due to a missing bounds check. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-36904
**google android privilege escalation**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-05T16:37:36.547
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-04)

> WLAN in Android before 2025-09-05 on Google Pixel devices allows elevation of privilege, aka A-396458384.

### CVE-2025-38352
**Linux Kernel Time-of-Check Time-of-Use (TOCTOU) Race Condition Vulnerability**
- **Signals:** KEV
- **Asset:** linux linux_kernel
- **CVSS max:** 7.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-08T16:28:23.960
- **CWE:** CWE-367
- **Risk score:** 88
- **KEV:** added 2025-09-04

> In the Linux kernel, the following vulnerability has been resolved:

posix-cpu-timers: fix race between handle_posix_cpu_timers() and posix_cpu_timer_del()

If an exiting non-autoreaping task has already passed exit_notify() and
calls handle_posix_cpu_timers() from IRQ, it can be…

### CVE-2025-53690
**Sitecore Multiple Products Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** sitecore experience_commerce
- **Attack:** Deserialization
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:39:16.593
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-09-04

> Deserialization of Untrusted Data vulnerability in Sitecore Experience Manager (XM), Sitecore Experience Platform (XP) allows Code Injection.This issue affects Experience Manager (XM): through 9.0; Experience Platform (XP): through 9.0.

### CVE-2025-55190
**argoproj argo_cd**
- **Signals:** CVSS
- **Asset:** argoproj argo_cd
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-19T15:20:53.823
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-04)

> Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes. In versions 2.13.0 through 2.13.8, 2.14.0 through 2.14.15, 3.0.0 through 3.0.12 and 3.1.0-rc1 through 3.1.1, API tokens with project-level permissions are able to retrieve sensitive repository credentials (…

### CVE-2025-55244
**microsoft azure_ai_bot_service privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_ai_bot_service
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T15:46:21.553
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-04)

> Azure Bot Service Elevation of Privilege Vulnerability

### CVE-2025-58357
**5ire 5ire**
- **Signals:** CVSS
- **Asset:** 5ire 5ire
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T20:09:16.937
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-04)

> 5ire is a cross-platform desktop artificial intelligence assistant and model context protocol client. Version 0.13.2 contains a vulnerability in the chat page's script gadgets that enables content injection attacks through multiple vectors: malicious prompt injection pages, compr…

### CVE-2025-58361
**Promptcraft Forge Studio is a toolkit for evaluating, optimizing, and maintaining LLM-powered applications.**
- **Signals:** CVSS
- **Attack:** cross-site scripting
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-04)

> Promptcraft Forge Studio is a toolkit for evaluating, optimizing, and maintaining  LLM-powered applications. All versions contain an non-exhaustive URL scheme check that does not protect against XSS. User-controlled URLs pass through src/utils/validation.ts, but the check only st…

### CVE-2025-7385
**Input from search query parameter in GOV CMS is not sanitized properly, leading to a Blind SQL injection vulnerability, which might be ex...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-04)

> Input from search query parameter in GOV CMS is not sanitized properly, leading to a Blind SQL injection vulnerability, which might be exploited by an unauthenticated remote attacker. 

Versions 4.0 and above are not affected.

### CVE-2025-8311
**dotCMS versions 24.03.22 and after, identified a Boolean-based blind SQLi vulnerability in the /api/v1/contenttype endpoint.**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-04)

> dotCMS versions 24.03.22 and after, identified a Boolean-based blind SQLi vulnerability in the /api/v1/contenttype endpoint. This endpoint uses the sites query parameter, which accepts a comma-separated list of site identifiers or keys.

The vulnerability was triggered via the si…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-04*
