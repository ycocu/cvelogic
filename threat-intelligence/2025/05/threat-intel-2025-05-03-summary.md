# Daily Threat Intelligence — May 03, 2025

**Digest window (UTC):** 2025-05-03
**Generated:** 2026-06-02T07:32:39Z

## Threat brief

1 material risk changes today across KEV, exploits, critical disclosures, and EPSS movers.

## Executive summary

- 1 material risk changes today across KEV, exploits, critical disclosures, and EPSS movers.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **1** |


## CVEs

### CVE-2025-3918
**The Job Listings plugin for WordPress is vulnerable to Privilege Escalation due to improper authorization within the register_action() fu...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-03)

> The Job Listings plugin for WordPress is vulnerable to Privilege Escalation due to improper authorization within the register_action() function in versions 0.1 to 0.1.1. The plugin’s registration handler reads the client-supplied $_POST['user_role'] and passes it directly to wp_i…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-03*
