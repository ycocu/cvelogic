# Daily Threat Intelligence — June 27, 2026

**Digest window (US Eastern, NVD):** 2026-06-27
**Generated:** 2026-06-29T10:33:12Z

## Threat brief

2 material risk changes today across KEV, exploits, critical disclosures, and EPSS movers.

## Executive summary

- 2 material risk changes today across KEV, exploits, critical disclosures, and EPSS movers.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **2** |


## CVEs

### CVE-2026-12415
**The Invoice Generator plugin for WordPress is vulnerable to privilege escalation due to a missing capability check on the pravel_invoice_...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-27
- **NVD modified:** 2026-06-27
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-27)

> The Invoice Generator plugin for WordPress is vulnerable to privilege escalation due to a missing capability check on the pravel_invoice_edit_account() AJAX action in versions up to, and including, 1.0.0. The handler is exposed via wp_ajax_nopriv_pravel_invoice_edit_account, acce…

### CVE-2026-58053
**Gitea act_runner with the Docker backend (through act 0.262.0) passes a workflow's container.options string to the Docker job container's...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Received
- **NVD published:** 2026-06-27
- **NVD modified:** 2026-06-27
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-27)

> Gitea act_runner with the Docker backend (through act 0.262.0) passes a workflow's container.options string to the Docker job container's HostConfig and, when configured with privileged: false, forces only the Privileged flag off while merging options such as --pid=host, --cap-ad…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-27*
