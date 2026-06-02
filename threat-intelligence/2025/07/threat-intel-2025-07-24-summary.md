# Daily Threat Intelligence — July 24, 2025

**Digest window (UTC):** 2025-07-24
**Generated:** 2026-06-02T07:33:06Z

## Threat brief

Foxmail Email Server — exploitation likelihood rose sharply (EPSS 8.1% → 26% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Foxmail Email Server — exploitation likelihood rose sharply (EPSS 8.1% → 26% · rising (+18%)).
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

### CVE-2005-0339
**foxmail foxmail_email_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** foxmail foxmail_email_server
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 8.1% (2025-03-30) → 25.8% (2025-07-24), Δ +17.7%**

> Buffer overflow in Foxmail 2.0 allows remote attackers to cause a denial of service and possibly execute arbitrary code via a long MAIL FROM command.

### CVE-2025-5243
**Unrestricted Upload of File with Dangerous Type, Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-24)

> Unrestricted Upload of File with Dangerous Type, Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in SMG Software Information Portal allows Code Injection, Upload a Web Shell to a Web Server, Code Inclusion.This issue affect…

### CVE-2025-4784
**moderec tourtella SQL Injection**
- **Signals:** CVSS
- **Asset:** moderec tourtella
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-28T14:43:17.137
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-24)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Moderec Tourtella allows SQL Injection.This issue affects Tourtella: before 26.05.2025.

### CVE-2025-32429
**xwiki xwiki SQL injection**
- **Signals:** CVSS
- **Asset:** xwiki xwiki
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-03T17:43:28.937
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-24)

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. In versions 9.4-rc-1 through 16.10.5 and 17.0.0-rc-1 through 17.2.2, it's possible for anyone to inject SQL using the parameter sort of the getdeleteddocuments.vm. It's inject…

### CVE-2025-41420
**wwbn avideo XSS**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:48.500
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-07-24)

> A cross-site scripting (xss) vulnerability exists in the userLogin cancelUri parameter functionality of WWBN AVideo 14.4 and dev master commit 8a8954ff. A specially crafted HTTP request can lead to arbitrary Javascript execution. An attacker can get a user to visit a webpage to t…

### CVE-2025-46410
**wwbn avideo XSS**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:19:05.250
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-07-24)

> A cross-site scripting (xss) vulnerability exists in the managerPlaylists PlaylistOwnerUsersId parameter functionality of WWBN AVideo 14.4 and dev master commit 8a8954ff. A specially crafted HTTP request can lead to arbitrary Javascript execution. An attacker can get a user to vi…

### CVE-2025-4822
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Bayraktar Solar Energies ScadaWatt...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-24)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Bayraktar Solar Energies ScadaWatt Otopilot allows SQL Injection.This issue affects ScadaWatt Otopilot: before 27.05.2025.

### CVE-2025-50128
**wwbn avideo XSS**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:19:12.463
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-07-24)

> A cross-site scripting (xss) vulnerability exists in the videoNotFound 404ErrorMsg parameter functionality of WWBN AVideo 14.4 and dev master commit 8a8954ff. A specially crafted HTTP request can lead to arbitrary Javascript execution. An attacker can get a user to visit a webpag…

### CVE-2025-53084
**wwbn avideo XSS**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **Attack:** XSS
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:19:13.567
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-24)

> A cross-site scripting (xss) vulnerability exists in the videosList page parameter functionality of WWBN AVideo 14.4 and dev master commit 8a8954ff. A specially crafted HTTP request can lead to arbitrary Javascript execution. An attacker can get a user to visit a webpage to trigg…

### CVE-2025-54369
**Node-SAML is a SAML library not dependent on any frameworks that runs in Node.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-87
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-24)

> Node-SAML is a SAML library not dependent on any frameworks that runs in Node. In versions 5.0.1 and below, Node-SAML loads the assertion from the (unsigned) original response document. This is different than the parts that are verified when checking signature. This allows an att…

### CVE-2025-6260
**The embedded web server on the thermostat listed version ranges contain a vulnerability that allows unauthenticated attackers, either on...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-24)

> The embedded web server on the thermostat listed version ranges contain a vulnerability that allows unauthenticated attackers, either on the local area network or from the Internet via a router with port forwarding set up, to gain direct access to the thermostat's embedded web se…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-24*
