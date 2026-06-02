# Daily Threat Intelligence — August 30, 2025

**Digest window (UTC):** 2025-08-30
**Generated:** 2026-06-02T07:33:19Z

## Threat brief

Php Blue Dragon — exploitation likelihood rose sharply (EPSS 11% → 21% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Php Blue Dragon — exploitation likelihood rose sharply (EPSS 11% → 21% · rising (+11%)).
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

### CVE-2006-4962
**blue_dragon php_blue_dragon Directory Traversal**
- **Signals:** EPSS
- **Asset:** blue_dragon php_blue_dragon
- **Attack:** Directory Traversal
- **CVSS max:** 6.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 10.7% (2025-07-04) → 21.3% (2025-08-30), Δ +10.6%**

> Directory traversal vulnerability in pbd_engine.php in Php Blue Dragon 2.9.1 and earlier allows remote attackers to read and execute arbitrary local files via a .. (dot dot) sequence via the phpExt parameter, as demonstrated by executing PHP code in a log file.

### CVE-2025-54945
**sun.net ehrd_ctms**
- **Signals:** CVSS
- **Asset:** sun.net ehrd_ctms
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-01-30T04:15:49.563
- **CWE:** CWE-73
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-30)

> An external control of file name or path vulnerability in SUNNET Corporate Training Management System before 10.11 allows remote attackers to execute arbitrary system commands via a malicious file by controlling the destination file path.

### CVE-2009-20011
**ContentKeeper Web Appliance (now maintained by Impero Software) versions prior to 125.10 are vulnerable to remote command execution due t...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-30)

> ContentKeeper Web Appliance (now maintained by Impero Software) versions prior to 125.10 are vulnerable to remote command execution due to insecure handling of file uploads via the mimencode CGI utility. The vulnerability allows unauthenticated attackers to upload and execute arb…

### CVE-2009-20009
**Belkin Bulldog Plus version 4.0.2 build 1219 contains a stack-based buffer overflow vulnerability in its web service authentication handler.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> Belkin Bulldog Plus version 4.0.2 build 1219 contains a stack-based buffer overflow vulnerability in its web service authentication handler. When a specially crafted HTTP request is sent with an oversized Authorization header, the application fails to properly validate the input …

### CVE-2009-20010
**Dogfood CRM version 2.0.10 contains a remote command execution vulnerability in the spell.php script used by its mail subsystem.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> Dogfood CRM version 2.0.10 contains a remote command execution vulnerability in the spell.php script used by its mail subsystem. The vulnerability arises from unsanitized user input passed via a POST request to the data parameter, which is processed by the underlying shell withou…

### CVE-2010-10016
**BS.Player version 2.57 (build 1051) contains a vulnerability in its playlist import functionality.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-30)

> BS.Player version 2.57 (build 1051) contains a vulnerability in its playlist import functionality. When processing .m3u files, the application fails to properly validate the length of playlist entries, resulting in a buffer overflow condition. This flaw occurs during parsing of l…

### CVE-2011-10032
**Sunway ForceControl version 6.1 SP3 and earlier contains a stack-based buffer overflow vulnerability in the SNMP NetDBServer service, whi...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> Sunway ForceControl version 6.1 SP3 and earlier contains a stack-based buffer overflow vulnerability in the SNMP NetDBServer service, which listens on TCP port 2001. The flaw is triggered when the service receives a specially crafted packet using opcode 0x57 with an overly long p…

### CVE-2025-34164
**A heap-based buffer overflow vulnerability in NetSupport Manager 14.x versions prior to 14.12.0000 allows a remote, unauthenticated attac...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> A heap-based buffer overflow vulnerability in NetSupport Manager 14.x versions prior to 14.12.0000 allows a remote, unauthenticated attacker to cause a denial of service (DoS) or execute arbitrary code.

### CVE-2025-54942
**sun.net ehrd_ctms**
- **Signals:** CVSS
- **Asset:** sun.net ehrd_ctms
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-30T05:16:12.113
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> A missing authentication for critical function vulnerability in SUNNET Corporate Training Management System before 10.11 allows remote attackers to access deployment functionality without prior authentication.

### CVE-2025-54943
**sun.net ehrd_ctms privilege escalation**
- **Signals:** CVSS
- **Asset:** sun.net ehrd_ctms
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-30T04:15:48.950
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> A missing authorization vulnerability in SUNNET Corporate Training Management System before 10.11 allows remote attackers to perform unauthorized application deployment due to the absence of proper access control checks.

### CVE-2025-54946
**sun.net ehrd_ctms SQL Injection**
- **Signals:** CVSS
- **Asset:** sun.net ehrd_ctms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-30T04:15:49.860
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-30)

> A SQL injection vulnerability in SUNNET Corporate Training Management System before 10.11 allows remote attackers to execute arbitrary SQL commands.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-30*
