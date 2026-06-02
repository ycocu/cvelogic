# Daily Threat Intelligence — December 16, 2025

**Digest window (UTC):** 2025-12-16
**Generated:** 2026-06-02T07:33:59Z

## Threat brief

Fortinet Multiple Products added to CISA KEV — confirmed in-the-wild exploitation. · SQL injection vulnerability in Summar Software´s Portal del Empleado.: public exploit or PoC linked (SQL Injection) · Dlink Dir-818l Firmware — exploitation likelihood rose sharply (EPSS 8.4% → 25% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet Multiple Products added to CISA KEV — confirmed in-the-wild exploitation.
- SQL injection vulnerability in Summar Software´s Portal del Empleado.: public exploit or PoC linked (SQL Injection)
- Dlink Dir-818l Firmware — exploitation likelihood rose sharply (EPSS 8.4% → 25% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-59718
**Fortinet Multiple Products Improper Verification of Cryptographic Signature Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet fortiproxy
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T13:54:45.390
- **CWE:** CWE-347
- **Risk score:** 88
- **KEV:** added 2025-12-16

> A improper verification of cryptographic signature vulnerability in Fortinet FortiOS 7.6.0 through 7.6.3, FortiOS 7.4.0 through 7.4.8, FortiOS 7.2.0 through 7.2.11, FortiOS 7.0.0 through 7.0.17, FortiProxy 7.6.0 through 7.6.3, FortiProxy 7.4.0 through 7.4.10, FortiProxy 7.2.0 thr…

### CVE-2025-40677
**SQL injection vulnerability in Summar Software´s Portal del Empleado.**
- **Signals:** EXP
- **Attack:** SQL Injection
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-16

> SQL injection vulnerability in Summar Software´s Portal del Empleado. This vulnerability allows an attacker to retrieve, create, update, and delete the database by sending a POST request using the parameter “ctl00$ContentPlaceHolder1$filtroNombre” in “/MemberPages/quienesquien.as…

### CVE-2022-35620
**dlink dir-818l_firmware RCE**
- **Signals:** EPSS
- **Asset:** dlink dir-818l_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:11:23.460
- **Risk score:** 86
- **EPSS 8.4% (2025-11-29) → 25.2% (2025-12-16), Δ +16.8%**

> D-LINK DIR-818LW A1:DIR818L_FW105b01 was discovered to contain a remote code execution (RCE) vulnerability via the function binary.soapcgi_main.

### CVE-2025-33210
**nvidia isaac_lab Code Execution**
- **Signals:** CVSS
- **Asset:** nvidia isaac_lab
- **Attack:** Code Execution
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T16:16:46.700
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-12-16)

> NVIDIA Isaac Lab contains a deserialization vulnerability.  A successful exploit of this vulnerability might lead to code execution.

### CVE-2025-37164
**Hewlett Packard Enterprise (HPE) OneView Code Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** hpe oneview
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-10T02:00:01.860
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-16)

> A remote code execution issue exists in HPE OneView.

### CVE-2025-46295
**claris filemaker_server RCE**
- **Signals:** CVSS
- **Asset:** claris filemaker_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-23T14:50:09.840
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-16)

> Apache Commons Text versions prior to 1.10.0 included interpolation features that could be abused when applications passed untrusted input into the text-substitution API. Because some interpolators could trigger actions like executing commands or accessing external resources, an …

### CVE-2025-50398
**mercurycom d196g_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** mercurycom d196g_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T15:30:24.640
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-16)

> Mercury D196G d196gv1-cn-up_2020-01-09_11.21.44 is vulnerable to Buffer Overflow in the function sub_404CAEDC via the parameter fac_password.

### CVE-2025-50401
**mercurycom d196g_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** mercurycom d196g_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T15:30:28.040
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-16)

> Mercury D196G d196gv1-cn-up_2020-01-09_11.21.44 is vulnerable to Buffer Overflow in the function sub_404CAEDC via the parameter password.

### CVE-2025-59342
**esm.sh is a nobuild content delivery network(CDN) for modern web development.**
- **Signals:** EXP
- **CVSS max:** 5.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-24
- **Risk score:** 78
- **EXP:** ref published 2025-12-16

> esm.sh is a nobuild content delivery network(CDN) for modern web development. In 136 and earlier, a path-traversal flaw in the handling of the X-Zone-Id HTTP header allows an attacker to cause the application to write files outside the intended storage location. The header value …

### CVE-2025-62863
**amperecomputing ampereone_a128-34x_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** amperecomputing ampereone_a192-32m_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T20:57:29.577
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-16)

> Ampere AmpereOne AC03 devices before 3.5.9.3, AmpereOne AC04 devices before 4.4.5.2, and AmpereOne M devices before 5.4.5.1 allow an incorrectly formed SMC call to UEFI-MM PCIe driver that could result in an out-of-bounds write within PCIe driver’s S-EL0 address space.

### CVE-2025-62864
**amperecomputing ampereone_a128-34x_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** amperecomputing ampereone_a192-32m_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T20:58:05.087
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-16)

> Ampere AmpereOne AC03 devices before 3.5.9.3, AmpereOne AC04 devices before 4.4.5.2, and AmpereOne M devices before 5.4.5.1 allow an incorrectly formed SMC call to UEFI-MM MMCommunicate service that could result in an out-of-bounds write within the UEFI-MM Secure Partition contex…

### CVE-2025-63414
**allskyteam allsky RCE**
- **Signals:** CVSS
- **Asset:** allskyteam allsky
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T00:25:34.513
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-16)

> A Path Traversal vulnerability in the Allsky WebUI version v2024.12.06_06 allows an unauthenticated remote attacker to achieve arbitrary command execution. By sending a crafted HTTP request to the /html/execute.php endpoint with a malicious payload in the id parameter, an attacke…

### CVE-2025-65834
**meltytech shotcut Buffer Overflow**
- **Signals:** CVSS
- **Asset:** meltytech shotcut
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-07T21:02:38.483
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-16)

> Meltytech Shotcut 25.10.31 is vulnerable to Buffer Overflow. A memory access violation occurs when processing MLT project files with manipulated width and height parameters. By setting these values to extremely large numbers, the application attempts to allocate excessive memory …

### CVE-2025-68270
**The Open edX Platform is a learning management platform.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-16)

> The Open edX Platform is a learning management platform. Prior to commit 05d0d0936daf82c476617257aa6c35f0cd4ca060, CourseLimitedStaffRole users are able to access and edit courses in studio if they are granted the role on an org rather than on a course, and CourseLimitedStaffRole…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-16*
