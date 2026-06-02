# Daily Threat Intelligence — January 23, 2026

**Digest window (UTC):** 2026-01-23
**Generated:** 2026-06-02T07:34:15Z

## Threat brief

Broadcom VMware VCenter Server added to CISA KEV — confirmed in-the-wild exploitation. · Open Group Cde Common Desktop Environment — exploitation likelihood rose sharply (EPSS 59% → 70% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Broadcom VMware VCenter Server added to CISA KEV — confirmed in-the-wild exploitation.
- Open Group Cde Common Desktop Environment — exploitation likelihood rose sharply (EPSS 59% → 70% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2024-37079
**Broadcom VMware vCenter Server Out-of-bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** vmware cloud_foundation
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-26T14:52:05.833
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2026-01-23

> vCenter Server contains a heap-overflow vulnerability in the implementation of the DCERPC protocol. A malicious actor with network access to vCenter Server may trigger this vulnerability by sending a specially crafted network packet potentially leading to remote code execution.

### CVE-2001-0803
**open_group cde_common_desktop_environment Buffer Overflow**
- **Signals:** EPSS
- **Asset:** open_group cde_common_desktop_environment
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 58.7% (2025-09-22) → 70.2% (2026-01-23), Δ +11.5%**

> Buffer overflow in the client connection routine of libDtSvc.so.1 in CDE Subprocess Control Service (dtspcd) allows remote attackers to execute arbitrary commands.

### CVE-2025-70983
**bladex springblade privilege escalation**
- **Signals:** CVSS
- **Asset:** bladex springblade
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:28:23.430
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-23)

> Incorrect access control in the authRoutes function of SpringBlade v4.5.0 allows attackers with low-level privileges to escalate privileges.

### CVE-2003-1165
**brs webweaver Buffer Overflow**
- **Signals:** EPSS
- **Asset:** brs webweaver
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 76
- **EPSS 8.2% (2025-06-08) → 18.6% (2026-01-23), Δ +10.4%**

> Buffer overflow in BRS WebWeaver 1.06 and earlier allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via an HTTP request with a long User-Agent header.

### CVE-2021-47891
**Unified Remote 3.9.0.2463 contains a remote code execution vulnerability that allows attackers to send crafted network packets to execute...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-23)

> Unified Remote 3.9.0.2463 contains a remote code execution vulnerability that allows attackers to send crafted network packets to execute arbitrary commands. Attackers can exploit the service by connecting to port 9512 and sending specially crafted packets to open a command promp…

### CVE-2022-25369
**An issue was discovered in Dynamicweb before 9.12.8.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-23)

> An issue was discovered in Dynamicweb before 9.12.8. An attacker can add a new administrator user without authentication. This flaw exists due to a logic issue when determining if the setup phases of the product can be run again. Once an attacker is authenticated as the new admin…

### CVE-2025-52024
**aptsys gemscms_backend**
- **Signals:** CVSS
- **Asset:** aptsys gemscms_backend
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:23:51.853
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-23)

> A vulnerability exists in the Aptsys POS Platform Web Services module thru 2025-05-28, which exposes internal API testing tools to unauthenticated users. By accessing specific URLs, an attacker is presented with a directory-style index listing all available backend services and P…

### CVE-2025-52025
**aptsys gemscms_backend SQL Injection**
- **Signals:** CVSS
- **Asset:** aptsys gemscms_backend
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:24:10.350
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-23)

> An SQL Injection vulnerability exists in the GetServiceByRestaurantID endpoint of the Aptsys gemscms POS Platform backend thru 2025-05-28. The vulnerability arises because user input is directly inserted into a dynamic SQL query syntax without proper sanitization or parameterizat…

### CVE-2025-67229
**todesktop builder**
- **Signals:** CVSS
- **Asset:** todesktop builder
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T18:44:08.557
- **CWE:** CWE-295
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-23)

> An improper certificate validation vulnerability exists in ToDesktop Builder v0.32.1 This vulnerability allows an unauthenticated, on-path attacker to spoof backend responses by exploiting insufficient certificate validation.

### CVE-2025-70457
**remyandrade modern_image_gallery_app RCE**
- **Signals:** CVSS
- **Asset:** remyandrade modern_image_gallery_app
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T17:59:24.497
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-23)

> A Remote Code Execution (RCE) vulnerability exists in Sourcecodester Modern Image Gallery App v1.0 within the gallery/upload.php component. The application fails to properly validate uploaded file contents. Additionally, the application preserves the user-supplied file extension …

### CVE-2025-70985
**ruoyi ruoyi**
- **Signals:** CVSS
- **Asset:** ruoyi ruoyi
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T21:27:40.100
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-23)

> Incorrect access control in the update function of RuoYi v4.8.2 allows unauthorized attackers to arbitrarily modify data outside of their scope.

### CVE-2026-22984
**linux linux_kernel Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-27T14:16:27.673
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-23)

> In the Linux kernel, the following vulnerability has been resolved:

libceph: prevent potential out-of-bounds reads in handle_auth_done()

Perform an explicit bounds check on payload_len to avoid a possible
out-of-bounds access in the callout.

[ idryomov: changelog ]

### CVE-2026-24423
**SmarterTools SmarterMail Missing Authentication for Critical Function Vulnerability**
- **Signals:** CVSS
- **Asset:** smartertools smartermail
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T16:45:15.323
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-23)

> SmarterTools SmarterMail versions prior to build 9511 contain an unauthenticated remote code execution vulnerability in the ConnectToHub API method. The attacker could point the SmarterMail to the malicious HTTP server, which serves the malicious OS command. This command will be …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-23*
