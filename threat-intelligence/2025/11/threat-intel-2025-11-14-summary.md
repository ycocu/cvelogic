# Daily Threat Intelligence — November 14, 2025

**Digest window (UTC):** 2025-11-14
**Generated:** 2026-06-02T07:33:47Z

## Threat brief

Fortinet FortiWeb added to CISA KEV — confirmed in-the-wild exploitation. · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet FortiWeb added to CISA KEV — confirmed in-the-wild exploitation.
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2025-64446
**Fortinet FortiWeb Path Traversal Vulnerability**
- **Signals:** KEV, CVSS
- **Asset:** fortinet fortiweb
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T18:27:33.730
- **CWE:** CWE-23
- **Risk score:** 97
- **KEV:** added 2025-11-14
- **CVSS critical:** 9.8 (disclosed 2025-11-14)

> A relative path traversal vulnerability in Fortinet FortiWeb 8.0.0 through 8.0.1, FortiWeb 7.6.0 through 7.6.4, FortiWeb 7.4.0 through 7.4.9, FortiWeb 7.2.0 through 7.2.11, FortiWeb 7.0.0 through 7.0.11 may allow an attacker to execute administrative commands on the system via cr…

### CVE-2025-54339
**desktopalert pingalert_application_server privilege escalation**
- **Signals:** CVSS
- **Asset:** desktopalert pingalert_application_server
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-19T21:30:20.750
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-14)

> An Incorrect Access Control vulnerability was found in the Application Server of Desktop Alert PingAlert version 6.1.0.11 to 6.1.1.2 exploitable remotely for Escalation of Privileges.

### CVE-2025-54343
**desktopalert pingalert_application_server privilege escalation**
- **Signals:** CVSS
- **Asset:** desktopalert pingalert_application_server
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-19T21:27:52.237
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-11-14)

> An Incorrect Access Control vulnerability was found in the Application Server of Desktop Alert PingAlert version 6.1.0.11 to 6.1.1.2 exploitable remotely for Escalation of Privileges.

### CVE-2021-4470
**TG8 Firewall contains a pre-authentication remote code execution vulnerability in the runphpcmd.php endpoint.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-14)

> TG8 Firewall contains a pre-authentication remote code execution vulnerability in the runphpcmd.php endpoint. The syscmd POST parameter is passed directly to a system command without validation and executed with root privileges. A remote, unauthenticated attacker can supply craft…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-14*
