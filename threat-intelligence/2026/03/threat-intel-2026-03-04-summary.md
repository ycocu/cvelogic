# Daily Threat Intelligence — March 04, 2026

**Digest window (UTC):** 2026-03-04
**Generated:** 2026-06-02T07:34:34Z

## Threat brief

Checkpoint Vpn-1 Firewall-1 — exploitation likelihood rose sharply (EPSS 9.5% → 72% · rising (+63%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Checkpoint Vpn-1 Firewall-1 — exploitation likelihood rose sharply (EPSS 9.5% → 72% · rising (+63%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2002-1623
**checkpoint vpn-1_firewall-1**
- **Signals:** EPSS
- **Asset:** checkpoint vpn-1_firewall-1
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 9.5% (2026-03-01) → 72.5% (2026-03-04), Δ +62.9%**

> The design of the Internet Key Exchange (IKE) protocol, when using Aggressive Mode for shared secret authentication, does not encrypt initiator or responder identities during negotiation, which may allow remote attackers to determine valid usernames by (1) monitoring responses be…

### CVE-2018-10548
**canonical debian_linux DoS**
- **Signals:** EPSS
- **Asset:** php php
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:41:32.600
- **CWE:** CWE-476
- **Risk score:** 82
- **EPSS 14.3% (2026-03-01) → 52.7% (2026-03-04), Δ +38.4%**

> An issue was discovered in PHP before 5.6.36, 7.0.x before 7.0.30, 7.1.x before 7.1.17, and 7.2.x before 7.2.5. ext/ldap/ldap.c allows remote LDAP servers to cause a denial of service (NULL pointer dereference and application crash) because of mishandling of the ldap_get_dn retur…

### CVE-2026-20131
**Cisco Secure Firewall Management Center (FMC) Software and Cisco Security Cloud Control (SCC) Firewall Management Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** cisco secure_firewall_management_center
- **Attack:** Deserialization
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T17:39:46.247
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-04)

> A vulnerability in the web-based management interface of Cisco Secure Firewall Management Center (FMC) Software could allow an unauthenticated, remote attacker to execute arbitrary Java code as root&nbsp;on an affected device.

This vulnerability is due to insecure deserializat…

### CVE-2000-1039
**microsoft windows_95 DoS**
- **Signals:** EPSS
- **Asset:** microsoft windows_95
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 17.1% (2026-03-01) → 44.9% (2026-03-04), Δ +27.7%**

> Various TCP/IP stacks and network applications allow remote attackers to cause a denial of service by flooding a target host with TCP connection attempts and completing the TCP/IP handshake without maintaining the connection state on the attacker host, aka the "NAPTHA" class of v…

### CVE-2004-0488
**apache debian_linux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-787
- **Risk score:** 82
- **EPSS 30.8% (2026-03-01) → 62.7% (2026-03-04), Δ +31.8%**

> Stack-based buffer overflow in the ssl_util_uuencode_binary function in ssl_util.c for Apache mod_ssl, when mod_ssl is configured to trust the issuing CA, may allow remote attackers to execute arbitrary code via a client certificate with a long subject DN.

### CVE-2004-0786
**apache http_server DoS**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 11.2% (2026-03-01) → 48.4% (2026-03-04), Δ +37.2%**

> The IPv6 URI parsing routines in the apr-util library for Apache 2.0.50 and earlier allow remote attackers to cause a denial of service (child process crash) via a certain URI, as demonstrated using the Codenomicon HTTP Test Tool.

### CVE-2005-2728
**apache http_server DoS**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 31.8% (2026-03-01) → 61.8% (2026-03-04), Δ +30.0%**

> The byte-range filter in Apache 2.0 before 2.0.54 allows remote attackers to cause a denial of service (memory consumption) via an HTTP header with a large Range field.

### CVE-2009-4873
**rhinosoft serv-u Buffer Overflow**
- **Signals:** EPSS
- **Asset:** rhinosoft serv-u
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 22.3% (2026-03-01) → 60.2% (2026-03-04), Δ +37.9%**

> Stack-based buffer overflow in the HTTP server in Rhino Software Serv-U Web Client 9.0.0.5 allows remote attackers to cause a denial of service (server crash) or execute arbitrary code via a long Session cookie.

### CVE-2014-0117
**apache http_server DoS**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** DoS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 77
- **EPSS 29.3% (2026-03-01) → 57.0% (2026-03-04), Δ +27.7%**

> The mod_proxy module in the Apache HTTP Server 2.4.x before 2.4.10, when a reverse proxy is enabled, allows remote attackers to cause a denial of service (child-process crash) via a crafted HTTP Connection header.

### CVE-2014-3556
**f5 nginx Command Injection**
- **Signals:** EPSS
- **Asset:** f5 nginx
- **Attack:** Command Injection
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-77
- **Risk score:** 81
- **EPSS 20.6% (2026-03-01) → 48.2% (2026-03-04), Δ +27.6%**

> The STARTTLS implementation in mail/ngx_mail_smtp_handler.c in the SMTP proxy in nginx 1.5.x and 1.6.x before 1.6.1 and 1.7.x before 1.7.4 does not properly restrict I/O buffering, which allows man-in-the-middle attackers to insert commands into encrypted SMTP sessions by sending…

### CVE-2023-2164
**gitlab gitlab cross-site scripting**
- **Signals:** EPSS
- **Asset:** gitlab gitlab
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:58:03.893
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 18.8% (2026-03-01) → 52.2% (2026-03-04), Δ +33.4%**

> An issue has been discovered in GitLab affecting all versions starting from 15.9 before 16.0.8, all versions starting from 16.1 before 16.1.3, all versions starting from 16.2 before 16.2.2. It was possible for an attacker to trigger a stored XSS vulnerability via user interaction…

### CVE-2025-46108
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T20:13:08.317
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> D-link Dir-513 A1FW110 is vulnerable to Buffer Overflow in the function formTcpipSetup.

### CVE-2025-70219
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T17:48:51.900
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the goform/formDeviceReboot.

### CVE-2025-70221
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T17:48:25.400
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the curTime parameter to goform/formLogin.

### CVE-2025-70222
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T17:38:50.697
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the curTime parameter to goform/formLogin,goform/getAuthCode.

### CVE-2025-70223
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T17:49:34.860
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the curTime parameter to goform/formAdvNetwork.

### CVE-2025-70225
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T17:47:55.410
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the curtime parameter to the goform/formEasySetupWWConfig component

### CVE-2025-70226
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T17:49:13.093
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-04)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the curTime parameter to goform/formEasySetupWizard.

### CVE-2026-29000
**pac4j-jwt versions prior to 4.5.9, 5.7.9, and 6.3.3 contain an authentication bypass vulnerability in JwtAuthenticator when processing en...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-16T16:18:36.200
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-04)

> pac4j-jwt versions prior to 4.5.9, 5.7.9, and 6.3.3 contain an authentication bypass vulnerability in JwtAuthenticator when processing encrypted JWTs that allows remote attackers to forge authentication tokens. Attackers who possess the server's RSA public key can create a JWE-wr…

### CVE-2026-3545
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T21:57:27.147
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-04)

> Insufficient data validation in Navigation in Google Chrome prior to 145.0.7632.159 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-04*
