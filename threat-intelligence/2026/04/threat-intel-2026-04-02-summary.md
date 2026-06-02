# Daily Threat Intelligence — April 02, 2026

**Digest window (UTC):** 2026-04-02
**Generated:** 2026-06-02T07:34:49Z

## Threat brief

TrueConf Client added to CISA KEV — confirmed in-the-wild exploitation. · Themegrill Masteriyo — exploitation likelihood rose sharply (EPSS 32% → 48% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- TrueConf Client added to CISA KEV — confirmed in-the-wild exploitation.
- Themegrill Masteriyo — exploitation likelihood rose sharply (EPSS 32% → 48% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2026-3502
**TrueConf Client Download of Code Without Integrity Check Vulnerability**
- **Signals:** KEV
- **Asset:** trueconf trueconf
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T11:40:57.390
- **CWE:** CWE-494
- **Risk score:** 88
- **KEV:** added 2026-04-02

> TrueConf Client downloads application update code and applies it without performing verification. An attacker who is able to influence the update delivery path can substitute a tampered update payload. If the payload is executed or installed by the updater, this may result in arb…

### CVE-2024-24882
**themegrill masteriyo privilege escalation**
- **Signals:** EPSS
- **Asset:** themegrill masteriyo
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T10:16:31.920
- **CWE:** CWE-266
- **Risk score:** 86
- **EPSS 31.5% (2026-01-18) → 48.3% (2026-04-02), Δ +16.7%**

> Incorrect Privilege Assignment vulnerability in masteriyo Masteriyo - LMS learning-management-system.This issue affects Masteriyo - LMS: from n/a through <= 1.7.2.

### CVE-2026-34717
**openproject openproject SQL injection**
- **Signals:** CVSS
- **Asset:** openproject openproject
- **Attack:** SQL injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T01:03:32.890
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-02)

> OpenProject is an open-source, web-based project management software. Prior to version 17.2.3, the =n operator in modules/reporting/lib/report/operator.rb:177 embeds user input directly into SQL WHERE clauses without parameterization. This issue has been patched in version 17.2.3…

### CVE-2022-25226
**cybelsoft thinvnc Code Execution**
- **Signals:** EPSS
- **Asset:** cybelsoft thinvnc
- **Attack:** Code Execution
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:51:50.393
- **Risk score:** 86
- **EPSS 69.7% (2026-04-01) → 81.9% (2026-04-02), Δ +12.2%**

> ThinVNC version 1.0b1 allows an unauthenticated user to bypass the authentication process via 'http://thin-vnc:8080/cmd?cmd=connect' by obtaining a valid SID without any kind of authentication. It is possible to achieve code execution on the server by sending keyboard or mouse ev…

### CVE-2024-14034
**Hirschmann HiEOS devices versions prior to 01.1.00 contain an authentication bypass vulnerability in the HTTP(S) management module that a...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-03T23:17:01.753
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-02)

> Hirschmann HiEOS devices versions prior to 01.1.00 contain an authentication bypass vulnerability in the HTTP(S) management module that allows unauthenticated remote attackers to gain administrative access by sending specially crafted HTTP(S) requests. Attackers can exploit impro…

### CVE-2024-25228
**vinchin vinchin_backup_and_recovery RCE**
- **Signals:** EPSS
- **Asset:** vinchin vinchin_backup_and_recovery
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T19:16:58.600
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 43.7% (2025-11-25) → 57.7% (2026-04-02), Δ +14.0%**

> Vinchin Backup and Recovery 7.2 and Earlier is vulnerable to Authenticated Remote Code Execution (RCE) via the getVerifydiyResult function in ManoeuvreHandler.class.php.

### CVE-2025-15620
**HiOS Switch Platform versions 09.1.00 through 09.4.04 and 10.0.00 through 10.3.00 contain a denial-of-service vulnerability in the web in...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-26T00:16:48.017
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-02)

> HiOS Switch Platform versions 09.1.00 through 09.4.04 and 10.0.00 through 10.3.00 contain a denial-of-service vulnerability in the web interface that allows remote attackers to reboot the affected device by sending a malicious HTTP GET request to a specific endpoint. Attackers ca…

### CVE-2025-41646
**kunbus revpi_status**
- **Signals:** EPSS
- **Asset:** kunbus revpi_status
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-10T19:29:22.893
- **CWE:** CWE-704
- **Risk score:** 86
- **EPSS 19.0% (2026-03-03) → 33.8% (2026-04-02), Δ +14.8%**

> An unauthorized remote attacker can bypass the authentication of the affected software package by misusing an incorrect type conversion. This leads to full compromise of the device

### CVE-2026-33950
**signalk signal_k_server Privilege Escalation**
- **Signals:** CVSS
- **Asset:** signalk signal_k_server
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T15:04:42.720
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-02)

> Signal K Server is a server application that runs on a central hub in a boat. Prior to version 2.24.0-beta.4, there is a privilege escalation vulnerability by Admin Role Injection via /enableSecurity. An unauthenticated attacker can gain full Administrator access to the SignalK s…

### CVE-2026-34745
**shaneisrael fireshare**
- **Signals:** CVSS
- **Asset:** shaneisrael fireshare
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T19:50:08.803
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-02)

> Fireshare facilitates self-hosted media and link sharing. Prior to version 1.5.3, the fix for CVE-2026-33645 was applied to the authenticated /api/uploadChunked endpoint but was not applied to the unauthenticated /api/uploadChunked/public endpoint in the same file (app/server/fir…

### CVE-2026-34758
**hackerbay oneuptime**
- **Signals:** CVSS
- **Asset:** hackerbay oneuptime
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T19:52:26.097
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-02)

> OneUptime is an open-source monitoring and observability platform. Prior to version 10.0.42, unauthenticated access to Notification test and Phone Number management endpoints allows SMS/Call/Email/WhatsApp abuse and phone number purchase. This issue has been patched in version 10…

### CVE-2026-34759
**hackerbay oneuptime privilege escalation**
- **Signals:** CVSS
- **Asset:** hackerbay oneuptime
- **Attack:** privilege escalation
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T18:45:18.940
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-02)

> OneUptime is an open-source monitoring and observability platform. Prior to version 10.0.42, multiple notification API endpoints are registered without authentication middleware, while sibling endpoints in the same codebase correctly use ClusterKeyAuthorization.isAuthorizedServic…

### CVE-2026-34838
**intermesh group-office Deserialization**
- **Signals:** CVSS
- **Asset:** intermesh group-office
- **Attack:** Deserialization
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T17:29:12.483
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-02)

> Group-Office is an enterprise customer relationship management and groupware tool. Prior to versions 6.8.156, 25.0.90, and 26.0.12, a vulnerability in the AbstractSettingsCollection model leads to insecure deserialization when these settings are loaded. By injecting a serialized …

### CVE-2026-34877
**arm mbed_tls RCE**
- **Signals:** CVSS
- **Asset:** arm mbed_tls
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T21:06:00.037
- **CWE:** CWE-250
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-02)

> An issue was discovered in Mbed TLS versions from 2.19.0 up to 3.6.5, Mbed TLS 4.0.0. Insufficient protection of serialized SSL context or session structures allows an attacker who can modify the serialized structures to induce memory corruption, leading to arbitrary code executi…

### CVE-2026-35053
**hackerbay oneuptime**
- **Signals:** CVSS
- **Asset:** hackerbay oneuptime
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T18:46:50.110
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-02)

> OneUptime is an open-source monitoring and observability platform. Prior to version 10.0.42, the Worker service's ManualAPI exposes workflow execution endpoints (GET /workflow/manual/run/:workflowId and POST /workflow/manual/run/:workflowId) without any authentication middleware.…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-02*
