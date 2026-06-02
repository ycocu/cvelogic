# Daily Threat Intelligence — October 02, 2025

**Digest window (UTC):** 2025-10-02
**Generated:** 2026-06-02T07:33:31Z

## Threat brief

Samsung Mobile Devices added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Samsung Mobile Devices added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2014-6278
**GNU Bash OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** gnu bash
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:07:15.530
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-10-02

> GNU Bash through 4.3 bash43-026 does not properly parse function definitions in the values of environment variables, which allows remote attackers to execute arbitrary commands via a crafted environment, as demonstrated by vectors involving the ForceCommand feature in OpenSSH ssh…

### CVE-2025-59403
**flocksafety flock_safety**
- **Signals:** CVSS
- **Asset:** flocksafety flock_safety
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-24T15:15:48.800
- **CWE:** CWE-749
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-02)

> The Flock Safety Android Collins application (aka com.flocksafety.android.collins) 6.35.31 for Android lacks authentication. It is responsible for the camera feed on Falcon, Sparrow, and Bravo devices, but exposes administrative API endpoints on port 8080 without authentication. …

### CVE-2025-59407
**flocksafety flock_safety**
- **Signals:** CVSS
- **Asset:** flocksafety flock_safety
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T17:26:24.580
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-02)

> The Flock Safety DetectionProcessing com.flocksafety.android.objects application 6.35.33 for Android (installed on Falcon and Sparrow License Plate Readers and Bravo Edge AI Compute Devices) bundles a Java Keystore (flock_rye.bks) along with its hardcoded password (flockhibiki17)…

### CVE-2015-7755
**Juniper ScreenOS Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** juniper screenos
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T16:27:21.830
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2025-10-02

> Juniper ScreenOS 6.2.0r15 through 6.2.0r18, 6.3.0r12 before 6.3.0r12b, 6.3.0r13 before 6.3.0r13b, 6.3.0r14 before 6.3.0r14b, 6.3.0r15 before 6.3.0r15b, 6.3.0r16 before 6.3.0r16b, 6.3.0r17 before 6.3.0r17b, 6.3.0r18 before 6.3.0r18b, 6.3.0r19 before 6.3.0r19b, and 6.3.0r20 before …

### CVE-2017-1000353
**Jenkins Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** jenkins jenkins
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:24:40.943
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-10-02

> Jenkins versions 2.56 and earlier as well as 2.46.1 LTS and earlier are vulnerable to an unauthenticated remote code execution. An unauthenticated remote code execution vulnerability allowed attackers to transfer a serialized Java `SignedObject` object to the Jenkins CLI, that wo…

### CVE-2025-21043
**Samsung Mobile Devices Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** samsung android
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T15:36:12.360
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-10-02

> Out-of-bounds write in libimagecodec.quram.so prior to SMR Sep-2025 Release 1 allows remote attackers to execute arbitrary code.

### CVE-2025-34210
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T19:22:03.683
- **CWE:** CWE-256
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-02)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host and Application (VA/SaaS deployments) store a large number of sensitive credentials (database passwords, MySQL root password, SaaS keys, Portainer admin password, etc.) in cleartext files that are world-readable. Any loc…

### CVE-2025-4008
**Smartbedded Meteobridge Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** smartbedded meteobridge_vm
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:02:18.900
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2025-10-02

> The Meteobridge web interface let meteobridge administrator manage their weather station data collection and administer their meteobridge system through a web application written in CGI shell scripts and C.

This web interface exposes an endpoint that is vulnerable to command inj…

### CVE-2025-59739
**andsoft e-tms Command Injection**
- **Signals:** CVSS
- **Asset:** andsoft e-tms
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T20:25:41.133
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-02)

> Operating system command injection vulnerability in AndSoft's e-TMS v25.03. This vulnerability allows an attacker to execute operating system commands on the server by sending a POST request. The relationship between parameter and assigned identifier is a 'm' parameter in '/clt/L…

### CVE-2025-59740
**andsoft e-tms Command Injection**
- **Signals:** CVSS
- **Asset:** andsoft e-tms
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T20:29:29.883
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-02)

> Operating system command injection vulnerability in AndSoft's e-TMS v25.03. This vulnerability allows an attacker to execute operating system commands on the server by sending a POST request. The relationship between parameter and assigned identifier is a 'm' parameter in '/clt/L…

### CVE-2025-59741
**andsoft e-tms Command Injection**
- **Signals:** CVSS
- **Asset:** andsoft e-tms
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T20:29:54.237
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-02)

> Operating system command injection vulnerability in AndSoft's e-TMS v25.03. This vulnerability allows an attacker to execute operating system commands on the server by sending a POST request. The relationship between parameter and assigned identifier is a 'm' parameter in '/CLT/L…

### CVE-2025-59742
**andsoft e-tms SQL Injection**
- **Signals:** CVSS
- **Asset:** andsoft e-tms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T20:30:04.473
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-02)

> SQL injection vulnerability in AndSoft's e-TMS v25.03. This vulnerability could allow an attacker to retrieve, create, update, and delete databases by sending a POST request. The relationship between parameter and assigned identifier is a 'USRMAIL' parameter in'/inc/login/TRACK_R…

### CVE-2025-59743
**andsoft e-tms SQL Injection**
- **Signals:** CVSS
- **Asset:** andsoft e-tms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T20:31:17.863
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-02)

> SQL injection vulnerability in AndSoft's e-TMS v25.03. This vulnerability could allow an attacker to retrieve, create, update, and delete databases by sending a POST request. The relationship between parameter and assigned identifier is a 'SessionID' cookie  in '/inc/connect/CONN…

### CVE-2025-61603
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-07T15:43:15.337
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-02)

> WeGIA is a Web manager for charitable institutions. Versions 3.4.12 and below include an SQL Injection vulnerability which was identified in the /controle/control.php endpoint, specifically in the descricao parameter. This vulnerability allows attackers to execute arbitrary SQL c…

### CVE-2025-61605
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-07T15:42:02.167
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-02)

> WeGIA is an open source web manager with a focus on charitable institutions. Versions 3.4.12 and below contain an SQL Injection vulnerability which was identified in the /pet/profile_pet.php endpoint, specifically in the id_pet parameter. This vulnerability allows attackers to ex…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-02*
