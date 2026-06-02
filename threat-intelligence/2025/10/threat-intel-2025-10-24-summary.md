# Daily Threat Intelligence — October 24, 2025

**Digest window (UTC):** 2025-10-24
**Generated:** 2026-06-02T07:33:39Z

## Threat brief

Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation. · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation.
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-59287
**Microsoft Windows Server Update Service (WSUS) Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_server_2012
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T14:33:19.727
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-10-24

> Deserialization of untrusted data in Windows Server Update Service allows an unauthorized attacker to execute code over a network.

### CVE-2025-12176
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T15:05:15.617
- **CWE:** CWE-1242
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-24)

> Undocumented administrative accounts were getting created to facilitate access for applications running on board.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2025-43995
**dell storage_manager Auth Bypass**
- **Signals:** CVSS
- **Asset:** dell storage_manager
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T14:43:05.420
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> Dell Storage Center - Dell Storage Manager, version(s) 20.1.21, contain(s) an Improper Authentication vulnerability. An unauthenticated attacker with remote access could potentially exploit this vulnerability, leading to Protection mechanism bypass. Authentication Bypass in DSM D…

### CVE-2025-11253
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Aksis Technology Inc.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Aksis Technology Inc. Netty ERP allows SQL Injection.This issue affects Netty ERP: before V.1.1000.

### CVE-2025-54236
**Adobe Commerce and Magento Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** adobe commerce
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T22:00:01.607
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2025-10-24

> Adobe Commerce versions 2.4.9-alpha2, 2.4.8-p2, 2.4.7-p7, 2.4.6-p12, 2.4.5-p14, 2.4.4-p15 and earlier are affected by an Improper Input Validation vulnerability. A successful attacker can abuse this to achieve session takeover, increasing the confidentiality, and integrity impact…

### CVE-2025-60548
**dlink dir-600l_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-600l_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T02:32:13.937
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> D-Link DIR600L Ax FW116WWb01 was discovered to contain a buffer overflow via the curTime parameter in the function formLanSetupRouterSettings.

### CVE-2025-60553
**dlink dir-600l_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-600l_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T02:31:39.963
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> D-Link DIR600L Ax FW116WWb01 was discovered to contain a buffer overflow via the curTime parameter in the function formSetWAN_Wizard52.

### CVE-2025-60554
**dlink dir-600l_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-600l_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T02:31:20.300
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> D-Link DIR600L Ax FW116WWb01 was discovered to contain a buffer overflow via the curTime parameter in the function formSetEnableWizard.

### CVE-2025-60803
**Antabot White-Jotter up to commit 9bcadc was discovered to contain an unauthenticated remote code execution (RCE) vulnerability via the c...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> Antabot White-Jotter up to commit 9bcadc was discovered to contain an unauthenticated remote code execution (RCE) vulnerability via the component /api/aaa;/../register.

### CVE-2025-6440
**The WooCommerce Designer Pro plugin for WordPress, used by the Pricom - Printing Company & Design Services WordPress theme, is vulnerable...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-24)

> The WooCommerce Designer Pro plugin for WordPress, used by the Pricom - Printing Company & Design Services WordPress theme, is vulnerable to arbitrary file uploads due to missing file type validation in the 'wcdp_save_canvas_design_ajax' function in all versions up to, and includ…

### CVE-2025-8536
**A SQL injection vulnerability has been identified in DobryCMS.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-24)

> A SQL injection vulnerability has been identified in DobryCMS. Improper neutralization of input provided by user into language functionality allows for SQL Injection attacks.

This issue affects older branches of this software.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-24*
