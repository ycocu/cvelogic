# Daily Threat Intelligence — April 11, 2026

**Digest window (UTC):** 2026-04-11
**Generated:** 2026-06-02T07:34:53Z

## Threat brief

Codesiddhant Jasmin-ransomware — exploitation likelihood rose sharply (EPSS 28% → 49% · rising (+21%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Codesiddhant Jasmin-ransomware — exploitation likelihood rose sharply (EPSS 28% → 49% · rising (+21%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2025-6095
**codesiddhant jasmin-ransomware SQL Injection**
- **Signals:** EPSS
- **Asset:** codesiddhant jasmin-ransomware
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-74
- **Risk score:** 79
- **EPSS 28.2% (2026-03-01) → 48.7% (2026-04-11), Δ +20.5%**

> A vulnerability, which was classified as critical, was found in codesiddhant Jasmin Ransomware 1.0.1. Affected is an unknown function of the file /checklogin.php. The manipulation of the argument username/password leads to sql injection. It is possible to launch the attack remote…

### CVE-2018-25083
**pull_it_project pull_it Command Injection**
- **Signals:** EPSS
- **Asset:** pull_it_project pull_it
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-02-24T20:15:31.150
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 4.3% (2026-04-09) → 17.6% (2026-04-11), Δ +13.3%**

> The pullit package before 1.4.0 for Node.js allows OS Command Injection because eval is used on an attacker-supplied Git branch name.

### CVE-2026-4149
**sonos era_300_firmware RCE**
- **Signals:** CVSS
- **Asset:** sonos era_300_firmware
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T12:26:48.387
- **CWE:** CWE-119
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-11)

> Sonos Era 300 SMB Response Out-Of-Bounds Access Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of Sonos Era 300. Authentication is not required to exploit this vulnerability.

The specific flaw e…

### CVE-2026-31845
**A reflected cross-site scripting (XSS) vulnerability exists in Rukovoditel CRM version 3.6.4 and earlier in the Zadarma telephony API end...**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-19T15:50:41.340
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-11)

> A reflected cross-site scripting (XSS) vulnerability exists in Rukovoditel CRM version 3.6.4 and earlier in the Zadarma telephony API endpoint (/api/tel/zadarma.php). The application directly reflects user-supplied input from the 'zd_echo' GET parameter into the HTTP response wit…

### CVE-2026-5058
**aws-mcp-server Command Injection Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:01:43.663
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-11)

> aws-mcp-server Command Injection Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of aws-mcp-server. Authentication is not required to exploit this vulnerability.

The specific flaw exists within t…

### CVE-2026-5059
**aws-mcp-server AWS CLI Command Injection Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:01:43.663
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-11)

> aws-mcp-server AWS CLI Command Injection Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of aws-mcp-server. Authentication is not required to exploit this vulnerability.

The specific flaw exists …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-11*
