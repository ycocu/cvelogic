# Daily Threat Intelligence — February 10, 2026

**Digest window (UTC):** 2026-02-10
**Generated:** 2026-06-02T07:34:23Z

## Threat brief

Microsoft Windows: 6 CVEs added to CISA KEV today. · Sun Solaris — exploitation likelihood rose sharply (EPSS 6.8% → 20% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows: 6 CVEs added to CISA KEV today.
- Sun Solaris — exploitation likelihood rose sharply (EPSS 6.8% → 20% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 6 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2026-21519
**Microsoft Windows Type Confusion Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T16:13:16.180
- **CWE:** CWE-843
- **Risk score:** 88
- **KEV:** added 2026-02-10

> Access of resource using incompatible type ('type confusion') in Desktop Window Manager allows an authorized attacker to elevate privileges locally.

### CVE-1999-0493
**sun solaris**
- **Signals:** EPSS
- **Asset:** sun solaris
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 6.8% (2025-03-30) → 20.1% (2026-02-10), Δ +13.4%**

> rpc.statd allows remote attackers to forward RPC calls to the local operating system via the SM_MON and SM_NOTIFY commands, which in turn could be used to remotely exploit other bugs such as in automountd.

### CVE-2026-26009
**Catalyst is a platform built for enterprise game server hosts, game communities, and billing panel integrations.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-10)

> Catalyst is a platform built for enterprise game server hosts, game communities, and billing panel integrations. Install scripts defined in server templates execute directly on the host operating system as root via bash -c, with no sandboxing or containerization. Any user with te…

### CVE-2018-5430
**TIBCO JasperReports Server Information Disclosure Vulnerability**
- **Signals:** EPSS
- **Asset:** tibco jasperreports_server
- **Attack:** Info Disclosure
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T18:58:46.060
- **CWE:** CWE-22
- **CWE:** CWE-200
- **Risk score:** 81
- **EPSS 31.4% (2026-02-03) → 41.4% (2026-02-10), Δ +10.0%**

> The Spring web flows of TIBCO Software Inc.'s TIBCO JasperReports Server, TIBCO JasperReports Server Community Edition, TIBCO JasperReports Server for ActiveMatrix BPM, TIBCO Jaspersoft for AWS with Multi-Tenancy, and TIBCO Jaspersoft Reporting and Analytics for AWS contain a vul…

### CVE-2025-11242
**Server-Side Request Forgery (SSRF) vulnerability in Teknolist Computer Systems Software Publishing Industry and Trade Inc.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-10)

> Server-Side Request Forgery (SSRF) vulnerability in Teknolist Computer Systems Software Publishing Industry and Trade Inc. Okulistik allows Server Side Request Forgery.This issue affects Okulistik: through 21102025.

### CVE-2026-0509
**sap netweaver_as_abap_kernel privilege escalation**
- **Signals:** CVSS
- **Asset:** sap netweaver_as_abap_kernel
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T16:04:59.500
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-02-10)

> SAP NetWeaver Application Server ABAP and ABAP Platform allows an authenticated, low-privileged user to perform background Remote Function Calls without the required S_RFC authorization in certain cases. This can result in a high impact on integrity and availability, and no impac…

### CVE-2026-1774
**CASL Ability, versions 2.4.0 through 6.7.4, contains a prototype pollution vulnerability.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-10)

> CASL Ability, versions 2.4.0 through 6.7.4, contains a prototype pollution vulnerability.

### CVE-2026-2095
**flowring agentflow Auth Bypass**
- **Signals:** CVSS
- **Asset:** flowring agentflow
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:53:19.297
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-10)

> Agentflow developed by Flowring has an Authentication Bypass vulnerability, allowing unauthenticated remote attackers to exploit a specific functionality to obtain arbitrary user authentication token and log into the system as any user.

### CVE-2026-2096
**flowring agentflow**
- **Signals:** CVSS
- **Asset:** flowring agentflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:52:16.510
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-10)

> Agentflow developed by Flowring has a Missing Authentication vulnerability, allowing unauthenticated remote attackers to read, modify, and delete database contents by using a specific functionality.

### CVE-2026-21510
**Microsoft Windows Shell Protection Mechanism Failure Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T16:13:25.603
- **CWE:** CWE-693
- **Risk score:** 88
- **KEV:** added 2026-02-10

> Protection mechanism failure in Windows Shell allows an unauthorized attacker to bypass a security feature over a network.

### CVE-2026-21513
**Microsoft MSHTML Framework Protection Mechanism Failure Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T13:28:07.120
- **CWE:** CWE-693
- **Risk score:** 88
- **KEV:** added 2026-02-10

> Protection mechanism failure in MSHTML Framework allows an unauthorized attacker to bypass a security feature over a network.

### CVE-2026-21514
**Microsoft Office Word Reliance on Untrusted Inputs in a Security Decision Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft 365_apps
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T15:47:04.413
- **CWE:** CWE-807
- **Risk score:** 88
- **KEV:** added 2026-02-10

> Reliance on untrusted inputs in a security decision in Microsoft Office Word allows an unauthorized attacker to bypass a security feature locally.

### CVE-2026-21525
**Microsoft Windows NULL Pointer Dereference Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 6.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T13:28:00.137
- **CWE:** CWE-476
- **Risk score:** 88
- **KEV:** added 2026-02-10

> Null pointer dereference in Windows Remote Access Connection Manager allows an unauthorized attacker to deny service locally.

### CVE-2026-21531
**microsoft azure_conversation_authoring_client_library Deserialization**
- **Signals:** CVSS
- **Asset:** microsoft azure_conversation_authoring_client_library
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T15:49:25.373
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-10)

> Deserialization of untrusted data in Azure SDK allows an unauthorized attacker to execute code over a network.

### CVE-2026-21533
**Microsoft Windows Improper Privilege Management Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T13:27:43.870
- **CWE:** CWE-269
- **Risk score:** 88
- **KEV:** added 2026-02-10

> Improper privilege management in Windows Remote Desktop allows an authorized attacker to elevate privileges locally.

### CVE-2026-23906
**apache druid**
- **Signals:** CVSS
- **Asset:** apache druid
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-12T05:16:55.753
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-10)

> Affected Products and Versions
  *  Apache Druid
  *  Affected Versions: 0.17.0 through 35.x (all versions prior to 36.0.0)
  *  Prerequisites:  *  druid-basic-security extension enabled
  *  LDAP authenticator configured
  *  Underlying LDAP server permits anonymous bind        …

### CVE-2026-25728
**oxygenz clipbucket**
- **Signals:** CVSS
- **Asset:** oxygenz clipbucket
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T15:02:02.293
- **CWE:** CWE-367
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-10)

> ClipBucket v5 is an open source video sharing platform. Prior to 5.5.3 - #40, a Time-of-Check to Time-of-Use (TOCTOU) race condition vulnerability exists in ClipBucket's avatar and background image upload functionality. The application moves uploaded files to a web-accessible loc…

### CVE-2026-25993
**evershop evershop SQL injection**
- **Signals:** CVSS
- **Asset:** evershop evershop
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T18:03:12.130
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-10)

> EverShop is a TypeScript-first eCommerce platform. During category update and deletion event handling, the application embeds
path / request_path values—derived from the url_key stored in the database—into SQL statements via string concatenation and passes them to execute(). As a…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-10*
