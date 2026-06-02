# Daily Threat Intelligence — July 31, 2025

**Digest window (UTC):** 2025-07-31
**Generated:** 2026-06-02T07:33:09Z

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

### CVE-2014-125121
**Array Networks vAPV (version 8.3.2.17) and vxAG (version 9.2.0.34) appliances are affected by a privilege escalation vulnerability caused...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-732
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-31)

> Array Networks vAPV (version 8.3.2.17) and vxAG (version 9.2.0.34) appliances are affected by a privilege escalation vulnerability caused by a combination of hardcoded SSH credentials (or SSH private key) and insecure permissions on a startup script. The devices ship with a defau…

### CVE-2014-125123
**An unauthenticated SQL injection vulnerability exists in the Kloxo web hosting control panel (developed by LXCenter) prior to version 6.1...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-31)

> An unauthenticated SQL injection vulnerability exists in the Kloxo web hosting control panel (developed by LXCenter) prior to version 6.1.12. The flaw resides in the login-name parameter passed to lbin/webcommand.php, which fails to properly sanitize input, allowing an attacker t…

### CVE-2014-125124
**An unauthenticated remote command execution vulnerability exists in Pandora FMS versions up to and including 5.0RC1 via the Anyterm web i...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-31)

> An unauthenticated remote command execution vulnerability exists in Pandora FMS versions up to and including 5.0RC1 via the Anyterm web interface, which listens on TCP port 8023. The anyterm-module endpoint accepts unsanitized user input via the p parameter and directly injects i…

### CVE-2013-10043
**A vulnerability exists in OAstium VoIP PBX astium-confweb-2.1-25399 and earlier, where improper input validation in the logon.php script...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-07-31)

> A vulnerability exists in OAstium VoIP PBX astium-confweb-2.1-25399 and earlier, where improper input validation in the logon.php script allows an attacker to bypass authentication via SQL injection. Once authenticated as an administrator, the attacker can upload arbitrary PHP co…

### CVE-2014-125126
**An unrestricted file upload vulnerability exists in Simple E-Document versions 3.0 to 3.1 that allows an unauthenticated attacker to bypa...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-07-31)

> An unrestricted file upload vulnerability exists in Simple E-Document versions 3.0 to 3.1 that allows an unauthenticated attacker to bypass authentication by sending a specific cookie header (access=3) with HTTP requests. The application’s upload mechanism fails to restrict file …

### CVE-2025-26062
**intelbras rx_1500_firmware**
- **Signals:** CVSS
- **Asset:** intelbras rx_1500_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:00.380
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-31)

> An access control issue in Intelbras RX1500 v2.2.9 and RX3000 v1.0.11 allows unauthenticated attackers to access the router's settings file and obtain potentially sensitive information from the current settings.

### CVE-2025-26063
**intelbras rx_1500_firmware**
- **Signals:** CVSS
- **Asset:** intelbras rx_1500_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:00.540
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-31)

> An issue in Intelbras RX1500 v2.2.9 and RX3000 v1.0.11 allows unauthenticated attackers to execute arbitrary code via injecting a crafted payload into the ESSID name when creating a network.

### CVE-2025-50475
**An OS command injection vulnerability exists in Russound MBX-PRE-D67F firmware version 3.1.6, allowing unauthenticated attackers to execu...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-31)

> An OS command injection vulnerability exists in Russound MBX-PRE-D67F firmware version 3.1.6, allowing unauthenticated attackers to execute arbitrary commands as root via crafted input to the hostname parameter in network configuration requests. This vulnerability stems from impr…

### CVE-2025-8286
**The affected products expose an unauthenticated Telnet-based command line interface that could allow an attacker to modify hardware confi...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-31)

> The affected products expose an unauthenticated Telnet-based command line interface that could allow an attacker to modify hardware configurations, manipulate data, or factory reset the device.

### CVE-2025-8426
**marvell qconvergeconsole Directory Traversal**
- **Signals:** CVSS
- **Asset:** marvell qconvergeconsole
- **Attack:** Directory Traversal
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-06T16:50:11.847
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-31)

> Marvell QConvergeConsole compressConfigFiles Directory Traversal Information Disclosure and Denial-of-Service Vulnerability. This vulnerability allows remote attackers to disclose sensitive information or to create a denial-of-service condition on affected installations of Marvel…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-31*
