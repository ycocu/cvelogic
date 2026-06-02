# Daily Threat Intelligence — September 05, 2025

**Digest window (UTC):** 2025-09-05
**Generated:** 2026-06-02T07:33:22Z

## Threat brief

9 new critical disclosures — review patch status on exposed services.

## Executive summary

- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2025-58367
**DeepDiff is a project focused on Deep Difference and search of any Python data.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-915
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-05)

> DeepDiff is a project focused on Deep Difference and search of any Python data. Versions 5.0.0 through 8.6.0 are vulnerable to class pollution via the Delta class constructor, and when combined with a gadget available in DeltaDiff, it can lead to Denial of Service and Remote Code…

### CVE-2025-58371
**roocode roo_code RCE**
- **Signals:** CVSS
- **Asset:** roocode roo_code
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-15T18:08:40.367
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-05)

> Roo Code is an AI-powered autonomous coding agent that lives in users' editors. In versions 3.26.6 and below, a Github workflow used unsanitized pull request metadata in a privileged context, allowing an attacker to craft malicious input and achieve Remote Code Execution (RCE) on…

### CVE-2025-49401
**Incorrect Privilege Assignment vulnerability in axiomthemes smart SEO smartSEO allows Privilege Escalation.This issue affects smart SEO:...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:36.970
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-05)

> Incorrect Privilege Assignment vulnerability in axiomthemes smart SEO smartSEO allows Privilege Escalation.This issue affects smart SEO: from n/a through <= 4.0.

### CVE-2025-35451
**multicam-systems ba12-n_firmware**
- **Signals:** CVSS
- **Asset:** ptzoptics pt12x-sdi-xx-g2_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T15:33:46.617
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-05)

> PTZOptics and possibly other ValueHD-based pan-tilt-zoom cameras use hard-coded, default administrative credentials. The passwords can readily be cracked. Many cameras have SSH or telnet listening on all interfaces. The passwords cannot be changed by the user, nor can the SSH or …

### CVE-2025-35452
**multicam-systems ba12-n_firmware**
- **Signals:** CVSS
- **Asset:** ptzoptics pt12x-sdi-xx-g2_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-23T17:08:13.470
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-09-05)

> PTZOptics and possibly other ValueHD-based pan-tilt-zoom cameras use default, shared credentials for the administrative web interface.

### CVE-2025-55037
**Improper neutralization of special elements used in an OS command ('OS Command Injection') issue exists in TkEasyGUI versions prior to v1...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-05)

> Improper neutralization of special elements used in an OS command ('OS Command Injection') issue exists in TkEasyGUI versions prior to v1.0.22. If this vulnerability is exploited, an arbitrary OS command may be executed by a remote unauthenticated attacker if the settings are con…

### CVE-2025-58366
**Onyxia is a data science environment for kubernetes.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-05)

> Onyxia is a data science environment for kubernetes. In versions 4.6.0 through 4.8.0, Onyxia-API leaked the credentials of private helm repositories in the public (unauthenticated) /public/catalogs endpoint.vOnly instances using private helm repositories (i.e setting username & p…

### CVE-2025-58628
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in kamleshyadav Miraculous miraculous...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:33:29.333
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-05)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in kamleshyadav Miraculous miraculous allows Blind SQL Injection.This issue affects Miraculous: from n/a through < 2.0.9.

### CVE-2025-58819
**Unrestricted Upload of File with Dangerous Type vulnerability in CreedAlly Bulk Featured Image bulk-featured-image allows Upload a Web Sh...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:33:41.753
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-05)

> Unrestricted Upload of File with Dangerous Type vulnerability in CreedAlly Bulk Featured Image bulk-featured-image allows Upload a Web Shell to a Web Server.This issue affects Bulk Featured Image: from n/a through <= 1.2.4.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-05*
