# Daily Threat Intelligence — August 08, 2025

**Digest window (UTC):** 2025-08-08
**Generated:** 2026-06-02T07:33:12Z

## Threat brief

Netgear Prosafe Firmware — exploitation likelihood rose sharply (EPSS 26% → 38% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Netgear Prosafe Firmware — exploitation likelihood rose sharply (EPSS 26% → 38% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2013-4776
**netgear prosafe_firmware DoS**
- **Signals:** EPSS
- **Asset:** netgear prosafe_firmware
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 82
- **EPSS 25.8% (2025-08-04) → 38.0% (2025-08-08), Δ +12.2%**

> NETGEAR ProSafe GS724Tv3 and GS716Tv2 with firmware 5.4.1.13 and earlier, GS748Tv4 5.4.1.14, and GS510TP 5.0.4.4 allows remote attackers to cause a denial of service (reboot or crash) via a crafted HTTP request to filesystem/.

### CVE-2005-1476
**mozilla firefox RCE**
- **Signals:** EPSS
- **Asset:** mozilla firefox
- **Attack:** RCE
- **CVSS max:** 5.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 38.1% (2025-03-30) → 49.8% (2025-08-08), Δ +11.6%**

> Firefox 1.0.3 allows remote attackers to execute arbitrary Javascript in other domains by using an IFRAME and causing the browser to navigate to a previous javascript: URL, which can lead to arbitrary code execution when combined with CVE-2005-1477.

### CVE-2012-10044
**MobileCartly version 1.0 contains an arbitrary file creation vulnerability in the savepage.php script.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-08)

> MobileCartly version 1.0 contains an arbitrary file creation vulnerability in the savepage.php script. The application fails to perform authentication or authorization checks before invoking file_put_contents() on attacker-controlled input. An unauthenticated attacker can exploit…

### CVE-2012-10041
**WAN Emulator v2.3 contains two unauthenticated command execution vulnerabilities.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> WAN Emulator v2.3 contains two unauthenticated command execution vulnerabilities. The result.php script calls shell_exec() with unsanitized input from the pc POST parameter, allowing remote attackers to execute arbitrary commands as the www-data user. The system also includes a S…

### CVE-2012-10043
**A stack-based buffer overflow vulnerability exists in ActFax Server version 4.32, specifically in the "Import Users from File" functional...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> A stack-based buffer overflow vulnerability exists in ActFax Server version 4.32, specifically in the "Import Users from File" functionality of the client interface. The application fails to properly validate the length of tab-delimited fields in .exp files, leading to unsafe usa…

### CVE-2012-10045
**XODA version 0.4.5 contains an unauthenticated file upload vulnerability that allows remote attackers to execute arbitrary PHP code on th...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> XODA version 0.4.5 contains an unauthenticated file upload vulnerability that allows remote attackers to execute arbitrary PHP code on the server. The flaw resides in the upload functionality, which fails to properly validate or restrict uploaded file types. By crafting a multipa…

### CVE-2012-10046
**The E-Mail Security Virtual Appliance (ESVA) (tested on version ESVA_2057) contains an unauthenticated command injection vulnerability in...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> The E-Mail Security Virtual Appliance (ESVA) (tested on version ESVA_2057) contains an unauthenticated command injection vulnerability in the learn-msg.cgi script. The CGI handler fails to sanitize user-supplied input passed via the id parameter, allowing attackers to inject arbi…

### CVE-2012-10047
**Cyclope Employee Surveillance Solution versions 6.x are vulnerable to a SQL injection flaw in its login mechanism.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:21.953
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-08)

> Cyclope Employee Surveillance Solution versions 6.x are vulnerable to a SQL injection flaw in its login mechanism. The username parameter in the auth-login POST request is not properly sanitized, allowing attackers to inject arbitrary SQL statements. This can be leveraged to writ…

### CVE-2012-10049
**WebPageTest version 2.6 and earlier contains an arbitrary file upload vulnerability in the resultimage.php script.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> WebPageTest version 2.6 and earlier contains an arbitrary file upload vulnerability in the resultimage.php script. The application fails to validate or sanitize user-supplied input before saving uploaded files to a publicly accessible directory. This flaw allows remote attackers …

### CVE-2012-10050
**CuteFlow version 2.11.2 and earlier contains an arbitrary file upload vulnerability in the restart_circulation_values_write.php script.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> CuteFlow version 2.11.2 and earlier contains an arbitrary file upload vulnerability in the restart_circulation_values_write.php script. The application fails to validate or restrict uploaded file types, allowing unauthenticated attackers to upload arbitrary PHP files to the uploa…

### CVE-2012-10052
**EGallery version 1.2 contains an unauthenticated arbitrary file upload vulnerability in the uploadify.php script.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> EGallery version 1.2 contains an unauthenticated arbitrary file upload vulnerability in the uploadify.php script. The application fails to validate file types or enforce authentication, allowing remote attackers to upload malicious PHP files directly into the web-accessible egall…

### CVE-2012-10053
**Simple Web Server 2.2 rc2 contains a stack-based buffer overflow vulnerability in its handling of the Connection HTTP header.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-08)

> Simple Web Server 2.2 rc2 contains a stack-based buffer overflow vulnerability in its handling of the Connection HTTP header. When a remote attacker sends an overly long string in this header, the server uses vsprintf() without proper bounds checking, leading to a buffer overflow…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-08*
