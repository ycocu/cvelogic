# Daily Threat Intelligence — November 05, 2025

**Digest window (UTC):** 2025-11-05
**Generated:** 2026-06-02T07:33:44Z

## Threat brief

Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 9.9% → 28% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 9.9% → 28% · rising (+18%)).
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

### CVE-2011-1347
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 84
- **EPSS 9.9% (2025-06-27) → 28.3% (2025-11-05), Δ +18.4%**

> Unspecified vulnerability in Microsoft Internet Explorer 8 on Windows 7 allows remote attackers to bypass Protected Mode and create arbitrary files by leveraging access to a Low integrity process, as demonstrated by Stephen Fewer as the third of three chained vulnerabilities duri…

### CVE-2025-55343
**quipux quipux SQL Injection**
- **Signals:** CVSS
- **Asset:** quipux quipux
- **Attack:** SQL Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T18:52:40.673
- **CWE:** CWE-74
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-11-05)

> Quipux 4.0.1 through e1774ac allows authenticated users to conduct SQL injection attacks via busqueda/busqueda.php txt_depe_codi, busqueda/busqueda.php txt_usua_codi, anexos_lista.php radi_temp, Administracion/listas/formArea_ajax.php codDepe, Administracion/listas/formDepeHijo_a…

### CVE-2025-63601
**snipeitapp snipe-it RCE**
- **Signals:** CVSS
- **Asset:** snipeitapp snipe-it
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2025-12-01T16:15:56.437
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-11-05)

> Snipe-IT before version 8.3.3 contains a remote code execution vulnerability that allows an authenticated attacker to upload a malicious backup file containing arbitrary files and execute system commands.

### CVE-2025-20354
**cisco unified_contact_center_express**
- **Signals:** CVSS
- **Asset:** cisco unified_contact_center_express
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T15:44:35.293
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-05)

> A vulnerability in the Java Remote Method Invocation (RMI) process of Cisco Unified CCX could allow an unauthenticated, remote attacker to upload arbitrary files and execute arbitrary commands with root permissions on an affected system.

This vulnerability is due to improper a…

### CVE-2025-20358
**cisco unified_contact_center_express**
- **Signals:** CVSS
- **Asset:** cisco unified_contact_center_express
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T15:43:44.413
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-05)

> A vulnerability in the Contact Center Express (CCX) Editor application of Cisco Unified CCX could allow an unauthenticated, remote attacker to bypass authentication and obtain administrative permissions pertaining to script creation and execution.

This vulnerability is due to …

### CVE-2025-45378
**dell cloudlink privilege escalation**
- **Signals:** CVSS
- **Asset:** dell cloudlink
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T17:52:11.437
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-05)

> Dell CloudLink, versions 8.0 through 8.1.2, contain vulnerability on restricted shell. A Privileged user with known password can break into command shell of CloudLink server and gain access of shell and escalate privilege, gain unauthorized access of system.

If ssh is enabled wi…

### CVE-2025-46364
**dell cloudlink privilege escalation**
- **Signals:** CVSS
- **Asset:** dell cloudlink
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T17:53:19.650
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-05)

> Dell CloudLink, versions prior to 8.1.1, contain a vulnerability where a privileged user with known password can run CLI Escape Vulnerability to gain control of system.

### CVE-2025-56231
**tonec internet_download_manager**
- **Signals:** CVSS
- **Asset:** tonec internet_download_manager
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-07T20:58:53.493
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-05)

> Tonec Internet Download Manager 6.42.41.1 and earlier suffers from Missing SSL Certificate Validation, which allows attackers to bypass update protections.

### CVE-2025-61304
**dynatrace activegate_ping_extension Command Injection**
- **Signals:** CVSS
- **Asset:** dynatrace activegate_ping_extension
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-08T17:50:05.627
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-05)

> OS command injection vulnerability in Dynatrace ActiveGate ping extension up to 1.016 via crafted ip address.

### CVE-2025-63334
**magdesign pocketvj_control_panel_firmware RCE**
- **Signals:** CVSS
- **Asset:** magdesign pocketvj_control_panel_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T17:49:51.780
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-05)

> PocketVJ CP PocketVJ-CP-v3 pvj version 3.9.1 contains an unauthenticated remote code execution vulnerability in the submit_opacity.php component. The application fails to sanitize user input in the opacityValue POST parameter before passing it to a shell command, allowing remote …

### CVE-2025-63416
**selfbest selfbest Privilege Escalation**
- **Signals:** CVSS
- **Asset:** selfbest selfbest
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T19:47:41.363
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-05)

> ** exclusively-hosted-service ** A Stored Cross-Site Scripting (XSS) vulnerability in the chat functionality of the SelfBest platform 2023.3 allows authenticated low-privileged attackers to execute arbitrary JavaScript in the context of other users' sessions. This can be exploite…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-05*
