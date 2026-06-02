# Daily Threat Intelligence — June 21, 2025

**Digest window (UTC):** 2025-06-21
**Generated:** 2026-06-02T07:32:55Z

## Threat brief

Zanematthew Zm Ajax Login \& Register — exploitation likelihood rose sharply (EPSS 33% → 46% · rising (+13%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Zanematthew Zm Ajax Login \& Register — exploitation likelihood rose sharply (EPSS 33% → 46% · rising (+13%)).
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2015-4153
**zanematthew zm_ajax_login_\&_register Directory Traversal**
- **Signals:** EPSS
- **Asset:** zanematthew zm_ajax_login_\&_register
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 32.8% (2025-05-25) → 45.9% (2025-06-21), Δ +13.1%**

> Directory traversal vulnerability in the zM Ajax Login & Register plugin before 1.1.0 for WordPress allows remote attackers to include and execute arbitrary php files via a relative path in the template parameter in a load_template action to wp-admin/admin-ajax.php.

### CVE-2025-6216
**alltena allegra Auth Bypass**
- **Signals:** CVSS
- **Asset:** alltena allegra
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-18T15:58:41.927
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-21)

> Allegra calculateTokenExpDate Password Recovery Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on affected installations of Allegra. Authentication is not required to exploit this vulnerability.

The specific flaw exists w…

### CVE-2025-1987
**bitdefender psono_client XSS**
- **Signals:** CVSS
- **Asset:** esaqa psono_client
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T18:59:12.797
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-21)

> A Cross-Site Scripting (XSS) vulnerability has been identified in Psono-Client’s handling of vault entries of type website_password and bookmark, as used in Bitdefender SecurePass. The client does not properly sanitize the URL field in these entries. As a result, an attacker can …

### CVE-2025-52556
**rfc3161-client is a Python library implementing the Time-Stamp Protocol (TSP) described in RFC 3161.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-21)

> rfc3161-client is a Python library implementing the Time-Stamp Protocol (TSP) described in RFC 3161. Prior to version 1.0.3, there is a flaw in the timestamp response signature verification logic. In particular, chain verification is performed against the TSR's embedded certifica…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-21*
