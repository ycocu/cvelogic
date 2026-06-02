# Daily Threat Intelligence — February 18, 2026

**Digest window (UTC):** 2026-02-18
**Generated:** 2026-06-02T07:34:27Z

## Threat brief

Dell RecoverPoint For Virtual Machines (RP4VMs) added to CISA KEV — confirmed in-the-wild exploitation. · Dlink Dir-822\+ Firmware — exploitation likelihood rose sharply (EPSS 5.4% → 54% · rising (+48%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Dell RecoverPoint For Virtual Machines (RP4VMs) added to CISA KEV — confirmed in-the-wild exploitation.
- Dlink Dir-822\+ Firmware — exploitation likelihood rose sharply (EPSS 5.4% → 54% · rising (+48%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2021-22175
**GitLab Server-Side Request Forgery (SSRF) Vulnerability**
- **Signals:** KEV
- **Asset:** gitlab gitlab
- **Attack:** SSRF
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T02:00:02.830
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2026-02-18

> When requests to the internal network for webhooks are enabled, a server-side request forgery vulnerability in GitLab affecting all versions starting from 10.5 was possible to exploit for an unauthenticated attacker even on a GitLab instance where registration is disabled

### CVE-2024-33344
**dlink dir-822\+_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** dlink dir-822\+_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-21T12:51:29.240
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 5.4% (2025-11-21) → 53.7% (2026-02-18), Δ +48.3%**

> D-Link DIR-822+ V1.0.5 was found to contain a command injection in ftext function of upload_firmware.cgi, which allows remote attackers to execute arbitrary commands via shell.

### CVE-2025-14009
**nltk nltk**
- **Signals:** CVSS
- **Asset:** nltk nltk
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T21:23:46.287
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-18)

> A critical vulnerability exists in the NLTK downloader component of nltk/nltk, affecting all versions. The _unzip_iter function in nltk/downloader.py uses zipfile.extractall() without performing path validation or security checks. This allows attackers to craft malicious zip pack…

### CVE-2012-5861
**sinapsitech esolar_duo_photovoltaic_system_monitor SQL injection**
- **Signals:** EPSS
- **Asset:** sinapsitech sinapsi_firmware
- **Attack:** SQL injection
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 80
- **EPSS 3.7% (2025-11-27) → 13.8% (2026-02-18), Δ +10.1%**

> These Sinapsi devices do not check the validity of the data before 
executing queries. By accessing the SQL table of certain pages that do 
not require authentication within the device, attackers can leak 
information from the device. This could allow the attacker to compromise
 …

### CVE-2016-3261
**microsoft internet_explorer Info Disclosure**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** Info Disclosure
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 79
- **EPSS 16.6% (2026-01-29) → 36.7% (2026-02-18), Δ +20.0%**

> Microsoft Internet Explorer 11 allows remote attackers to obtain sensitive information via a crafted web site, aka "Internet Explorer Information Disclosure Vulnerability."

### CVE-2016-3277
**microsoft edge Info Disclosure**
- **Signals:** EPSS
- **Asset:** microsoft edge
- **Attack:** Info Disclosure
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 79
- **EPSS 14.2% (2026-01-29) → 32.5% (2026-02-18), Δ +18.3%**

> Microsoft Internet Explorer 10 and 11 and Microsoft Edge allow remote attackers to obtain sensitive information via a crafted web site, aka "Microsoft Browser Information Disclosure Vulnerability."

### CVE-2019-25362
**alloksoft wmv_to_avi_mpeg_dvd_wmv_convertor Buffer Overflow**
- **Signals:** CVSS
- **Asset:** alloksoft wmv_to_avi_mpeg_dvd_wmv_convertor
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T15:17:47.687
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-18)

> WMV to AVI MPEG DVD WMV Convertor 4.6.1217 contains a buffer overflow vulnerability that allows attackers to execute arbitrary code by overwriting the license name and license code fields. Attackers can craft a malicious payload of 6000 bytes to trigger a bind shell on port 4444 …

### CVE-2019-25364
**tabslab mailcarrier Buffer Overflow**
- **Signals:** CVSS
- **Asset:** tabslab mailcarrier
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T20:41:08.130
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-18)

> MailCarrier 2.51 contains a buffer overflow vulnerability in the POP3 USER command that allows remote attackers to execute arbitrary code. Attackers can send a crafted oversized buffer to the POP3 service, overwriting memory and potentially gaining remote system access.

### CVE-2024-4325
**gradio_project gradio SSRF**
- **Signals:** EPSS
- **Asset:** gradio_project gradio
- **Attack:** SSRF
- **CVSS max:** 8.6
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T09:42:37.733
- **CWE:** CWE-918
- **Risk score:** 84
- **EPSS 47.7% (2025-11-21) → 65.1% (2026-02-18), Δ +17.4%**

> A Server-Side Request Forgery (SSRF) vulnerability exists in the gradio-app/gradio version 4.21.0, specifically within the `/queue/join` endpoint and the `save_url_to_cache` function. The vulnerability arises when the `path` value, obtained from the user and expected to be a URL,…

### CVE-2024-52765
**h3c gr-1800ax_firmware RCE**
- **Signals:** EPSS
- **Asset:** h3c gr-1800ax_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-03-13T14:15:33.100
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 3.9% (2026-02-15) → 38.6% (2026-02-18), Δ +34.7%**

> H3C GR-1800AX MiniGRW1B0V100R007 is vulnerable to remote code execution (RCE) via the aspForm parameter.

### CVE-2025-70150
**codeastro membership_management_system**
- **Signals:** CVSS
- **Asset:** codeastro membership_management_system
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T16:13:10.940
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-18)

> CodeAstro Membership Management System 1.0 contains a missing authentication vulnerability in delete_members.php that allows unauthenticated attackers to delete arbitrary member records via the id parameter.

### CVE-2025-70152
**fabian scholars_tracking_system SQL Injection**
- **Signals:** CVSS
- **Asset:** fabian scholars_tracking_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T17:54:31.543
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-18)

> code-projects Community Project Scholars Tracking System 1.0 is vulnerable to SQL Injection in the admin user management endpoints /admin/save_user.php and /admin/update_user.php. These endpoints lack authentication checks and directly concatenate user-supplied POST parameters (f…

### CVE-2026-22769
**Dell RecoverPoint for Virtual Machines (RP4VMs) Use of Hard-coded Credentials Vulnerability**
- **Signals:** KEV
- **Asset:** dell recoverpoint_for_virtual_machines
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T02:00:02.830
- **CWE:** CWE-798
- **CWE:** CWE-798
- **Risk score:** 88
- **KEV:** added 2026-02-18

> Dell RecoverPoint for Virtual Machines, versions prior to 6.0.3.1 HF1, contain a hardcoded credential vulnerability. This is considered critical as an unauthenticated remote attacker with knowledge of the hardcoded credential could potentially exploit this vulnerability leading t…

### CVE-2026-23491
**invoiceplane invoiceplane Path Traversal**
- **Signals:** CVSS
- **Asset:** invoiceplane invoiceplane
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-02-25T17:25:38.747
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-18)

> InvoicePlane is a self-hosted open source application for managing invoices, clients, and payments. A path traversal vulnerability exists in the `get_file` method of the `Guest` module's `Get` controller in InvoicePlane up to and including through 1.6.3. The vulnerability allows …

### CVE-2026-25548
**invoiceplane invoiceplane RCE**
- **Signals:** CVSS
- **Asset:** invoiceplane invoiceplane
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T18:45:32.913
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-18)

> InvoicePlane is a self-hosted open source application for managing invoices, clients, and payments. A critical Remote Code Execution (RCE) vulnerability exists in InvoicePlane 1.7.0 through a chained Local File Inclusion (LFI) and Log Poisoning attack. An authenticated administra…

### CVE-2026-27174
**mjdm majordomo RCE**
- **Signals:** CVSS
- **Asset:** mjdm majordomo
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T20:02:36.767
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-18)

> MajorDoMo (aka Major Domestic Module) allows unauthenticated remote code execution via the admin panel's PHP console feature. An include order bug in modules/panel.class.php causes execution to continue past a redirect() call that lacks an exit statement, allowing unauthenticated…

### CVE-2026-27175
**mjdm majordomo Command Injection**
- **Signals:** CVSS
- **Asset:** mjdm majordomo
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T20:02:13.103
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-18)

> MajorDoMo (aka Major Domestic Module) is vulnerable to unauthenticated OS command injection via rc/index.php. The $param variable from user input is interpolated into a command string within double quotes without sanitization via escapeshellarg(). The command is inserted into a d…

### CVE-2026-27180
**mjdm majordomo RCE**
- **Signals:** CVSS
- **Asset:** mjdm majordomo
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T19:51:21.530
- **CWE:** CWE-494
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-18)

> MajorDoMo (aka Major Domestic Module) is vulnerable to unauthenticated remote code execution through supply chain compromise via update URL poisoning. The saverestore module exposes its admin() method through the /objects/?module=saverestore endpoint without authentication becaus…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-18*
