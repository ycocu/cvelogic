# Daily Threat Intelligence — August 05, 2025

**Digest window (UTC):** 2025-08-05
**Generated:** 2026-06-02T07:33:11Z

## Threat brief

D-Link DNR-322L: 3 CVEs added to CISA KEV today. · Santesoft Sante Pacs Server — exploitation likelihood rose sharply (EPSS 4.8% → 25% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- D-Link DNR-322L: 3 CVEs added to CISA KEV today.
- Santesoft Sante Pacs Server — exploitation likelihood rose sharply (EPSS 4.8% → 25% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2020-25079
**D-Link DCS-2530L and DCS-2670L Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** dlink dcs-4703e_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T22:02:03.050
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2025-08-05

> An issue was discovered on D-Link DCS-2530L before 1.06.01 Hotfix and DCS-2670L through 2.02 devices. cgi-bin/ddns_enc.cgi allows authenticated command injection.

### CVE-2022-2272
**santesoft sante_pacs_server SQL injection**
- **Signals:** EPSS
- **Asset:** santesoft sante_pacs_server
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:00:39.787
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 4.8% (2025-08-04) → 24.7% (2025-08-05), Δ +19.8%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Sante PACS Server 3.0.4. Authentication is not required to exploit this vulnerability. The specific flaw exists within the processing of calls to the login endpoint. When parsing the …

### CVE-2013-10069
**dlink dir-300_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink dir-600_firmware
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T18:37:48.680
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-05)

> The web interface of multiple D-Link routers, including DIR-600 rev B (≤2.14b01) and DIR-300 rev B (≤2.13), contains an unauthenticated OS command injection vulnerability in command.php, which improperly handles the cmd POST parameter. A remote attacker can exploit this flaw with…

### CVE-2012-10030
**freefloat freefloat_ftp_server**
- **Signals:** CVSS
- **Asset:** freefloat freefloat_ftp_server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-03T14:58:01.787
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-05)

> FreeFloat FTP Server contains multiple critical design flaws that allow unauthenticated remote attackers to upload arbitrary files to sensitive system directories. The server accepts empty credentials, defaults user access to the root of the C:\ drive, and imposes no restrictions…

### CVE-2012-10033
**Narcissus is vulnerable to remote code execution via improper input handling in its image configuration workflow.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-05)

> Narcissus is vulnerable to remote code execution via improper input handling in its image configuration workflow. Specifically, the backend.php script fails to sanitize the release parameter before passing it to the configure_image() function. This function invokes PHP’s passthru…

### CVE-2012-10035
**Turbo FTP Server versions 1.30.823 and 1.30.826 contain a buffer overflow vulnerability in the handling of the PORT command.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-05)

> Turbo FTP Server versions 1.30.823 and 1.30.826 contain a buffer overflow vulnerability in the handling of the PORT command. By sending a specially crafted payload, an unauthenticated remote attacker can overwrite memory structures and execute arbitrary code with SYSTEM privilege…

### CVE-2013-10064
**A stack-based buffer overflow vulnerability exists in ActFax Server version 5.01.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-05)

> A stack-based buffer overflow vulnerability exists in ActFax Server version 5.01. The server's RAW protocol interface fails to safely process user-supplied data in @F506 fax header fields due to insecure usage of strcpy. Remote attackers can exploit this vulnerability by sending …

### CVE-2013-10066
**An unauthenticated arbitrary file upload vulnerability exists in Kordil EDMS v2.2.60rc3.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-05)

> An unauthenticated arbitrary file upload vulnerability exists in Kordil EDMS v2.2.60rc3. The application exposes an upload endpoint (users_add.php) that allows attackers to upload files to the /userpictures/ directory without authentication. This flaw enables remote code executio…

### CVE-2013-10067
**Glossword versions 1.8.8 through 1.8.12 contain an authenticated arbitrary file upload vulnerability.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-05)

> Glossword versions 1.8.8 through 1.8.12 contain an authenticated arbitrary file upload vulnerability. When deployed as a standalone application, the administrative interface (gw_admin.php) allows users with administrator privileges to upload files to the gw_temp/a/ directory. Due…

### CVE-2013-10068
**Foxit Reader versions through 5.4.5.0114, including the bundled Foxit Reader Plugin 2.2.1.530, contains a stack-based buffer overflow vul...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T00:16:42.597
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-05)

> Foxit Reader versions through 5.4.5.0114, including the bundled Foxit Reader Plugin 2.2.1.530, contains a stack-based buffer overflow vulnerability in the npFoxitReaderPlugin.dll module. When a PDF file is loaded from a remote host, an overly long query string in the URL can over…

### CVE-2013-10070
**PHP-Charts v1.0 contains a PHP code execution vulnerability in wizard/url.php, where user-supplied GET parameter names are passed directl...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-95
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-05)

> PHP-Charts v1.0 contains a PHP code execution vulnerability in wizard/url.php, where user-supplied GET parameter names are passed directly to eval() without sanitization. A remote attacker can exploit this flaw by crafting a request that injects arbitrary PHP code, resulting in c…

### CVE-2014-125113
**An unrestricted file upload vulnerability exists in Dell (acquired by Quest) KACE K1000 System Management Appliance version 5.0 - 5.3, 5....**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-05)

> An unrestricted file upload vulnerability exists in Dell (acquired by Quest) KACE K1000 System Management Appliance version 5.0 - 5.3, 5.4 prior to 5.4.76849, and 5.5 prior to 5.5.90547 in the download_agent.php endpoint. An attacker can upload arbitrary PHP files to a temporary …

### CVE-2020-25078
**D-Link DCS-2530L and DCS-2670L Devices Unspecified Vulnerability**
- **Signals:** KEV
- **Asset:** dlink dcs-4603_firmware
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T22:02:08.727
- **Risk score:** 88
- **KEV:** added 2025-08-05

> An issue was discovered on D-Link DCS-2530L before 1.06.01 Hotfix and DCS-2670L through 2.02 devices. The unauthenticated /config/getuser endpoint allows for remote administrator password disclosure.

### CVE-2022-40799
**D-Link DNR-322L Download of Code Without Integrity Check Vulnerability**
- **Signals:** KEV
- **Asset:** dlink dnr-322l_firmware
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T18:13:46.230
- **CWE:** CWE-494
- **CWE:** CWE-494
- **Risk score:** 88
- **KEV:** added 2025-08-05

> Data Integrity Failure in 'Backup Config' in D-Link DNR-322L <= 2.60B15 allows an authenticated attacker to execute OS level commands on the device.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-05*
