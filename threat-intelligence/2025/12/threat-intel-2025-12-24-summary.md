# Daily Threat Intelligence — December 24, 2025

**Digest window (UTC):** 2025-12-24
**Generated:** 2026-06-02T07:34:02Z

## Threat brief

Zohocorp Manageengine Admanager Plus — exploitation likelihood rose sharply (EPSS 35% → 79% · rising (+44%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Zohocorp Manageengine Admanager Plus — exploitation likelihood rose sharply (EPSS 35% → 79% · rising (+44%)).
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

### CVE-2022-42904
**zohocorp manageengine_admanager_plus**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_admanager_plus
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2025-04-30T14:15:25.133
- **CWE:** CWE-77
- **Risk score:** 82
- **EPSS 35.0% (2025-11-21) → 79.4% (2025-12-24), Δ +44.5%**

> Zoho ManageEngine ADManager Plus through 7151 allows authenticated admin users to execute the commands in proxy settings.

### CVE-2019-25241
**iwt facesentry_access_control_system_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** iwt facesentry_access_control_system_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-12-31T14:15:50.723
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-24)

> FaceSentry Access Control System 6.4.8 contains a critical authentication vulnerability with hard-coded SSH credentials for the wwwuser account. Attackers can leverage the insecure sudoers configuration to escalate privileges and gain root access by executing sudo commands withou…

### CVE-2025-13773
**The Print Invoice & Delivery Notes for WooCommerce plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-24)

> The Print Invoice & Delivery Notes for WooCommerce plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 5.8.0 via the 'WooCommerce_Delivery_Notes::update' function. This is due to missing capability check in the 'WooCommerce_Delivery_N…

### CVE-2018-25128
**SOCA Access Control System 180612 contains multiple SQL injection vulnerabilities that allow attackers to manipulate database queries thr...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> SOCA Access Control System 180612 contains multiple SQL injection vulnerabilities that allow attackers to manipulate database queries through unvalidated POST parameters. Attackers can bypass authentication, retrieve password hashes, and gain administrative access with full syste…

### CVE-2018-25134
**Synaccess netBooter NP-02x/NP-08x 6.8 contains an authentication bypass vulnerability in the webNewAcct.cgi script that allows unauthenti...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> Synaccess netBooter NP-02x/NP-08x 6.8 contains an authentication bypass vulnerability in the webNewAcct.cgi script that allows unauthenticated attackers to create admin user accounts. Attackers can exploit the missing control check by sending crafted POST requests to create admin…

### CVE-2018-25135
**Anviz AIM CrossChex Standard 4.3.6.0 contains a CSV injection vulnerability that allows attackers to execute commands by inserting malici...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-149
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> Anviz AIM CrossChex Standard 4.3.6.0 contains a CSV injection vulnerability that allows attackers to execute commands by inserting malicious formulas in user import fields. Attackers can craft payloads in fields like 'Name', 'Gender', or 'Position' to trigger Excel macro executio…

### CVE-2018-25138
**flir flir_ax8_firmware**
- **Signals:** CVSS
- **Asset:** flir flir_ax8_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-05T14:15:50.533
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> FLIR AX8 Thermal Camera 1.32.16 contains hard-coded SSH and web panel credentials that cannot be changed through normal camera operations. Attackers can exploit these persistent credentials to gain unauthorized shell access and login to multiple camera interfaces using predefined…

### CVE-2018-25140
**FLIR thermal traffic cameras contain an unauthenticated device manipulation vulnerability in their WebSocket implementation that allows a...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> FLIR thermal traffic cameras contain an unauthenticated device manipulation vulnerability in their WebSocket implementation that allows attackers to bypass authentication and authorization controls. Attackers can directly modify device configurations, access system information, a…

### CVE-2018-25147
**microhardcorp bullet-3g_firmware**
- **Signals:** CVSS
- **Asset:** microhardcorp ipn4g_firmware
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-26T19:47:07.440
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> Microhard Systems IPn4G 1.1.0 contains hardcoded default credentials that cannot be changed through normal gateway operations. Attackers can exploit these default credentials to gain unauthorized root-level access to the device by logging in with predefined username and password …

### CVE-2025-68916
**riello-ups netman_208 Code Execution**
- **Signals:** CVSS
- **Asset:** riello-ups netman_208
- **Attack:** Code Execution
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-02T19:44:03.497
- **CWE:** CWE-25
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-24)

> Riello UPS NetMan 208 Application before 1.12 allows cgi-bin/certsupload.cgi /../ directory traversal for file upload with resultant code execution.

### CVE-2025-8769
**Telenium Online Web Application is vulnerable due to a Perl script that is called to load the login page.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-24)

> Telenium Online Web Application is vulnerable due to a Perl script that 
is called to load the login page. Due to improper input validation, an 
attacker can inject arbitrary Perl code through a crafted HTTP request, 
leading to remote code execution on the server.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-24*
