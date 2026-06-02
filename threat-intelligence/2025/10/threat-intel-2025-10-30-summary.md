# Daily Threat Intelligence — October 30, 2025

**Digest window (UTC):** 2025-10-30
**Generated:** 2026-06-02T07:33:42Z

## Threat brief

Broadcom VMware Aria Operations And VMware Tools added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Broadcom VMware Aria Operations And VMware Tools added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-24893
**XWiki Platform Eval Injection Vulnerability**
- **Signals:** KEV
- **Asset:** xwiki xwiki
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T13:17:09.460
- **CWE:** CWE-95
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2025-10-30

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any guest can perform arbitrary remote code execution through a request to `SolrSearch`. This impacts the confidentiality, integrity and availability of the whole XWiki instal…

### CVE-2024-14003
**nagios nagios_xi RCE**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:09:37.150
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R1.2 are vulnerable to remote code execution (RCE) through its NRDP (Nagios Remote Data Processor) server plugins. Insufficient validation of inbound NRDP request parameters allows crafted input to reach command execution paths, enabling attackers …

### CVE-2024-14005
**nagios nagios_xi Command Injection**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:36:47.133
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R1.2 contain a command injection vulnerability in the Docker Wizard. Insufficient validation of user-supplied input in the wizard allows an authenticated administrator to inject shell metacharacters that are incorporated into backend command invoca…

### CVE-2024-13996
**nagios nagios_xi**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:17:23.587
- **CWE:** CWE-613
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R1.1.3 did not invalidate all other active sessions for a user when that user's password was changed. As a result, any pre-existing sessions (including those potentially controlled by an attacker) remained valid after a credential update. This insu…

### CVE-2024-14008
**nagios nagios_xi privilege escalation**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T18:17:48.463
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R1.3.2 contain a remote command execution vulnerability in the WinRM Configuration Wizard. Insufficient validation of user-supplied input allows an authenticated administrator to inject shell metacharacters that are incorporated into backend comman…

### CVE-2024-14009
**nagios nagios_xi Privilege Escalation**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T18:17:08.733
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R1.0.1 contain a privilege escalation vulnerability in the System Profile component. The System Profile feature is an administrative diagnostic/configuration capability. Due to improper access controls and unsafe handling of exported/imported profi…

### CVE-2025-34134
**nagios nagios_xi RCE**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T18:17:25.503
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R1.4.2 contain a remote code execution vulnerability in the Business Process Intelligence (BPI) component. Insufficient validation and sanitization of administrator-controlled BPI configuration parameters (notably bpi_logfile and bpi_configfile) al…

### CVE-2025-34274
**nagios log_server privilege escalation**
- **Signals:** CVSS
- **Asset:** nagios log_server
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:27:58.503
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-30)

> Nagios Log Server versions prior to 2024R2.0.3 contain an execution with unnecessary privileges vulnerability as it runs its embedded Logstash process as the root user. If an attacker is able to compromise the Logstash process - for example by exploiting an insecure plugin, pipel…

### CVE-2025-34277
**nagios log_server RCE**
- **Signals:** CVSS
- **Asset:** nagios log_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:27:31.010
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios Log Server versions prior to 2024R1.3.1 contain a code injection vulnerability where malformed dashboard ID values are not properly validated before being forwarded to an internal API. An attacker able to supply crafted dashboard ID values can cause the system to execute a…

### CVE-2025-34284
**nagios nagios_xi Command Injection**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T18:14:12.050
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2024R2 contain a command injection vulnerability in the WinRM plugin. Insufficient validation of user-supplied parameters allows an authenticated administrator to inject shell metacharacters that are incorporated into backend command invocations. Succe…

### CVE-2025-34286
**nagios nagios_xi RCE**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T18:13:04.890
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-30)

> Nagios XI versions prior to 2026R1  contain a remote code execution vulnerability in the Core Config Manager (CCM) Run Check command. Insufficient validation/escaping of parameters used to build backend command lines allows an authenticated administrator to inject shell metachara…

### CVE-2025-41244
**Broadcom VMware Aria Operations and VMware Tools Privilege Defined with Unsafe Actions Vulnerability**
- **Signals:** KEV
- **Asset:** vmware aria_operations
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:58:13.620
- **CWE:** CWE-267
- **Risk score:** 88
- **KEV:** added 2025-10-30

> VMware Aria Operations and VMware Tools contain a local privilege escalation vulnerability. A malicious local actor with non-administrative privileges having access to a VM with VMware Tools installed and managed by Aria Operations with SDMP enabled may exploit this vulnerability…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-30*
