# Daily Threat Intelligence — August 28, 2025

**Digest window (UTC):** 2025-08-28
**Generated:** 2026-06-02T07:33:19Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-57819
**Sangoma FreePBX Authentication Bypass Vulnerability**
- **Signals:** CVSS
- **Asset:** sangoma freepbx
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:58:40.963
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-28)

> FreePBX is an open-source web-based graphical user interface. FreePBX 15, 16, and 17 endpoints are vulnerable due to insufficiently sanitized user-supplied data allowing unauthenticated access to FreePBX Administrator leading to arbitrary database manipulation and remote code exe…

### CVE-2025-49387
**Unrestricted Upload of File with Dangerous Type vulnerability in add-ons.org Drag and Drop File Upload for Elementor Forms drag-and-drop-...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:34.733
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-28)

> Unrestricted Upload of File with Dangerous Type vulnerability in add-ons.org Drag and Drop File Upload for Elementor Forms drag-and-drop-file-upload-for-elementor-forms allows Upload a Web Shell to a Web Server.This issue affects Drag and Drop File Upload for Elementor Forms: fro…

### CVE-2025-58048
**Paymenter is a free and open-source webshop solution for hostings.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-08-28)

> Paymenter is a free and open-source webshop solution for hostings. Prior to version 1.2.11, the ticket attachments functionality in Paymenter allows a malicious authenticated user to upload arbitrary files. This could result in sensitive data extraction from the database, credent…

### CVE-2025-49388
**Incorrect Privilege Assignment vulnerability in kamleshyadav Miraculous Core Plugin miraculouscore allows Privilege Escalation.This issue...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:34.847
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-28)

> Incorrect Privilege Assignment vulnerability in kamleshyadav Miraculous Core Plugin miraculouscore allows Privilege Escalation.This issue affects Miraculous Core Plugin: from n/a through <= 2.0.7.

### CVE-2025-52761
**Deserialization of Untrusted Data vulnerability in manfcarlo WP Funnel Manager wp-funnel-manager allows Object Injection.This issue affec...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:07.780
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-28)

> Deserialization of Untrusted Data vulnerability in manfcarlo WP Funnel Manager wp-funnel-manager allows Object Injection.This issue affects WP Funnel Manager: from n/a through <= 1.4.0.

### CVE-2025-54720
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in SteelThemes Nest Addons nest-addons...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:53.083
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-28)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in SteelThemes Nest Addons nest-addons allows SQL Injection.This issue affects Nest Addons: from n/a through <= 1.6.3.

### CVE-2025-54725
**Authentication Bypass Using an Alternate Path or Channel vulnerability in uxper Golo golo allows Authentication Abuse.This issue affects...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:53.460
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-28)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in uxper Golo golo allows Authentication Abuse.This issue affects Golo: from n/a through <= 1.7.0.

### CVE-2025-54738
**Authentication Bypass Using an Alternate Path or Channel vulnerability in NooTheme Jobmonster noo-jobmonster allows Authentication Abuse....**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:54.880
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-28)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in NooTheme Jobmonster noo-jobmonster allows Authentication Abuse.This issue affects Jobmonster: from n/a through <= 4.7.9.

### CVE-2025-55583
**dlink dir-868l_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink dir-868l_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T18:41:54.723
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-28)

> D-Link DIR-868L B1 router firmware version FW2.05WWB02 contains an unauthenticated OS command injection vulnerability in the fileaccess.cgi component. The endpoint /dws/api/UploadFile accepts a pre_api_arg parameter that is passed directly to system-level shell execution function…

### CVE-2025-58059
**Valtimo is a platform for Business Process Automation.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-28)

> Valtimo is a platform for Business Process Automation. In versions before 12.16.0.RELEASE, and from 13.0.0.RELEASE to before 13.1.2.RELEASE, any admin that can create or modify and execute process-definitions could gain access to sensitive data or resources. This includes but is …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-28*
