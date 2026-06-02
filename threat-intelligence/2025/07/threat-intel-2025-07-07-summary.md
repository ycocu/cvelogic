# Daily Threat Intelligence — July 07, 2025

**Digest window (UTC):** 2025-07-07
**Generated:** 2026-06-02T07:33:01Z

## Threat brief

Synacor Zimbra Collaboration Suite (ZCS) added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Synacor Zimbra Collaboration Suite (ZCS) added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2014-3931
**Multi-Router Looking Glass (MRLG) Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** multi-router_looking_glass_project multi-router_looking_glass
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T18:55:50.843
- **CWE:** CWE-119
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2025-07-07

> fastping.c in MRLG (aka Multi-Router Looking Glass) before 5.5.0 allows remote attackers to cause an arbitrary memory write and memory corruption.

### CVE-2025-53529
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-10T21:16:36.407
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-07)

> WeGIA is a web manager for charitable institutions. An SQL Injection vulnerability was identified in the /html/funcionario/profile_funcionario.php endpoint. The id_funcionario parameter is not properly sanitized or validated before being used in a SQL query, allowing an unauthent…

### CVE-2024-25176
**luajit luajit**
- **Signals:** CVSS
- **Asset:** luajit luajit
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:15:43.220
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-07)

> LuaJIT through 2.1 and OpenRusty luajit2 before v2.1-20240626 have a stack-buffer-overflow in lj_strfmt_wfnum in lj_strfmt_num.c.

### CVE-2016-10033
**PHPMailer Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** phpmailer_project phpmailer
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T16:27:03.000
- **CWE:** CWE-88
- **CWE:** CWE-88
- **Risk score:** 88
- **KEV:** added 2025-07-07

> The mailSend function in the isMail transport in PHPMailer before 5.2.18 might allow remote attackers to pass extra parameters to the mail command and consequently execute arbitrary code via a \" (backslash double quote) in a crafted Sender property.

### CVE-2019-5418
**Rails Ruby on Rails Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** rubyonrails rails
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:40:11.770
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-07-07

> There is a File Content Disclosure vulnerability in Action View <5.2.2.1, <5.1.6.2, <5.0.7.2, <4.2.11.1 and v3 where specially crafted accept headers can cause contents of arbitrary files on the target system's filesystem to be exposed.

### CVE-2019-9621
**Synacor Zimbra Collaboration Suite (ZCS) Server-Side Request Forgery (SSRF) Vulnerability**
- **Signals:** KEV
- **Asset:** synacor zimbra_collaboration_suite
- **Attack:** SSRF
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T16:46:00.360
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2025-07-07

> Zimbra Collaboration Suite before 8.6 patch 13, 8.7.x before 8.7.11 patch 10, and 8.8.x before 8.8.10 patch 7 or 8.8.x before 8.8.11 patch 3 allows SSRF via the ProxyServlet component.

### CVE-2024-25178
**luajit luajit Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** luajit luajit
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:15:43.557
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-07)

> LuaJIT through 2.1 and OpenRusty luajit2 before v2.1-20240314 have an out-of-bounds read in the stack-overflow handler in lj_state.c.

### CVE-2025-43932
**JobCenter through 7e7b0b2 allows account takeover via the password reset feature because SERVER_NAME is not configured and thus a reset d...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-07)

> JobCenter through 7e7b0b2 allows account takeover via the password reset feature because SERVER_NAME is not configured and thus a reset depends on the Host HTTP header.

### CVE-2025-43933
**fblog through 983bede allows account takeover via the password reset feature because SERVER_NAME is not configured and thus a reset depen...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-472
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-07)

> fblog through 983bede allows account takeover via the password reset feature because SERVER_NAME is not configured and thus a reset depends on the Host HTTP header.

### CVE-2025-45065
**employee record management system in php and mysql v1 was discovered to contain a SQL injection vulnerability via the loginerms.php endpo...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-07)

> employee record management system in php and mysql v1 was discovered to contain a SQL injection vulnerability via the loginerms.php endpoint.

### CVE-2025-45479
**educoder challenges**
- **Signals:** CVSS
- **Asset:** educoder challenges
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T19:24:56.213
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-07)

> Insufficient security mechanisms for created containers in educoder challenges v1.0 allow attackers to execute arbitrary code via injecting crafted content into a container.

### CVE-2025-47202
**samsung exynos_1080_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** samsung exynos_980_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T16:59:07.630
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-07)

> In RRC in Samsung Mobile Processor, Wearable Processor, and Modem Exynos 980, 990, 850, 1080, 2100, 1280, 2200, 1330, 1380, 1480, 2400, 1580, 9110, W920, W930, W1000, Modem 5123, Modem 5300, and Modem 5400, the lack of a length check leads to out-of-bounds writes.

### CVE-2025-53495
**Missing Authorization vulnerability in Wikimedia Foundation Mediawiki - AbuseFilter Extension allows Unauthorized Access.This issue affec...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-07)

> Missing Authorization vulnerability in Wikimedia Foundation Mediawiki - AbuseFilter Extension allows Unauthorized Access.This issue affects Mediawiki - AbuseFilter Extension: from 1.43.X before 1.43.2.

### CVE-2025-53499
**Missing Authorization vulnerability in Wikimedia Foundation Mediawiki - AbuseFilter Extension allows Unauthorized Access.This issue affec...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-07)

> Missing Authorization vulnerability in Wikimedia Foundation Mediawiki - AbuseFilter Extension allows Unauthorized Access.This issue affects Mediawiki - AbuseFilter Extension: from 1.43.X before 1.43.2.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-07*
