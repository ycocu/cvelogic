# Daily Threat Intelligence — January 08, 2026

**Digest window (UTC):** 2026-01-08
**Generated:** 2026-06-02T07:34:09Z

## Threat brief

Qualcomm Eudora — exploitation likelihood rose sharply (EPSS 8.0% → 21% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Qualcomm Eudora — exploitation likelihood rose sharply (EPSS 8.0% → 21% · rising (+13%)).
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

### CVE-2004-2005
**qualcomm eudora Buffer Overflow**
- **Signals:** EPSS
- **Asset:** qualcomm eudora
- **Attack:** Buffer Overflow
- **CVSS max:** 5.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 79
- **EPSS 8.0% (2025-03-30) → 20.8% (2026-01-08), Δ +12.8%**

> Buffer overflow in Eudora for Windows 5.2.1, 6.0.3, and 6.1 allows remote attackers to execute arbitrary code via an e-mail with (1) a link to a long URL to the C drive or (2) a long attachment name.

### CVE-1999-1557
**ipswitch imail Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ipswitch imail
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 11.6% (2025-04-04) → 23.7% (2026-01-08), Δ +12.0%**

> Buffer overflow in the login functions in IMAP server (imapd) in Ipswitch IMail 5.0 and earlier allows remote attackers to cause a denial of service and possibly execute arbitrary code via (1) a long user name or (2) a long password.

### CVE-2025-61246
**indieka900 online_shopping_system SQL Injection**
- **Signals:** CVSS
- **Asset:** indieka900 online_shopping_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-16T21:31:24.953
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-08)

> indieka900 online-shopping-system-php 1.0 is vulnerable to SQL Injection in master/review_action.php via the proId parameter.

### CVE-2003-0755
**gtkftpd gtkftp Buffer Overflow**
- **Signals:** EPSS
- **Asset:** gtkftpd gtkftp
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 83
- **EPSS 2.4% (2025-10-17) → 12.6% (2026-01-08), Δ +10.3%**

> Buffer overflow in sys_cmd.c for gtkftpd 1.0.4 and earlier allows remote attackers to execute arbitrary code by creating long directory names and listing them with a LIST command.

### CVE-2025-59470
**veeam veeam_backup_\&_replication RCE**
- **Signals:** CVSS
- **Asset:** veeam veeam_backup_\&_replication
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T20:59:08.753
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-01-08)

> This vulnerability allows a Backup Operator to perform remote code execution (RCE) as the postgres user by sending a malicious interval or order parameter.

### CVE-2025-61546
**edubusinesssolutions print_shop_pro_webdesk**
- **Signals:** CVSS
- **Asset:** edubusinesssolutions print_shop_pro_webdesk
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-02-10T18:16:19.737
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-08)

> There is an issue on the /PSP/appNET/Store/CartV12.aspx/GetUnitPrice endpoint in edu Business Solutions Print Shop Pro WebDesk version 18.34 (fixed in 19.69) that enables remote attacker to create financial discrepancies by purchasing items with a negative quantity. This vulnerab…

### CVE-2025-61548
**edubusinesssolutions print_shop_pro_webdesk SQL Injection**
- **Signals:** CVSS
- **Asset:** edubusinesssolutions print_shop_pro_webdesk
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-10T18:16:20.083
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-08)

> SQL Injection is present on the hfInventoryDistFormID parameter in the /PSP/appNET/Store/CartV12.aspx/GetUnitPrice endpoint in edu Business Solutions Print Shop Pro WebDesk version 18.34 (fixed in 19.69). Unsanitized user input is incorporated directly into SQL queries without pr…

### CVE-2025-66913
**jeecg jimureport RCE**
- **Signals:** CVSS
- **Asset:** jeecg jimureport
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T01:06:25.553
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-08)

> JimuReport thru version 2.1.3 is vulnerable to remote code execution when processing user-controlled H2 JDBC URLs. The application passes the attacker-supplied JDBC URL directly to the H2 driver, allowing the use of certain directives to execute arbitrary Java code. A different v…

### CVE-2025-66916
**dromara ruoyi-vue-plus**
- **Signals:** CVSS
- **Asset:** dromara ruoyi-vue-plus
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T01:05:34.193
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-08)

> The snailjob component in RuoYi-Vue-Plus versions 5.5.1 and earlier, interface /snail-job/workflow/check-node-expression can execute QLExpress expressions, but it does not filter user input, allowing attackers to use the File class to perform arbitrary file reading and writing.

### CVE-2025-67325
**webkul qloapps RCE**
- **Signals:** CVSS
- **Asset:** webkul qloapps
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T01:06:56.767
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-08)

> Unrestricted file upload in the hotel review feature in QloApps versions 1.7.0 and earlier allows remote unauthenticated attackers to achieve remote code execution.

### CVE-2025-68715
**pandawireless pwru01_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** pandawireless pwru01_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T01:04:35.430
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-08)

> An issue was discovered in Panda Wireless PWRU0 devices with firmware 2.2.9 that exposes multiple HTTP endpoints (/goform/setWan, /goform/setLan, /goform/wirelessBasic) that do not enforce authentication. A remote unauthenticated attacker can modify WAN, LAN, and wireless setting…

### CVE-2025-68717
**kaysus ks-wr3600_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** kaysus ks-wr3600_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T16:35:48.640
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-08)

> KAYSUS KS-WR3600 routers with firmware 1.0.5.9.1 allow authentication bypass during session validation. If any user is logged in, endpoints such as /cgi-bin/system-tool accept unauthenticated requests with empty or invalid session values. This design flaw lets attackers piggyback…

### CVE-2026-22234
**opexustech ecase_portal**
- **Signals:** CVSS
- **Asset:** opexustech ecase_portal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T14:05:09.970
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-08)

> OPEXUS eCasePortal before version 9.0.45.0 allows an unauthenticated attacker to navigate to the 'Attachments.aspx' endpoint, iterate through predictable values of 'formid', and download or delete all user-uploaded files, or upload new files.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-08*
