# Daily Threat Intelligence — June 27, 2025

**Digest window (UTC):** 2025-06-27
**Generated:** 2026-06-02T07:32:57Z

## Threat brief

Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 14% → 26% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 14% → 26% · rising (+11%)).
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

### CVE-2001-0002
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 81
- **EPSS 14.5% (2025-03-30) → 25.6% (2025-06-27), Δ +11.1%**

> Internet Explorer 5.5 and earlier allows remote attackers to obtain the physical location of cached content and open the content in the Local Computer Zone, then use compiled HTML help (.chm) files to execute arbitrary programs.

### CVE-2025-53091
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-08T14:48:01.653
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-27)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. A Time-Based Blind SQL Injection vulnerability was discovered in version 3.3.3 the almox parameter of the `/controle/getProdutosPorAlmox.php` endpoint. This issue allows any u…

### CVE-2025-52207
**PBXCoreREST/Controllers/Files/PostController.php in MikoPBX through 2024.1.114 allows uploading a PHP script to an arbitrary directory.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-23
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-27)

> PBXCoreREST/Controllers/Files/PostController.php in MikoPBX through 2024.1.114 allows uploading a PHP script to an arbitrary directory.

### CVE-2024-11739
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Case Informatics Case ERP allows SQ...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-27)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Case Informatics Case ERP allows SQL Injection.This issue affects Case ERP: before V2.0.1.

### CVE-2024-12143
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mobilteg Mobile Informatics Mikro H...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T15:16:26.653
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-27)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mobilteg Mobile Informatics Mikro Hand Terminal - MikroDB allows SQL Injection.

This issue affects Mikro Hand Terminal - MikroDB. 

NOTE: The vendor did not inform about the com…

### CVE-2024-12150
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Eron Software Wowwo CRM allows Blin...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T15:16:26.997
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-27)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Eron Software Wowwo CRM allows Blind SQL Injection.

This issue affects Wowwo CRM. 

NOTE: The vendor did not inform about the completion of the fixing process within the specifi…

### CVE-2024-12364
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mavi Yeşil Software Guest Tracking...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T15:16:27.100
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-27)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mavi Yeşil Software Guest Tracking Software allows SQL Injection.

This issue affects Guest Tracking Software. 

NOTE: The vendor did not inform about the completion of the fixin…

### CVE-2025-52834
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in favethemes Homey homey allows SQL I...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:15.720
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-27)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in favethemes Homey homey allows SQL Injection.This issue affects Homey: from n/a through <= 2.4.7.

### CVE-2025-5310
**Dover Fueling Solutions ProGauge MagLink LX Consoles expose an undocumented and unauthenticated target communication framework (TCF) inte...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-27)

> Dover Fueling Solutions ProGauge MagLink LX Consoles expose an undocumented and unauthenticated target communication framework (TCF) interface on a specific port. Files can be created, deleted, or modified, potentially leading to remote code execution.

### CVE-2025-53260
**Unrestricted Upload of File with Dangerous Type vulnerability in getredhawkstudio File Manager Plugin For Wordpress file-manager-plugin-f...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:22.680
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-27)

> Unrestricted Upload of File with Dangerous Type vulnerability in getredhawkstudio File Manager Plugin For Wordpress file-manager-plugin-for-wordpress allows Upload a Web Shell to a Web Server.This issue affects File Manager Plugin For Wordpress: from n/a through <= 7.5.

### CVE-2025-53314
**Cross-Site Request Forgery (CSRF) vulnerability in sh1zen WP Optimizer wp-optimizer allows SQL Injection.This issue affects WP Optimizer:...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:28.673
- **CWE:** CWE-352
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-06-27)

> Cross-Site Request Forgery (CSRF) vulnerability in sh1zen WP Optimizer wp-optimizer allows SQL Injection.This issue affects WP Optimizer: from n/a through <= 2.5.0.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-27*
