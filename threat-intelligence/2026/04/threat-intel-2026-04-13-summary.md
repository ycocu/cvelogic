# Daily Threat Intelligence — April 13, 2026

**Digest window (UTC):** 2026-04-13
**Generated:** 2026-06-02T07:34:55Z

## Threat brief

Microsoft Windows: 4 CVEs added to CISA KEV today. · Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 9.9% → 22% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows: 4 CVEs added to CISA KEV today.
- Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 9.9% → 22% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 7 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2012-1854
**Microsoft Visual Basic for Applications Insecure Library Loading Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft office
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:05:40.017
- **CWE:** CWE-426
- **Risk score:** 88
- **KEV:** added 2026-04-13

> Untrusted search path vulnerability in VBE6.dll in Microsoft Office 2003 SP3, 2007 SP2 and SP3, and 2010 Gold and SP1; Microsoft Visual Basic for Applications (VBA); and Summit Microsoft Visual Basic for Applications SDK allows local users to gain privileges via a Trojan horse DL…

### CVE-2021-34507
**microsoft windows_10 Info Disclosure**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** Info Disclosure
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:10:33.673
- **Risk score:** 80
- **EPSS 9.9% (2025-12-28) → 22.0% (2026-04-13), Δ +12.1%**

> Windows Remote Assistance Information Disclosure Vulnerability

### CVE-2026-22562
**A malicious actor with access to the UniFi Play network could exploit a Path Traversal vulnerability found in the device firmware to writ...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-30T16:14:21.333
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-13)

> A malicious actor with access to the UniFi Play network could exploit a Path Traversal vulnerability found in the device firmware to write files on the system that could be used for a remote code execution (RCE).
 
Affected Products:
UniFi Play PowerAmp (Version 1.0.35 and earlie…

### CVE-2020-9715
**Adobe Acrobat Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** adobe acrobat_dc
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T14:45:00.160
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-04-13

> Adobe Acrobat and Reader versions 2020.009.20074 and earlier, 2020.001.30002, 2017.011.30171 and earlier, and 2015.006.30523 and earlier have an use-after-free vulnerability. Successful exploitation could lead to arbitrary code execution .

### CVE-2023-21529
**Microsoft Exchange Server Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft exchange_server
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T14:44:35.520
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-04-13

> Microsoft Exchange Server Remote Code Execution Vulnerability

### CVE-2023-36424
**Microsoft Windows Out-of-Bounds Read Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T14:44:43.473
- **CWE:** CWE-125
- **Risk score:** 88
- **KEV:** added 2026-04-13

> Windows Common Log File System Driver Elevation of Privilege Vulnerability

### CVE-2025-60710
**Microsoft Windows Link Following Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_11_24h2
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T14:44:19.867
- **CWE:** CWE-59
- **Risk score:** 88
- **KEV:** added 2026-04-13

> Improper link resolution before file access ('link following') in Host Process for Windows Tasks allows an authorized attacker to elevate privileges locally.

### CVE-2026-21643
**Fortinet SQL Injection Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet forticlientems
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T14:21:18.670
- **CWE:** CWE-89
- **Risk score:** 88
- **KEV:** added 2026-04-13

> An improper neutralization of special elements used in an sql command ('sql injection') vulnerability in Fortinet FortiClientEMS 7.4.4 may allow an unauthenticated attacker to execute unauthorized code or commands via specifically crafted HTTP requests.

### CVE-2026-22563
**A series of Improper Input Validation vulnerabilities could allow a Command Injection by a malicious actor with access to the UniFi Play...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-30T16:14:21.333
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-13)

> A series of Improper Input Validation vulnerabilities could allow a Command Injection by a malicious actor with access to the UniFi Play network.
 
Affected Products:
UniFi Play PowerAmp (Version 1.0.35 and earlier) 
UniFi Play Audio Port  (Version 1.0.24 and earlier)  

Mitigati…

### CVE-2026-22564
**An Improper Access Control vulnerability could allow a malicious actor with access to the UniFi Play network to enable SSH to make unauth...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-30T16:14:21.333
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-13)

> An Improper Access Control vulnerability could allow a malicious actor with access to the UniFi Play network to enable SSH to make unauthorized changes to the system.  

Affected Products:
UniFi Play PowerAmp (Version 1.0.35 and earlier) 
UniFi Play Audio Port  (Version 1.0.24 an…

### CVE-2026-23891
**decidim decidim Code Execution**
- **Signals:** CVSS
- **Asset:** decidim decidim
- **Attack:** Code Execution
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:40:25.103
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-13)

> Decidim is a participatory democracy framework. In versions below 0.30.5 and 0.31.0.rc1 through 0.31.0, a stored code execution vulnerability in the user name field allows a low-privileged attacker to execute arbitrary code in the context of any user who passively visits a commen…

### CVE-2026-31048
**An issue in the <code>pickle</code> protocol of Pyro v3.x allows attackers to execute arbitrary code via supplying a crafted pickled stri...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T19:18:46.690
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-13)

> An issue in the <code>pickle</code> protocol of Pyro v3.x allows attackers to execute arbitrary code via supplying a crafted pickled string message.

### CVE-2026-31282
**Totara LMS v19.1.5 and before is vulnerable to Incorrect Access Control.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-06T07:16:00.677
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-13)

> Totara LMS v19.1.5 and before is vulnerable to Incorrect Access Control. The login page code can be manipulated to reveal the login form. An attacker can chain that with missing rate-limit on the login form to launch a brute force attack. NOTE: this is disputed by the Supplier be…

### CVE-2026-31283
**In Totara LMS v19.1.5 and before, the forgot password API does not implement rate limiting for the target email address.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T08:16:29.853
- **CWE:** CWE-770
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-13)

> In Totara LMS v19.1.5 and before, the forgot password API does not implement rate limiting for the target email address. which can be used for an Email Bombing attack. NOTE: the Supplier's position is that the pwresettime configuration defaults to 30 minutes, the pwresettime conf…

### CVE-2026-34621
**Adobe Acrobat and Reader Prototype Pollution Vulnerability**
- **Signals:** KEV
- **Asset:** adobe acrobat_dc
- **Attack:** RCE
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T21:23:27.000
- **CWE:** CWE-1321
- **Risk score:** 88
- **KEV:** added 2026-04-13

> Acrobat Reader versions 24.001.30356, 26.001.21367 and earlier are affected by an Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution') vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation…

### CVE-2026-40042
**Pachno 1.0.6 contains an XML external entity injection vulnerability that allows unauthenticated attackers to read arbitrary files by exp...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-17T15:28:29.690
- **CWE:** CWE-403
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-13)

> Pachno 1.0.6 contains an XML external entity injection vulnerability that allows unauthenticated attackers to read arbitrary files by exploiting unsafe XML parsing in the TextParser helper. Attackers can inject malicious XML entities through wiki table syntax and inline tags in i…

### CVE-2026-40044
**Pachno 1.0.6 contains a deserialization vulnerability that allows unauthenticated attackers to execute arbitrary code by injecting malici...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-17T15:28:29.690
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-13)

> Pachno 1.0.6 contains a deserialization vulnerability that allows unauthenticated attackers to execute arbitrary code by injecting malicious serialized objects into cache files. Attackers can write PHP object payloads to world-writable cache files with predictable names in the ca…

### CVE-2026-6100
**Use-after-free (UAF) was possible in the `lzma.LZMADecompressor`, `bz2.BZ2Decompressor`, and `gzip.GzipFile` when a memory allocation fai...**
- **Signals:** CVSS
- **Attack:** Use-After-Free
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:18:16.507
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-13)

> Use-after-free (UAF) was possible in the `lzma.LZMADecompressor`, `bz2.BZ2Decompressor`, and `gzip.GzipFile` when a memory allocation fails with a `MemoryError` and the decompression instance is re-used. This scenario can be triggered if the process is under memory pressure. The …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-13*
