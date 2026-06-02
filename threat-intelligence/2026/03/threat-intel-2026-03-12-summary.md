# Daily Threat Intelligence — March 12, 2026

**Digest window (UTC):** 2026-03-12
**Generated:** 2026-06-02T07:34:37Z

## Threat brief

74cms — exploitation likelihood rose sharply (EPSS 48% → 62% · rising (+14%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 74cms — exploitation likelihood rose sharply (EPSS 48% → 62% · rising (+14%)).
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

### CVE-2020-29279
**74cms 74cms RCE**
- **Signals:** EPSS
- **Asset:** 74cms 74cms
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:23:51.460
- **Risk score:** 86
- **EPSS 47.9% (2026-01-19) → 62.2% (2026-03-12), Δ +14.3%**

> PHP remote file inclusion in the assign_resume_tpl method in Application/Common/Controller/BaseController.class.php in 74CMS before 6.0.48 allows remote code execution.

### CVE-2026-3611
**The Honeywell IQ4x building management controller, exposes its full web-based HMI without authentication in its factory-default configura...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-13T20:06:54.667
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-12)

> The Honeywell IQ4x building management controller, exposes its full web-based HMI without authentication in its factory-default configuration. With no user module configured, security is disabled by design and the system operates under a System Guest (level 100) context, granting…

### CVE-2025-70245
**dlink dir-513_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-513_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-13T19:53:53.807
- **CWE:** CWE-787
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-12)

> Stack buffer overflow vulnerability in D-Link DIR-513 v1.10 via the curTime parameter to goform/formSetWizardSelectMode.

### CVE-2026-26793
**gl-inet ar300m16_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** gl-inet ar300m16_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T16:02:22.993
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-12)

> GL-iNet GL-AR300M16 v4.3.11 was discovered to contain a command injection vulnerability via the set_config function. This vulnerability allows attackers to execute arbitrary commands via a crafted input.

### CVE-2026-26795
**gl-inet ar300m16_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** gl-inet ar300m16_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-16T14:18:27.577
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-12)

> GL-iNet GL-AR300M16 v4.3.11 was discovered to contain a command injection vulnerability via the module parameter in the M.get_system_log function. This vulnerability allows attackers to execute arbitrary commands via a crafted input.

### CVE-2026-28252
**trane tracer_concierge**
- **Signals:** CVSS
- **Asset:** trane tracer_sc_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-27T16:22:41.620
- **CWE:** CWE-327
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-12)

> A Use of a Broken or Risky Cryptographic Algorithm vulnerability in Trane Tracer SC, Tracer SC+, and Tracer Concierge could allow an attacker to bypass authentication and gain root-level access to the device.

### CVE-2026-32137
**dataease dataease SQL injection**
- **Signals:** CVSS
- **Asset:** dataease dataease
- **Attack:** SQL injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T16:03:02.080
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-12)

> Dataease is an open source data visualization analysis tool. Prior to 2.10.20, The table parameter for /de2api/datasource/previewData is directly concatenated into the SQL statement without any filtering or parameterization. Since tableName is a user-controllable string, attacker…

### CVE-2026-32140
**dataease dataease RCE**
- **Signals:** CVSS
- **Asset:** dataease dataease
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-03-13T19:54:40.230
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-12)

> Dataease is an open source data visualization analysis tool. Prior to 2.10.20, By controlling the IniFile parameter, an attacker can force the JDBC driver to load an attacker-controlled configuration file. This configuration file can inject dangerous JDBC properties, leading to r…

### CVE-2026-32242
**parseplatform parse-server**
- **Signals:** CVSS
- **Asset:** parseplatform parse-server
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T16:57:55.797
- **CWE:** CWE-362
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-12)

> Parse Server is an open source backend that can be deployed to any infrastructure that can run Node.js. Prior to 9.6.0-alpha.11 and 8.6.37, Parse Server's built-in OAuth2 auth adapter exports a singleton instance that is reused directly across all OAuth2 provider configurations. …

### CVE-2026-32248
**parseplatform parse-server**
- **Signals:** CVSS
- **Asset:** parseplatform parse-server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T19:00:34.193
- **CWE:** CWE-943
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-12)

> Parse Server is an open source backend that can be deployed to any infrastructure that can run Node.js. Prior to 9.6.0-alpha.12 and 8.6.38, an unauthenticated attacker can take over any user account that was created with an authentication provider that does not validate the forma…

### CVE-2026-32251
**tolgee tolgee**
- **Signals:** CVSS
- **Asset:** tolgee tolgee
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T15:57:42.580
- **CWE:** CWE-611
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-12)

> Tolgee is an open-source localization platform. Prior to 3.166.3, the XML parsers used for importing Android XML resources (.xml) and .resx files don't disable external entity processing. An authenticated user who can import translation files into a project can exploit this to re…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-12*
