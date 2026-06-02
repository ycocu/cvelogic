# Daily Threat Intelligence — April 22, 2026

**Digest window (UTC):** 2026-04-22
**Generated:** 2026-06-02T07:34:59Z

## Threat brief

Microsoft Defender added to CISA KEV — confirmed in-the-wild exploitation. · Missing Authorization vulnerability in Ronald Huereca Highlight and Share highlight-and-share all...: public exploit or PoC linked (privilege escalation) · Phpmyadmin — exploitation likelihood rose sharply (EPSS 0.4% → 36% · rising (+36%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Defender added to CISA KEV — confirmed in-the-wild exploitation.
- Missing Authorization vulnerability in Ronald Huereca Highlight and Share highlight-and-share all...: public exploit or PoC linked (privilege escalation)
- Phpmyadmin — exploitation likelihood rose sharply (EPSS 0.4% → 36% · rising (+36%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2026-33825
**Microsoft Defender Insufficient Granularity of Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft defender_antimalware_platform
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T17:26:30.713
- **CWE:** CWE-1220
- **Risk score:** 88
- **KEV:** added 2026-04-22

> Insufficient granularity of access control in Microsoft Defender allows an authorized attacker to elevate privileges locally.

### CVE-2025-67586
**Missing Authorization vulnerability in Ronald Huereca Highlight and Share highlight-and-share allows Exploiting Incorrectly Configured Ac...**
- **Signals:** EXP
- **Attack:** privilege escalation
- **CVSS max:** 4.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T18:16:44.833
- **CWE:** CWE-862
- **Risk score:** 78
- **EXP:** ref published 2026-04-22

> Missing Authorization vulnerability in Ronald Huereca Highlight and Share highlight-and-share allows Exploiting Incorrectly Configured Access Control Security Levels.This issue affects Highlight and Share: from n/a through <= 5.2.0.

### CVE-2009-1285
**phpmyadmin phpmyadmin**
- **Signals:** EPSS
- **Asset:** phpmyadmin phpmyadmin
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 0.4% (2026-02-25) → 36.1% (2026-04-22), Δ +35.7%**

> Static code injection vulnerability in the getConfigFile function in setup/lib/ConfigFile.class.php in phpMyAdmin 3.x before 3.1.3.2 allows remote attackers to inject arbitrary PHP code into configuration files.

### CVE-2014-3931
**Multi-Router Looking Glass (MRLG) Buffer Overflow Vulnerability**
- **Signals:** EPSS
- **Asset:** multi-router_looking_glass_project multi-router_looking_glass
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T18:55:50.843
- **CWE:** CWE-119
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 35.6% (2026-03-04) → 50.0% (2026-04-22), Δ +14.4%**

> fastping.c in MRLG (aka Multi-Router Looking Glass) before 5.5.0 allows remote attackers to cause an arbitrary memory write and memory corruption.

### CVE-2018-25270
**thinkphp thinkphp RCE**
- **Signals:** CVSS
- **Asset:** thinkphp thinkphp
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T17:20:13.943
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-22)

> ThinkPHP 5.0.23 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary PHP code by invoking functions through the routing parameter. Attackers can craft requests to the index.php endpoint with malicious function parameters to exe…

### CVE-2018-25272
**ELBA5 5.8.0 contains a remote code execution vulnerability that allows attackers to obtain database credentials and execute arbitrary com...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T20:46:33.890
- **CWE:** CWE-326
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-22)

> ELBA5 5.8.0 contains a remote code execution vulnerability that allows attackers to obtain database credentials and execute arbitrary commands with SYSTEM level permissions. Attackers can connect to the database using default connector credentials, decrypt the DBA password, and e…

### CVE-2025-7771
**ThrottleStop.sys, a legitimate driver, exposes two IOCTL interfaces that allow arbitrary read and write access to physical memory via the...**
- **Signals:** EXP
- **Attack:** privilege escalation
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-782
- **Risk score:** 78
- **EXP:** ref published 2026-04-22

> ThrottleStop.sys, a legitimate driver, exposes two IOCTL interfaces that allow arbitrary read and write access to physical memory via the MmMapIoSpace function. This insecure implementation can be exploited by a malicious user-mode application to patch the running Windows kernel …

### CVE-2026-31478
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T23:23:52.747
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-22)

> In the Linux kernel, the following vulnerability has been resolved:

ksmbd: replace hardcoded hdr2_len with offsetof() in smb2_calc_max_out_buf_len()

After this commit (e2b76ab8b5c9 "ksmbd: add support for read compound"),
response buffer management was changed to use dynamic io…

### CVE-2026-31501
**In the Linux kernel, the following vulnerability has been resolved: net: ti: icssg-prueth: fix use-after-free of CPPI descriptor in RX pa...**
- **Signals:** CVSS
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T15:16:09.710
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-22)

> In the Linux kernel, the following vulnerability has been resolved:

net: ti: icssg-prueth: fix use-after-free of CPPI descriptor in RX path

cppi5_hdesc_get_psdata() returns a pointer into the CPPI descriptor.
In both emac_rx_packet() and emac_rx_packet_zc(), the descriptor is
f…

### CVE-2026-33471
**nimiq nimiq_proof-of-stake**
- **Signals:** CVSS
- **Asset:** nimiq nimiq_proof-of-stake
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T17:11:40.037
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-22)

> nimiq-block contains block primitives to be used in Nimiq's Rust implementation. `SkipBlockProof::verify` computes its quorum check using `BitSet.len()`, then iterates `BitSet` indices and casts each `usize` index to `u16` (`slot as u16`) for slot lookup. Prior to version 1.3.0, …

### CVE-2026-33656
**espocrm espocrm**
- **Signals:** CVSS
- **Asset:** espocrm espocrm
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T17:04:54.173
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-22)

> EspoCRM is an open source customer relationship management application. Prior to version 9.3.4, EspoCRM's built-in formula scripting engine allowing updating attachment's sourceId thus allowing an authenticated admin to overwrite the `sourceId` field on `Attachment` entities. Bec…

### CVE-2026-34415
**Xerte Online Toolkits versions 3.15 and earlier contain an incomplete input validation vulnerability in the elFinder connector endpoint t...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T20:16:25.387
- **CWE:** CWE-184
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-22)

> Xerte Online Toolkits versions 3.15 and earlier contain an incomplete input validation vulnerability in the elFinder connector endpoint that fails to block PHP-executable extensions .php4 due to an incorrect regex pattern. Unauthenticated attackers can exploit this flaw combined …

### CVE-2026-41167
**Jellystat is a free and open source Statistics App for Jellyfin.**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T20:46:33.890
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-22)

> Jellystat is a free and open source Statistics App for Jellyfin. Prior to version 1.1.10, multiple API endpoints in Jellystat build SQL queries by interpolating unsanitized request-body fields directly into raw SQL strings. An authenticated user can inject arbitrary SQL via `POST…

### CVE-2026-41468
**Beghelli Sicuro24 SicuroWeb embeds AngularJS 1.5.2, an end-of-life component containing known sandbox escape primitives.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T21:18:45.917
- **CWE:** CWE-1104
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-22)

> Beghelli Sicuro24 SicuroWeb embeds AngularJS 1.5.2, an end-of-life component containing known sandbox escape primitives. When combined with template injection present in the same application, these primitives allow attackers to escape the AngularJS sandbox and achieve arbitrary J…

### CVE-2026-6356
**augmentt augmentt privilege escalation**
- **Signals:** CVSS
- **Asset:** augmentt augmentt
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T20:06:18.500
- **CWE:** CWE-1220
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-22)

> A vulnerability in the web application allows standard users to escalate their privileges to those of a super administrator through parameter manipulation, enabling them to access and modify sensitive information.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-22*
