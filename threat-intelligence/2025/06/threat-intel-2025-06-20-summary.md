# Daily Threat Intelligence — June 20, 2025

**Digest window (UTC):** 2025-06-20
**Generated:** 2026-06-02T07:32:55Z

## Threat brief

Fortinet Fortios: public exploit or PoC linked · Sap Netweaver — exploitation likelihood rose sharply (EPSS 12% → 27% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet Fortios: public exploit or PoC linked
- Sap Netweaver — exploitation likelihood rose sharply (EPSS 12% → 27% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2024-50562
**fortinet fortios**
- **Signals:** EXP
- **Asset:** fortinet fortisase
- **CVSS max:** 4.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-25T15:25:23.913
- **CWE:** CWE-613
- **Risk score:** 78
- **EXP:** ref published 2025-06-20

> An Insufficient Session Expiration vulnerability [CWE-613] in FortiOS SSL-VPN version 7.6.0, version 7.4.6 and below, version 7.2.10 and below, 7.0 all versions, 6.4 all versions may allow an attacker in possession of a cookie used to log in the SSL-VPN portal to log in again, al…

### CVE-2025-47957
**microsoft 365_apps**
- **Signals:** EXP
- **Asset:** microsoft 365_apps
- **CVSS max:** 8.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T13:33:34.613
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-06-20

> Use after free in Microsoft Office Word allows an unauthorized attacker to execute code locally.

### CVE-2015-7241
**sap netweaver XXE**
- **Signals:** EPSS
- **Asset:** sap netweaver
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-611
- **Risk score:** 86
- **EPSS 11.5% (2025-03-30) → 27.4% (2025-06-20), Δ +15.9%**

> XML External Entity (XXE) vulnerability in SAP Netweaver before 7.01.

### CVE-2025-1974
**A security issue was discovered in Kubernetes where under certain conditions, an unauthenticated attacker with access to the pod network...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-653
- **Risk score:** 78
- **EXP:** ref published 2025-06-20

> A security issue was discovered in Kubernetes where under certain conditions, an unauthenticated attacker with access to the pod network can achieve arbitrary code execution in the context of the ingress-nginx controller. This can lead to disclosure of Secrets accessible to the c…

### CVE-2025-25034
**A PHP object injection vulnerability exists in SugarCRM versions prior to 6.5.24, 6.7.13, 7.5.2.5, 7.6.2.2, and 7.7.1.0 due to improper v...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-20)

> A PHP object injection vulnerability exists in SugarCRM versions prior to 6.5.24, 6.7.13, 7.5.2.5, 7.6.2.2, and 7.7.1.0 due to improper validation of PHP serialized input in the SugarRestSerialize.php script. The vulnerable code fails to sanitize the rest_data parameter before pa…

### CVE-2025-25037
**An information disclosure vulnerability exists in Aquatronica Controller System firmware versions <= 5.1.6 and web interface versions <=...**
- **Signals:** CVSS
- **Attack:** Info Disclosure
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-20)

> An information disclosure vulnerability exists in Aquatronica Controller System firmware versions <= 5.1.6 and web interface versions <= 2.0. The tcp.php endpoint fails to restrict unauthenticated access, allowing remote attackers to issue crafted POST requests and retrieve sensi…

### CVE-2025-25038
**minidvblinux minidvblinux Command Injection**
- **Signals:** CVSS
- **Asset:** minidvblinux minidvblinux
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T17:46:41.027
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-20)

> An OS command injection vulnerability exists in MiniDVBLinux version 5.4 and earlier. The system’s web-based management interface fails to properly sanitize user-supplied input before passing it to operating system commands. A remote unauthenticated attacker can exploit this vuln…

### CVE-2025-34022
**A path traversal vulnerability exists in multiple models of Selea Targa IP OCR-ANPR cameras, including iZero, Targa 512, Targa 504, Targa...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-20)

> A path traversal vulnerability exists in multiple models of Selea Targa IP OCR-ANPR cameras, including iZero, Targa 512, Targa 504, Targa Semplice, Targa 704 TKM, Targa 805, Targa 710 INOX, Targa 750, and Targa 704 ILB. The /common/get_file.php script in the “Download Archive in …

### CVE-2025-34024
**edimax ew-7438rpn_mini_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** edimax ew-7438rpn_mini_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2025-11-20T22:15:55.127
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-20)

> An OS command injection vulnerability exists in the Edimax EW-7438RPn firmware version 1.13 and prior via the mp.asp form handler. The /goform/mp endpoint improperly handles user-supplied input to the command parameter. An authenticated attacker can inject shell commands using sh…

### CVE-2025-34029
**edimax ew-7438rpn_mini_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** edimax ew-7438rpn_mini_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2025-11-20T22:15:55.260
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-20)

> An OS command injection vulnerability exists in the Edimax EW-7438RPn Mini firmware version 1.13 and prior via the syscmd.asp form handler. The /goform/formSysCmd endpoint exposes a system command interface through the sysCmd parameter. A remote authenticated attacker can submit …

### CVE-2025-34030
**An OS command injection vulnerability exists in sar2html version 3.2.2 and prior via the plot parameter in index.php.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-20)

> An OS command injection vulnerability exists in sar2html version 3.2.2 and prior via the plot parameter in index.php. The application fails to sanitize user-supplied input before using it in a system-level context. Remote, unauthenticated attackers can inject shell commands by ap…

### CVE-2025-44635
**There are multiple unauthorized remote command execution vulnerabilities in the H3C ER2200G2, ERG2-450W, ERG2-1200W, ERG2-1350W, NR1200W...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-20)

> There are multiple unauthorized remote command execution vulnerabilities in the H3C ER2200G2, ERG2-450W, ERG2-1200W, ERG2-1350W, NR1200W series routers before ERG2AW-MNW100-R1117; H3C ER3100G2, ER3200G2, ER3260G2, ER5100G2, ER5200G2, ER6300G2, ER8300G2, ER8300G2-X series routers …

### CVE-2025-45890
**xxyopen novel-plus Directory Traversal**
- **Signals:** CVSS
- **Asset:** xxyopen novel-plus
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-26T14:25:56.920
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-20)

> Directory Traversal vulnerability in novel plus before v.5.1.0 allows a remote attacker to execute arbitrary code via the filePath parameter

### CVE-2025-49132
**Pterodactyl is a free, open-source game server management panel.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-20)

> Pterodactyl is a free, open-source game server management panel. Prior to version 1.11.11, using the /locales/locale.json with the locale and namespace query parameters, a malicious actor is able to execute arbitrary code without being authenticated. With the ability to execute a…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-20*
