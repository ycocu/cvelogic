# Daily Threat Intelligence — February 26, 2026

**Digest window (UTC):** 2026-02-26
**Generated:** 2026-06-02T07:34:31Z

## Threat brief

Joomla Com User — exploitation likelihood rose sharply (EPSS 21% → 55% · rising (+35%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Joomla Com User — exploitation likelihood rose sharply (EPSS 21% → 55% · rising (+35%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2008-3681
**joomla com_user**
- **Signals:** EPSS
- **Asset:** joomla com_user
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-264
- **Risk score:** 82
- **EPSS 20.8% (2026-01-08) → 55.3% (2026-02-26), Δ +34.5%**

> components/com_user/models/reset.php in Joomla! 1.5 through 1.5.5 does not properly validate reset tokens, which allows remote attackers to reset the "first enabled user (lowest id)" password, typically for the administrator.

### CVE-2024-36373
**jetbrains teamcity cross-site scripting**
- **Signals:** EPSS
- **Asset:** jetbrains teamcity
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-01-27T18:41:16.957
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 37.5% (2025-12-28) → 56.2% (2026-02-26), Δ +18.8%**

> In JetBrains TeamCity before 2024.03.2 several stored XSS in untrusted builds settings were possible

### CVE-2026-27941
**openlit openlit_software_development_kit privilege escalation**
- **Signals:** CVSS
- **Asset:** openlit openlit_software_development_kit
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T20:06:09.357
- **CWE:** CWE-829
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-26)

> OpenLIT is an open source platform for AI engineering. Prior to version 1.37.1, several GitHub Actions workflows in OpenLIT's GitHub repository use the `pull_request_target` event while checking out and executing untrusted code from forked pull requests. These workflows run with …

### CVE-2004-1256
**abcmidi abcmidi Buffer Overflow**
- **Signals:** EPSS
- **Asset:** abcmidi abcmidi
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 84
- **EPSS 8.0% (2025-03-30) → 19.0% (2026-02-26), Δ +11.0%**

> Multiple buffer overflows in the (1) event_text and (2) event_specific functions in abc2midi 2004.12.04 allow remote attackers to execute arbitrary code via crafted ABC files.

### CVE-2012-1530
**adobe acrobat Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe acrobat
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 10.1% (2025-03-30) → 21.6% (2026-02-26), Δ +11.5%**

> Heap-based buffer overflow in the XSLT engine in Adobe Reader and Acrobat 9.x before 9.5.3, 10.x before 10.1.5, and 11.x before 11.0.1 allows attackers to execute arbitrary code or cause a denial of service (memory corruption) via a PDF file containing an XSL file that triggers m…

### CVE-2019-18665
**secudos domos**
- **Signals:** EPSS
- **Asset:** secudos domos
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:33:29.253
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 57.2% (2025-11-21) → 72.9% (2026-02-26), Δ +15.7%**

> The Log module in SECUDOS DOMOS before 5.6 allows local file inclusion.

### CVE-2024-36374
**jetbrains teamcity cross-site scripting**
- **Signals:** EPSS
- **Asset:** jetbrains teamcity
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-01-27T18:41:45.113
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 27.6% (2025-12-28) → 45.8% (2026-02-26), Δ +18.2%**

> In JetBrains TeamCity before 2024.03.2 stored XSS via build step settings was possible

### CVE-2025-50857
**ZenTaoPMS v18.11 through v21.6.beta is vulnerable to Directory Traversal in /module/ai/control.php.**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-26)

> ZenTaoPMS v18.11 through v21.6.beta is vulnerable to Directory Traversal in /module/ai/control.php. This allows attackers to execute arbitrary code via a crafted file upload

### CVE-2026-22207
**OpenViking through version 0.1.18, prior to commit 0251c70, contains a broken access control vulnerability that allows unauthenticated at...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-26)

> OpenViking through version 0.1.18, prior to commit 0251c70, contains a broken access control vulnerability that allows unauthenticated attackers to gain ROOT privileges when the root_api_key configuration is omitted. Attackers can send requests to protected endpoints without auth…

### CVE-2026-27804
**parseplatform parse-server**
- **Signals:** CVSS
- **Asset:** parseplatform parse-server
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T03:09:41.600
- **CWE:** CWE-327
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-26)

> Parse Server is an open source backend that can be deployed to any infrastructure that can run Node.js. Prior to versions 8.6.3 and 9.1.1-alpha.4, an unauthenticated attacker can forge a Google authentication token with `alg: "none"` to log in as any user linked to a Google accou…

### CVE-2026-27966
**langflow langflow RCE**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-28T00:54:27.840
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-26)

> Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to version 1.8.0, the CSV Agent node in Langflow hardcodes `allow_dangerous_code=True`, which automatically exposes LangChain’s Python REPL tool (`python_repl_ast`). As a result, an attacker can …

### CVE-2026-27969
**linuxfoundation vitess**
- **Signals:** CVSS
- **Asset:** linuxfoundation vitess
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T18:28:21.607
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-26)

> Vitess is a database clustering system for horizontal scaling of MySQL. Prior to versions 23.0.3 and 22.0.4, anyone with read/write access to the backup storage location (e.g. an S3 bucket) can manipulate backup manifest files so that files in the manifest — which may be files th…

### CVE-2026-28213
**evershop evershop**
- **Signals:** CVSS
- **Asset:** evershop evershop
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-28T01:18:18.080
- **CWE:** CWE-200
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-26)

> EverShop is a TypeScript-first eCommerce platform. Versions prior to 2.1.1 have a vulnerability in the "Forgot Password" functionality. When specifying a target email address, the API response returns the password reset token. This allows an attacker to take over the associated a…

### CVE-2026-28215
**hoppscotch hoppscotch**
- **Signals:** CVSS
- **Asset:** hoppscotch hoppscotch
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T15:53:07.053
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-26)

> hoppscotch is an open source API development ecosystem. Prior to version 2026.2.0, an unauthenticated attacker can overwrite the entire infrastructure configuration of a self-hosted Hoppscotch instance including OAuth provider credentials and SMTP settings  by sending a single HT…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-26*
