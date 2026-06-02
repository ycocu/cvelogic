# Daily Threat Intelligence — May 02, 2025

**Digest window (UTC):** 2025-05-02
**Generated:** 2026-06-02T07:32:39Z

## Threat brief

Commvault Command Center added to CISA KEV — confirmed in-the-wild exploitation. · Siemens Simatic S7-300 Cpu — exploitation likelihood rose sharply (EPSS 33% → 51% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Commvault Command Center added to CISA KEV — confirmed in-the-wild exploitation.
- Siemens Simatic S7-300 Cpu — exploitation likelihood rose sharply (EPSS 33% → 51% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-34028
**Commvault Command Center Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** commvault commvault
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:57:56.350
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-05-02

> The Commvault Command Center Innovation Release allows an unauthenticated actor to upload ZIP files that represent install packages that, when expanded by the target server, are vulnerable to path traversal vulnerability that can result in Remote Code Execution via malicious JSP.…

### CVE-2015-2177
**siemens simatic_s7-300_cpu DoS**
- **Signals:** EPSS
- **Asset:** siemens simatic_s7-300_cpu_firmware
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 83
- **EPSS 33.2% (2025-04-28) → 50.6% (2025-05-02), Δ +17.4%**

> Siemens SIMATIC S7-300 CPU devices allow remote attackers to cause a denial of service (defect-mode transition) via crafted packets on (1) TCP port 102 or (2) Profibus.

### CVE-2025-2605
**honeywell mb-secure_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** honeywell mb-secure_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2025-05-17T06:15:18.303
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-02)

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in Honeywell MB-Secure allows Privilege Abuse. This issue affects MB-Secure: from V11.04 before V12.53 and MB-Secure PRO from V01.06 before V03.09.Honeywell also recommends up…

### CVE-2024-58136
**Yiiframework Yii Improper Protection of Alternate Path Vulnerability**
- **Signals:** KEV
- **Asset:** yiiframework yii
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:28:54.540
- **CWE:** CWE-424
- **Risk score:** 88
- **KEV:** added 2025-05-02

> Yii 2 before 2.0.52 mishandles the attaching of behavior that is defined by an __class array key, a CVE-2024-4990 regression, as exploited in the wild in February through April 2025.

### CVE-2025-2421
**felisify sambabox**
- **Signals:** CVSS
- **Asset:** felisify sambabox
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-09-12T08:15:45.057
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Profelis Informatics SambaBox allows Code Injection.This issue affects SambaBox: before 5.1.

### CVE-2025-2812
**mydata ticket_sales_automation SQL Injection**
- **Signals:** CVSS
- **Asset:** mydata ticket_sales_automation
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-05-28T15:15:24.520
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mydata Informatics Ticket Sales Automation allows Blind SQL Injection.This issue affects Ticket Sales Automation: before 03.04.2025 (DD.MM.YYYY).

### CVE-2025-3708
**le-show le-yan SQL Injection**
- **Signals:** CVSS
- **Asset:** le-show le-yan
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-07T16:50:44.930
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Le-show medical practice management system from Le-yan has a SQL Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary SQL commands to read, modify, and delete database contents.

### CVE-2025-3709
**flowring agentflow**
- **Signals:** CVSS
- **Asset:** flowring agentflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-07T16:50:52.680
- **CWE:** CWE-307
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Agentflow from Flowring Technology has an Account Lockout Bypass vulnerability, allowing unauthenticated remote attackers to exploit this vulnerability to perform password brute force attack.

### CVE-2025-3927
**digigram pyko-out**
- **Signals:** CVSS
- **Asset:** digigram pyko-out
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-17T14:18:20.087
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Digigram's PYKO-OUT audio-over-IP (AoIP) web-server does not require a password by default, allowing any attacker with the target IP address to connect and compromise the device, potentially pivoting to connected network or hardware devices.

### CVE-2025-44868
**wavlink wl-wn530h4_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** wavlink wl-wn530h4_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-13T13:04:52.783
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Wavlink WL-WN530H4 20220801 was found to contain a command injection vulnerability in the ping_test function of the adm.cgi via the pingIp parameter. This vulnerability allows attackers to execute arbitrary commands via a crafted request.

### CVE-2025-44872
**tenda ac9_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** tenda ac9_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-27T14:21:40.517
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Tenda AC9 V15.03.06.42_multi was found to contain a command injection vulnerability in the formsetUsbUnload function via the deviceName parameter. This vulnerability allows attackers to execute arbitrary commands via a crafted request.

### CVE-2025-44877
**tenda ac9_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** tenda ac9_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-27T14:21:50.710
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> Tenda AC9 V15.03.06.42_multi was found to contain a command injection vulnerability in the formSetSambaConf function via the usbname parameter. This vulnerability allows attackers to execute arbitrary commands via a crafted request.

### CVE-2025-45800
**totolink a950rg_firmware**
- **Signals:** CVSS
- **Asset:** totolink a950rg_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-04T17:26:02.743
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-02)

> TOTOLINK A950RG V4.1.2cu.5204_B20210112 contains a command execution vulnerability in the setDeviceName interface of the /lib/cste_modules/global.so library, specifically in the processing of the deviceMac parameter.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-02*
