# Daily Threat Intelligence — June 04, 2026

**Digest window (UTC):** 2026-06-04
**Generated:** 2026-06-05T23:49:19Z

## Threat brief

Gomlab Gom Player — exploitation likelihood rose sharply (EPSS 26% → 51% · rising (+24%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Gomlab Gom Player — exploitation likelihood rose sharply (EPSS 26% → 51% · rising (+24%)).
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

### CVE-2011-5162
**gomlab gom_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** gomlab gom_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 26.3% (2026-05-17) → 50.8% (2026-06-04), Δ +24.5%**

> Stack-based buffer overflow in GOM Player 2.1.33.5071 allows user-assisted remote attackers to execute arbitrary code via a .ASX file with a long URI in the "ref href" tag.  NOTE: this issue exists because of a CVE-2007-0707 regression.

### CVE-2021-3239
**e-learning_system_project e-learning_system SQL Injection**
- **Signals:** EPSS
- **Asset:** e-learning_system_project e-learning_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:21:09.310
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 38.4% (2025-03-30) → 62.7% (2026-06-04), Δ +24.3%**

> E-Learning System 1.0 suffers from an unauthenticated SQL injection vulnerability, which allows remote attackers to execute arbitrary code on the hosting web server and gain a reverse shell.

### CVE-2026-48567
**Authentication bypass by spoofing in Azure HorizonDB allows an unauthorized attacker to elevate privileges over a network.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD modified:** 2026-06-04T23:17:32.677
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-04)

> Authentication bypass by spoofing in Azure HorizonDB allows an unauthorized attacker to elevate privileges over a network.

### CVE-2012-10041
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 57.6% (2026-04-24) → 74.2% (2026-06-04), Δ +16.6%**

> WAN Emulator v2.3 contains two unauthenticated command execution vulnerabilities. The result.php script calls shell_exec() with unsanitized input from the pc POST parameter, allowing remote attackers to execute arbitrary commands as the www-data user. The system also includes a S…

### CVE-2012-10042
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 47.6% (2026-04-24) → 67.0% (2026-06-04), Δ +19.4%**

> Sflog! CMS 1.0 contains an authenticated arbitrary file upload vulnerability in the blog management interface. The application ships with default credentials (admin:secret) and allows authenticated users to upload files via manage.php. The upload mechanism fails to validate file …

### CVE-2012-10046
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 52.9% (2026-01-05) → 68.1% (2026-06-04), Δ +15.1%**

> The E-Mail Security Virtual Appliance (ESVA) (tested on version ESVA_2057) contains an unauthenticated command injection vulnerability in the learn-msg.cgi script. The CGI handler fails to sanitize user-supplied input passed via the id parameter, allowing attackers to inject arbi…

### CVE-2012-10047
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:21.953
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 53.2% (2026-04-24) → 71.2% (2026-06-04), Δ +18.0%**

> Cyclope Employee Surveillance Solution versions 6.x are vulnerable to a SQL injection flaw in its login mechanism. The username parameter in the auth-login POST request is not properly sanitized, allowing attackers to inject arbitrary SQL statements. This can be leveraged to writ…

### CVE-2012-10048
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 54.3% (2026-04-24) → 72.0% (2026-06-04), Δ +17.6%**

> Zenoss Core 3.x contains a command injection vulnerability in the showDaemonXMLConfig endpoint. The daemon parameter is passed directly to a Popen() call in ZenossInfo.py without proper sanitation, allowing authenticated users to execute arbitrary commands on the server as the ze…

### CVE-2013-2760
**bestwebsharing groovy_media_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** bestwebsharing groovy_media_player
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 6.8% (2025-03-30) → 24.2% (2026-06-04), Δ +17.5%**

> Buffer overflow in Groovy Media Player 3.2.0 allows remote attackers to execute arbitrary code via a long string in a .m3u file.

### CVE-2025-67446
**Improper Authentication (Authentication Bypass) exists in Neterbit NW-431F Router 20241014-IR03 and before.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-04T19:15:31.080
- **CWE:** CWE-384
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-04)

> Improper Authentication (Authentication Bypass) exists in Neterbit NW-431F Router 20241014-IR03 and before. The router uses a weak/predictable cookie value for authentication. By modifying the cookie value (e.g., setting it to "admin"), an attacker can bypass the authentication s…

### CVE-2025-67447
**The network diagnosis (ping) module in Neterbit NW-431F Router 20241014-IR03 and before is vulnerable to OS command injection.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-04T19:16:26.597
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-04)

> The network diagnosis (ping) module in Neterbit NW-431F Router 20241014-IR03 and before is vulnerable to OS command injection. The application does not properly sanitize user input in the IP address field before passing it to the system's ping command. An attacker can inject arbi…

### CVE-2025-71316
**SQLite 'sqldiff.exe' does not securely handle the way the Microsoft Windows C runtime converts Unicode characters to ANSI codepages.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-04T20:16:56.947
- **CWE:** CWE-176
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-04)

> SQLite 'sqldiff.exe' does not securely handle the way the Microsoft Windows C runtime converts Unicode characters to ANSI codepages.  An attacker could use the '-L' option to load an arbitrary DLL with a crafted command line argument string that results in command line file argum…

### CVE-2025-8730
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-259
- **Risk score:** 84
- **EPSS 30.2% (2026-04-24) → 45.1% (2026-06-04), Δ +14.9%**

> A vulnerability was found in Belkin F9K1009 and F9K1010 2.00.04/2.00.09 and classified as critical. Affected by this issue is some unknown functionality of the component Web Interface. The manipulation leads to hard-coded credentials. The attack may be launched remotely. The expl…

### CVE-2026-10868
**A mass assignment vulnerability exists in the MISP user edit functionality due to insufficient filtering of user-supplied fields in Users...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-06-04T16:20:27.330
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-04)

> A mass assignment vulnerability exists in the MISP user edit functionality due to insufficient filtering of user-supplied fields in UsersController::edit(). When processing edit requests, the application accepted a user-controlled User.id value from request data. An authenticated…

### CVE-2026-10880
**OSNexus QuantaStor SDS Manager is vulnerable to SQL injection in the login endpoint.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-04T19:15:17.327
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-04)

> OSNexus QuantaStor SDS Manager is vulnerable to SQL injection in the login endpoint. The username field is not properly sanitized before being incorporated into a SQL query, allowing an unauthenticated remote attacker to bypass authentication and log in as an administrator withou…

### CVE-2026-25550
**Seagull Software BarTender 2010, 2016, and 2019 contain an unauthenticated remote code execution vulnerability in the .NET Remoting servi...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-04T19:15:17.327
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-04)

> Seagull Software BarTender 2010, 2016, and 2019 contain an unauthenticated remote code execution vulnerability in the .NET Remoting service exposed on TCP port 7375 via BtSystem.Service.exe. The service registers an unauthenticated singleton endpoint — BarTenderSystem for BarTend…

### CVE-2026-29059
**windmill windmill Path Traversal**
- **Signals:** EPSS
- **Asset:** windmill windmill
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T17:48:25.300
- **CWE:** CWE-22
- **Risk score:** 81
- **EPSS 0.0% (2026-04-15) → 23.3% (2026-06-04), Δ +23.3%**

> Windmill is an open-source developer platform for internal code: APIs, background jobs, workflows and UIs. Prior to version 1.603.3, an unauthenticated path traversal vulnerability exists in Windmill's get_log_file endpoint "(/api/w/{workspace}/jobs_u/get_log_file/{filename})". T…

### CVE-2026-43986
**Tautulli is a Python based monitoring and tracking tool for Plex Media Server.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-06-04T18:16:30.743
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-04)

> Tautulli is a Python based monitoring and tracking tool for Plex Media Server. Versions prior to 2.17.1 expose a public `/image/<hash>` route that resolves attacker-controlled entries from `image_hash_lookup` and replays them through the same server-side image fetch logic used by…

### CVE-2026-48579
**Improper authorization in Microsoft Exchange Online allows an unauthorized attacker to disclose information over a network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD modified:** 2026-06-04T23:17:32.830
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-04)

> Improper authorization in Microsoft Exchange Online allows an unauthorized attacker to disclose information over a network.

### CVE-2026-50076
**Deserialization of Untrusted Data in the Java replace-resolve path in Apache Fory fory-core Java SDK before 1.1.0 on Java/JVM platforms a...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.1
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-04T19:15:17.327
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-04)

> Deserialization of Untrusted Data in the Java replace-resolve path in Apache Fory fory-core Java SDK before 1.1.0 on Java/JVM platforms allows a remote attacker to bypass class registration, TypeChecker, and DisallowedList checks and invoke classpath-present readResolve/readExter…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-04*
