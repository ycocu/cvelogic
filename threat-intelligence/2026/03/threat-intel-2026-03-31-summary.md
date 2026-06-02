# Daily Threat Intelligence — March 31, 2026

**Digest window (UTC):** 2026-03-31
**Generated:** 2026-06-02T07:34:48Z

## Threat brief

Ivanti Avalanche — exploitation likelihood rose sharply (EPSS 4.3% → 36% · rising (+32%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Avalanche — exploitation likelihood rose sharply (EPSS 4.3% → 36% · rising (+32%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2022-36983
**ivanti avalanche**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:12.600
- **CWE:** CWE-306
- **CWE:** CWE-306
- **Risk score:** 86
- **EPSS 4.3% (2026-03-30) → 36.3% (2026-03-31), Δ +32.0%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Ivanti Avalanche. Authentication is not required to exploit this vulnerability. The specific flaw exists within the SetSettings class. The issue results from the lack of authenticatio…

### CVE-2017-0100
**microsoft windows_10 privilege escalation**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-287
- **Risk score:** 83
- **EPSS 34.7% (2026-02-01) → 50.3% (2026-03-31), Δ +15.7%**

> A DCOM object in Helppane.exe in Microsoft Windows 7 SP1; Windows Server 2008 R2; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows local users to gain privileges via a crafted application, aka "Windows H…

### CVE-2026-30278
**funair fly_is_fun RCE**
- **Signals:** CVSS
- **Asset:** funair fly_is_fun
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T15:01:01.663
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-31)

> An arbitrary file overwrite vulnerability in FLY is FUN Aviation Navigation v35.33 allows attackers to overwrite critical internal files via the file import process, leading to arbitrary code execution or information exposure.

### CVE-2021-27030
**autodesk fbx_review RCE**
- **Signals:** EPSS
- **Asset:** autodesk fbx_review
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:57:12.723
- **CWE:** CWE-22
- **Risk score:** 83
- **EPSS 42.8% (2026-03-10) → 55.3% (2026-03-31), Δ +12.6%**

> A user may be tricked into opening a malicious FBX file which may exploit a Directory Traversal Remote Code Execution vulnerability in FBX’s Review causing it to run arbitrary code on the system.

### CVE-2026-1579
**px4 autopilot**
- **Signals:** CVSS
- **Asset:** px4 autopilot
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T15:33:30.363
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-31)

> The MAVLink communication protocol does not require cryptographic 
authentication by default. When MAVLink 2.0 message signing is not 
enabled, any message -- including SERIAL_CONTROL, which provides 
interactive shell access -- can be sent by an unauthenticated party with
 acces…

### CVE-2026-30282
**uxgroupllc cast_to_tv Code Execution**
- **Signals:** CVSS
- **Asset:** uxgroupllc cast_to_tv
- **Attack:** Code Execution
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T21:00:07.770
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-31)

> An arbitrary file overwrite vulnerability in UXGROUP LLC Cast to TV Screen Mirroring v2.2.77 allows attackers to overwrite critical internal files via the file import process, leading to arbtrary code execution or information exposure.

### CVE-2026-30283
**peaksel animal_sounds_and_ringtones RCE**
- **Signals:** CVSS
- **Asset:** peaksel animal_sounds_and_ringtones
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T14:49:50.953
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-31)

> An arbitrary file overwrite vulnerability in PEAKSEL D.O.O. NIS Animal Sounds and Ringtones v1.3.0 allows attackers to overwrite critical internal files via the file import process, leading to arbitrary code execution or information exposure.

### CVE-2026-30285
**zora zora RCE**
- **Signals:** CVSS
- **Asset:** zora zora
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T16:11:37.583
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-31)

> An arbitrary file overwrite vulnerability in Zora: Post, Trade, Earn Crypto v2.60.0 allows attackers to overwrite critical internal files via the file import process, leading to arbitrary code execution or information exposure.

### CVE-2026-30286
**funambol zefiro RCE**
- **Signals:** CVSS
- **Asset:** funambol zefiro
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T18:26:13.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-31)

> An arbitrary file overwrite vulnerability in Funambol, Inc. Zefiro Cloud v32.0.2026011614 allows attackers to overwrite critical internal files via the file import process, leading to arbitrary code execution or information exposure.

### CVE-2026-3356
**The MS27102A Remote Spectrum Monitor is vulnerable to an authentication bypass that allows unauthorized users to access and manipulate it...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-01T14:23:37.727
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-31)

> The MS27102A Remote Spectrum Monitor is vulnerable to an authentication bypass that allows unauthorized users to access and manipulate its management interface. Because the device provides no mechanism to enable or configure authentication, the issue is inherent to its design rat…

### CVE-2026-34406
**aptrs aptrs**
- **Signals:** CVSS
- **Asset:** aptrs aptrs
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-10T15:43:33.397
- **CWE:** CWE-915
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-31)

> APTRS (Automated Penetration Testing Reporting System) is a Python and Django-based automated reporting tool designed for penetration testers and security organizations. Prior to version 2.0.1, the edit_user endpoint (POST /api/auth/edituser/<pk>) allows Any user who can reach th…

### CVE-2026-34448
**b3log siyuan cross-site scripting**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** cross-site scripting
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T16:58:40.760
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-31)

> SiYuan is a personal knowledge management system. Prior to version 3.6.2, an attacker who can place a malicious URL in an Attribute View mAsse field can trigger stored XSS when a victim opens the Gallery or Kanban view with “Cover From -> Asset Field” enabled. The vulnerable code…

### CVE-2026-34449
**b3log siyuan RCE**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T16:57:32.883
- **CWE:** CWE-942
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-31)

> SiYuan is a personal knowledge management system. Prior to version 3.6.2, a malicious website can achieve Remote Code Execution (RCE) on any desktop running SiYuan by exploiting the permissive CORS policy (Access-Control-Allow-Origin: * + Access-Control-Allow-Private-Network: tru…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-31*
