# Daily Threat Intelligence — March 11, 2026

**Digest window (UTC):** 2026-03-11
**Generated:** 2026-06-02T07:34:37Z

## Threat brief

N8n added to CISA KEV — confirmed in-the-wild exploitation. · Devbunch Master Elements — exploitation likelihood rose sharply (EPSS 55% → 68% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- N8n added to CISA KEV — confirmed in-the-wild exploitation.
- Devbunch Master Elements — exploitation likelihood rose sharply (EPSS 55% → 68% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-68613
**n8n Improper Control of Dynamically-Managed Code Resources Vulnerability**
- **Signals:** KEV
- **Asset:** n8n n8n
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T19:40:09.533
- **CWE:** CWE-913
- **CWE:** CWE-913
- **Risk score:** 88
- **KEV:** added 2026-03-11

> n8n is an open source workflow automation platform. Versions starting with 0.211.0 and prior to 1.120.4, 1.121.1, and 1.122.0 contain a critical Remote Code Execution (RCE) vulnerability in their workflow expression evaluation system. Under certain conditions, expressions supplie…

### CVE-2022-0693
**devbunch master_elements SQL Injection**
- **Signals:** EPSS
- **Asset:** devbunch master_elements
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:39:12.033
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 55.5% (2026-03-10) → 68.2% (2026-03-11), Δ +12.8%**

> The Master Elements WordPress plugin through 8.0 does not validate and escape the meta_ids parameter of its remove_post_meta_condition AJAX action (available to both unauthenticated and authenticated users) before using it in a SQL statement, leading to an unauthenticated SQL Inj…

### CVE-2026-31957
**himmelblau-idm himmelblau**
- **Signals:** CVSS
- **Asset:** himmelblau-idm himmelblau
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-16T19:39:37.913
- **CWE:** CWE-1188
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-11)

> Himmelblau is an interoperability suite for Microsoft Azure Entra ID and Intune. From 3.0.0 to before 3.1.0, if Himmelblau is deployed without a configured tenant domain in himmelblau.conf, authentication is not tenant-scoped. In this mode, Himmelblau can accept authentication at…

### CVE-2021-20086
**jquery-bbq_project jquery-bbq**
- **Signals:** EPSS
- **Asset:** jquery-bbq_project jquery-bbq
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T22:15:47.437
- **CWE:** CWE-1321
- **Risk score:** 83
- **EPSS 38.4% (2026-03-10) → 49.6% (2026-03-11), Δ +11.1%**

> Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution') in jquery-bbq 1.2.1 allows a malicious user to inject properties into Object.prototype.

### CVE-2025-66956
**Insecure Access Control in Contact Plan, E-Mail, SMS and Fax components in Asseco SEE Live 2.0 allows remote attackers to access and exec...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T19:18:46.690
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-11)

> Insecure Access Control in Contact Plan, E-Mail, SMS and Fax components in Asseco SEE Live 2.0 allows remote attackers to access and execute attachments via a computable URL.

### CVE-2025-70024
**An issue pertaining to CWE-89: Improper Neutralization of Special Elements used in an SQL Command was discovered in benkeen generatedata...**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T19:18:46.690
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-11)

> An issue pertaining to CWE-89: Improper Neutralization of Special Elements used in an SQL Command was discovered in benkeen generatedata 4.0.14.

### CVE-2025-70041
**An issue pertaining to CWE-259: Use of Hard-coded Password was discovered in oslabs-beta ThermaKube master.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-10T14:16:46.260
- **CWE:** CWE-259
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-11)

> An issue pertaining to CWE-259: Use of Hard-coded Password was discovered in oslabs-beta ThermaKube master.

### CVE-2026-27591
**wintercms winter**
- **Signals:** CVSS
- **Asset:** wintercms winter
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T17:37:17.370
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-11)

> Winter is a free, open-source content management system (CMS) based on the Laravel PHP framework. Prior to 1.0.477, 1.1.12, and 1.2.12, Winter CMS allowed authenticated backend users to escalate their accounts level of access to the system by modifying the roles / permissions ass…

### CVE-2026-31896
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T20:05:49.723
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-11)

> WeGIA is a web manager for charitable institutions. Prior to version 3.6.6, a critical SQL injection vulnerability exists in the WeGIA application. The remover_produto_ocultar.php script uses extract($_REQUEST) to populate local variables and then directly concatenates these vari…

### CVE-2026-31976
**xygeni xygeni-action**
- **Signals:** CVSS
- **Asset:** xygeni xygeni-action
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-16T19:02:12.933
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-11)

> xygeni-action is the GitHub Action for Xygeni Scanner. On March 3, 2026, an attacker with access to compromised credentials created a series of pull requests (#46, #47, #48) injecting obfuscated shell code into action.yml. The PRs were blocked by branch protection rules and never…

### CVE-2026-32096
**useplunk plunk SSRF**
- **Signals:** CVSS
- **Asset:** useplunk plunk
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-16T17:00:18.470
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-11)

> Plunk is an open-source email platform built on top of AWS SES. Prior to 0.7.0, a Server-Side Request Forgery (SSRF) vulnerability existed in the SNS webhook handler. An unauthenticated attacker could send a crafted request that caused the server to make an arbitrary outbound HTT…

### CVE-2026-32136
**adguard adguardhome**
- **Signals:** CVSS
- **Asset:** adguard adguardhome
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T20:19:00.987
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-11)

> AdGuard Home is a network-wide software for blocking ads and tracking. Prior to 0.107.73, an unauthenticated remote attacker can bypass all authentication in AdGuardHome by sending an HTTP/1.1 request that requests an upgrade to HTTP/2 cleartext (h2c). Once the upgrade is accepte…

### CVE-2026-3916
**google chrome memory safety**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T15:43:05.787
- **CWE:** CWE-125
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-11)

> Out of bounds read in Web Speech in Google Chrome prior to 146.0.7680.71 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-11*
