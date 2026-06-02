# Daily Threat Intelligence — August 21, 2025

**Digest window (UTC):** 2025-08-21
**Generated:** 2026-06-02T07:33:16Z

## Threat brief

Apple IOS, IPadOS, And MacOS added to CISA KEV — confirmed in-the-wild exploitation. · Netgear Nvrmini 2 — exploitation likelihood rose sharply (EPSS 10% → 33% · rising (+23%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apple IOS, IPadOS, And MacOS added to CISA KEV — confirmed in-the-wild exploitation.
- Netgear Nvrmini 2 — exploitation likelihood rose sharply (EPSS 10% → 33% · rising (+23%)).
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

### CVE-2025-43300
**Apple iOS, iPadOS, and macOS Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** apple ipados
- **Attack:** Memory Corruption
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T14:28:33.887
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-08-21

> An out-of-bounds write issue was addressed with improved bounds checking. This issue is fixed in iOS 15.8.5 and iPadOS 15.8.5, iOS 16.7.12 and iPadOS 16.7.12, iOS 18.6.2 and iPadOS 18.6.2, iPadOS 17.7.10, macOS Sequoia 15.6.1, macOS Sonoma 14.7.8, macOS Ventura 13.7.8. Processing…

### CVE-2016-5680
**netgear nvrmini_2 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** nuuo nvrmini_2
- **Attack:** Buffer Overflow
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 10.2% (2025-03-30) → 33.3% (2025-08-21), Δ +23.1%**

> Stack-based buffer overflow in cgi-bin/cgi_main in NUUO NVRmini 2 1.7.6 through 3.0.0 and NETGEAR ReadyNAS Surveillance 1.1.2 allows remote authenticated users to execute arbitrary code via the sn parameter to the transfer_license command.

### CVE-2025-53763
**microsoft purview_data_governance privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft purview_data_governance
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-25T18:38:23.763
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-21)

> Improper access control in Azure Databricks allows an unauthorized attacker to elevate privileges over a network.

### CVE-2010-20112
**Amlib’s NetOpacs webquery.dll contains a stack-based buffer overflow vulnerability triggered by improper handling of HTTP GET parameters.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-21)

> Amlib’s NetOpacs webquery.dll contains a stack-based buffer overflow vulnerability triggered by improper handling of HTTP GET parameters. Specifically, the application fails to enforce bounds on input supplied to the app parameter, allowing excessive data to overwrite memory stru…

### CVE-2010-20113
**easyftp_server_project easyftp_server Buffer Overflow**
- **Signals:** CVSS
- **Asset:** easyftp_server_project easyftp_server
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-10T20:06:30.820
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-21)

> EasyFTP Server 1.7.0.11 and earlier contains a stack-based buffer overflow vulnerability in its HTTP interface. When processing a GET request to list.html, the server fails to properly validate the length of the path parameter. Supplying an excessively long value causes a buffer …

### CVE-2010-20115
**Arcane Software’s Vermillion FTP Daemon (vftpd) versions up to and including 1.31 contains a memory corruption vulnerability triggered by...**
- **Signals:** CVSS
- **Attack:** Memory Corruption
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-704
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-21)

> Arcane Software’s Vermillion FTP Daemon (vftpd) versions up to and including 1.31 contains a memory corruption vulnerability triggered by a malformed FTP PORT command. The flaw arises from an out-of-bounds array access during input parsing, allowing an attacker to manipulate stac…

### CVE-2010-20121
**easyftp_server_project easyftp_server RCE**
- **Signals:** CVSS
- **Asset:** easyftp_server_project easyftp_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-10T20:03:36.037
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-21)

> EasyFTP Server versions up to 1.7.0.11 contain a stack-based buffer overflow vulnerability in the FTP command parser. When processing the CWD (Change Working Directory) command, the server fails to properly validate the length of the input string, allowing attackers to overwrite …

### CVE-2010-20122
**Xftp FTP Client version up to and including 3.0 (build 0238) contain a stack-based buffer overflow vulnerability triggered by a malicious...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-21)

> Xftp FTP Client version up to and including 3.0 (build 0238) contain a stack-based buffer overflow vulnerability triggered by a maliciously crafted PWD response from an FTP server. When the client connects to a server and receives an overly long directory string in response to th…

### CVE-2015-2055
**zhone_technologies gpon_2520_firmware DoS**
- **Signals:** EPSS
- **Asset:** zhone_technologies gpon_2520_firmware
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 81
- **EPSS 10.2% (2025-03-30) → 20.9% (2025-08-21), Δ +10.7%**

> Zhone GPON 2520 with firmware R4.0.2.566b allows remote attackers to cause a denial of service via a long string in the oldpassword parameter.

### CVE-2025-3128
**A remote unauthenticated attacker who has bypassed authentication could execute arbitrary OS commands to disclose, tamper with, destroy o...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-21)

> A remote unauthenticated attacker who has bypassed authentication could 
execute arbitrary OS commands to disclose, tamper with, destroy or 
delete information in Mitsubishi Electric smartRTU, or cause a denial-of
 service condition on the product.

### CVE-2025-52352
**Aikaan IoT management platform v3.25.0325-5-g2e9c59796 provides a configuration to disable user sign-up in distributed deployments by hid...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-21)

> Aikaan IoT management platform v3.25.0325-5-g2e9c59796 provides a configuration to disable user sign-up in distributed deployments by hiding the sign-up option on the login page UI. However, the sign-up API endpoint remains publicly accessible and functional, allowing unauthentic…

### CVE-2025-53795
**microsoft pc_manager privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft pc_manager
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-25T18:37:39.303
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-21)

> Improper authorization in Microsoft PC Manager allows an unauthorized attacker to elevate privileges over a network.

### CVE-2025-57761
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-22T21:13:42.327
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-21)

> WeGIA is a Web manager for charitable institutions. Prior to 3.4.10, there is a SQL Injection vulnerability in the /html/funcionario/dependente_remover.php endpoint, specifically in the id_funcionario parameter. This vulnerability allows attackers to execute arbitrary SQL command…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-21*
