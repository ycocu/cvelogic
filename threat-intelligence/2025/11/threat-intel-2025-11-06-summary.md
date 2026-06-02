# Daily Threat Intelligence — November 06, 2025

**Digest window (UTC):** 2025-11-06
**Generated:** 2026-06-02T07:33:44Z

## Threat brief

Cups — exploitation likelihood rose sharply (EPSS 44% → 59% · rising (+14%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cups — exploitation likelihood rose sharply (EPSS 44% → 59% · rising (+14%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2015-1159
**cups cups XSS**
- **Signals:** EPSS
- **Asset:** cups cups
- **Attack:** XSS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-79
- **Risk score:** 77
- **EPSS 44.4% (2025-10-02) → 58.8% (2025-11-06), Δ +14.4%**

> Cross-site scripting (XSS) vulnerability in the cgi_puts function in cgi-bin/template.c in the template engine in CUPS before 2.0.3 allows remote attackers to inject arbitrary web script or HTML via the QUERY parameter to help/.

### CVE-2025-6327
**Unrestricted Upload of File with Dangerous Type vulnerability in KingAddons.com King Addons for Elementor king-addons allows Upload a Web...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-06)

> Unrestricted Upload of File with Dangerous Type vulnerability in KingAddons.com King Addons for Elementor king-addons allows Upload a Web Shell to a Web Server.This issue affects King Addons for Elementor: from n/a through <= 51.1.36.

### CVE-2025-27918
**anydesk anydesk Buffer Overflow**
- **Signals:** CVSS
- **Asset:** anydesk anydesk
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-12-08T17:16:13.713
- **CWE:** CWE-190
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-06)

> An issue was discovered in AnyDesk for Windows before 9.0.5, AnyDesk for macOS before 9.0.1, AnyDesk for Linux before 7.0.0, AnyDesk for iOS before 7.1.2, and AnyDesk for Android before 8.0.0. It has an integer overflow and resultant heap-based buffer overflow via a UDP packet du…

### CVE-2022-50589
**salesagility suitecrm SQL Injection**
- **Signals:** CVSS
- **Asset:** salesagility suitecrm
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T19:07:23.373
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-06)

> SuiteCRM versions prior to 7.12.6 contain a SQL injection vulnerability within the processing of the ‘uid’ parameter within the ‘export’ functionality. Successful exploitation allows remote unauthenticated attackers to ultimately execute arbitrary code.

### CVE-2022-50592
**advantech iview RCE**
- **Signals:** CVSS
- **Asset:** advantech iview
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T18:54:19.717
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-06)

> Advantech iView versions prior to v5.7.04 build 6425 contain a vulnerability within the SNMP management tool that allows for remote attackers to bypass authentication checks and reach a SQL injection vulnerability within the ‘getInventoryReportData’ parameter to the ‘NetworkServl…

### CVE-2022-50593
**advantech iview RCE**
- **Signals:** CVSS
- **Asset:** advantech iview
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-08T16:12:55.903
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-06)

> Advantech iView versions prior to v5.7.04 build 6425 contain a vulnerability within the SNMP management tool that allows for remote attackers to bypass authentication checks and reach a SQL injection vulnerability within the ‘search_term’ parameter to the ‘NetworkServlet’ endpoin…

### CVE-2022-50595
**advantech iview RCE**
- **Signals:** CVSS
- **Asset:** advantech iview
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T18:14:17.173
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-06)

> Advantech iView versions prior to v5.7.04 build 6425 contain a vulnerability within the SNMP management tool that allows for remote attackers to bypass authentication checks and reach a SQL injection vulnerability within the ‘ztp_search_value’ parameter to the ‘NetworkServlet’ en…

### CVE-2022-50596
**dlink dir-1260_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink dir-1260_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-28T17:00:26.797
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-06)

> D-Link DIR-1260 Wi-Fi router firmware versions up to and including v1.20B05 contain a command injection vulnerability within the web management interface that allows for unauthenticated attackers to execute arbitrary commands on the device with root privileges. The flaw specifica…

### CVE-2025-12487
**oobabooga text-generation-webui trust_remote_code Reliance on Untrusted Inputs Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-807
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-06)

> oobabooga text-generation-webui trust_remote_code Reliance on Untrusted Inputs Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of oobabooga text-generation-webui. Authentication is not required to…

### CVE-2025-12488
**oobabooga text-generation-webui trust_remote_code Reliance on Untrusted Inputs Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-807
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-06)

> oobabooga text-generation-webui trust_remote_code Reliance on Untrusted Inputs Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of oobabooga text-generation-webui. Authentication is not required to…

### CVE-2025-6325
**Incorrect Privilege Assignment vulnerability in KingAddons.com King Addons for Elementor king-addons allows Privilege Escalation.This iss...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-06)

> Incorrect Privilege Assignment vulnerability in KingAddons.com King Addons for Elementor king-addons allows Privilege Escalation.This issue affects King Addons for Elementor: from n/a through <= 51.1.36.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-06*
