# Daily Threat Intelligence — August 18, 2025

**Digest window (UTC):** 2025-08-18
**Generated:** 2026-06-02T07:33:15Z

## Threat brief

Trend Micro Apex One added to CISA KEV — confirmed in-the-wild exploitation. · Tenda Ac20 Firmware: public exploit or PoC linked (Command Injection) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Trend Micro Apex One added to CISA KEV — confirmed in-the-wild exploitation.
- Tenda Ac20 Firmware: public exploit or PoC linked (Command Injection)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 7 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2025-54948
**Trend Micro Apex One OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** trendmicro apex_one
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T14:42:24.467
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-08-18

> A vulnerability in Trend Micro Apex One (on-premise) management console could allow a pre-authenticated remote attacker to upload malicious code and execute commands on affected installations.

### CVE-2024-28623
**ritecms ritecms XSS**
- **Signals:** EXP
- **Asset:** ritecms ritecms
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-04-16T15:33:39.210
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> RiteCMS v3.0.0 was discovered to contain a cross-site scripting (XSS) vulnerability via the component main_menu/edit_section.

### CVE-2025-55591
**totolink a3002r_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink a3002r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-21T14:11:06.290
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-18)

> TOTOLINK-A3002R v4.0.0-B20230531.1404 was discovered to contain a command injection vulnerability in the devicemac parameter in the formMapDel endpoint.

### CVE-2015-6830
**phpmyadmin phpmyadmin**
- **Signals:** EXP
- **Asset:** phpmyadmin phpmyadmin
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> libraries/plugins/auth/AuthenticationCookie.class.php in phpMyAdmin 4.3.x before 4.3.13.2 and 4.4.x before 4.4.14.1 allows remote attackers to bypass a multiple-reCaptcha protection mechanism against brute-force credential guessing by providing a correct response to a single reCa…

### CVE-2024-54761
**bigantsoft bigant_office_messenger_5 SQL Injection**
- **Signals:** EXP
- **Asset:** bigantsoft bigant_office_messenger_5
- **Attack:** SQL Injection
- **CVSS max:** 6.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-29T17:43:45.920
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> BigAnt Office Messenger 5.6.06 is vulnerable to SQL Injection via the 'dev_code' parameter.

### CVE-2025-31715
**In vowifi service, there is a possible command injection due to improper input validation.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-18)

> In vowifi service, there is a possible command injection due to improper input validation. This could lead to remote escalation of privilege with no additional execution privileges needed.

### CVE-2025-50154
**microsoft windows_10_1507**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2025-10-21T15:15:38.670
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> Exposure of sensitive information to an unauthorized actor in Windows File Explorer allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-52392
**Soosyze CMS 2.0 allows brute-force login attacks via the /user/login endpoint due to missing rate-limiting and lockout mechanisms.**
- **Signals:** EXP
- **CVSS max:** 5.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-307
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> Soosyze CMS 2.0 allows brute-force login attacks via the /user/login endpoint due to missing rate-limiting and lockout mechanisms. An attacker can repeatedly submit login attempts without restrictions, potentially gaining unauthorized administrative access. This vulnerability cor…

### CVE-2025-54117
**namelessmc nameless XSS**
- **Signals:** CVSS
- **Asset:** namelessmc nameless
- **Attack:** XSS
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-20T21:23:49.083
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-08-18)

> NamelessMC is a free, easy to use & powerful website software for Minecraft servers. Cross-site scripting (XSS) vulnerability in NamelessMC before 2.2.3 allows remote authenticated attackers to inject arbitrary web script or HTML via the dashboard text editor component. This vuln…

### CVE-2025-54156
**santesoft sante_pacs_server**
- **Signals:** CVSS
- **Asset:** santesoft sante_pacs_server
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T17:28:02.640
- **CWE:** CWE-319
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-18)

> The Sante PACS Server Web Portal sends credential information without encryption.

### CVE-2025-55205
**Capsule is a multi-tenancy and policy-based framework for Kubernetes.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-08-18)

> Capsule is a multi-tenancy and policy-based framework for Kubernetes. A namespace label injection vulnerability in Capsule v0.10.3 and earlier allows authenticated tenant users to inject arbitrary labels into system namespaces (kube-system, default, capsule-system), bypassing mul…

### CVE-2025-55282
**aiven aiven-db-migrate Privilege Escalation**
- **Signals:** CVSS
- **Asset:** aiven aiven-db-migrate
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-21T21:40:35.840
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-18)

> aiven-db-migrate is an Aiven database migration tool. Prior to 1.0.7, there is a privilege escalation vulnerability that allows a user to elevate to superuser inside PostgreSQL databases during a migration from an untrusted source server. By exploiting a lack of search_path restr…

### CVE-2025-55283
**aiven aiven-db-migrate Privilege Escalation**
- **Signals:** CVSS
- **Asset:** aiven aiven-db-migrate
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-21T21:38:40.753
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-18)

> aiven-db-migrate is an Aiven database migration tool. Prior to 1.0.7, there is a privilege escalation vulnerability that allows elevation to superuser inside PostgreSQL databases during a migration from an untrusted source server. The vulnerability stems from psql executing comma…

### CVE-2025-55293
**meshtastic meshtastic_firmware**
- **Signals:** CVSS
- **Asset:** meshtastic meshtastic_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T17:48:30.923
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-18)

> Meshtastic is an open source mesh networking solution. Prior to v2.6.3, an attacker can send NodeInfo with a empty publicKey first, then overwrite it with a new key. First sending a empty key bypasses 'if (p.public_key.size > 0) {', clearing the existing publicKey (and resetting …

### CVE-2025-55299
**VaulTLS is a modern solution for managing mTLS (mutual TLS) certificates.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-521
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-18)

> VaulTLS is a modern solution for managing mTLS (mutual TLS) certificates. Prior to 0.9.1, user accounts created through the User web UI have an empty but not NULL password set, attackers can use this to login with an empty password. This is combined with that fact, that previousl…

### CVE-2025-7693
**A security issue exists due to improper handling of malformed CIP Forward Close packets during fuzzing.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-18)

> A security issue exists due to improper handling of malformed CIP Forward Close packets during fuzzing. The controller enters a solid red Fault LED state and becomes unresponsive. Upon power cycle, the controller will enter recoverable fault where the MS LED and Fault LED become …

### CVE-2025-7766
**Lantronix Provisioning Manager is vulnerable to XML external entity attacks in configuration files supplied by network devices, leading t...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-611
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> Lantronix Provisioning Manager is vulnerable to XML external entity attacks in configuration files supplied by network devices, leading to unauthenticated remote code execution on hosts with Provisioning Manager installed.

### CVE-2025-9090
**tenda ac20_firmware Command Injection**
- **Signals:** EXP
- **Asset:** tenda ac20_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-74
- **Risk score:** 78
- **EXP:** ref published 2025-08-18

> A vulnerability was identified in Tenda AC20 16.03.08.12. Affected is the function websFormDefine of the file /goform/telnet of the component Telnet Service. The manipulation leads to command injection. It is possible to launch the attack remotely. The exploit has been disclosed …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-18*
