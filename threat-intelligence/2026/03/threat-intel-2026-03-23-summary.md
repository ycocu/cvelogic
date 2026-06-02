# Daily Threat Intelligence — March 23, 2026

**Digest window (UTC):** 2026-03-23
**Generated:** 2026-06-02T07:34:44Z

## Threat brief

Inductiveautomation Ignition — exploitation likelihood rose sharply (EPSS 25% → 42% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Inductiveautomation Ignition — exploitation likelihood rose sharply (EPSS 25% → 42% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2022-35871
**inductiveautomation ignition**
- **Signals:** EPSS
- **Asset:** inductiveautomation ignition
- **CVSS max:** 8.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:11:50.997
- **CWE:** CWE-306
- **Risk score:** 83
- **EPSS 25.2% (2025-12-27) → 42.0% (2026-03-23), Δ +16.8%**

> This vulnerability allows remote attackers to execute arbitrary code on affected installations of Inductive Automation Ignition 8.1.15 (b2022030114). Authentication is not required to exploit this vulnerability. The specific flaw exists within the authenticateAdSso method. The is…

### CVE-2023-28434
**MinIO Security Feature Bypass Vulnerability**
- **Signals:** EPSS
- **Asset:** minio minio
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T15:03:51.180
- **CWE:** CWE-269
- **Risk score:** 84
- **EPSS 39.0% (2026-02-14) → 52.1% (2026-03-23), Δ +13.1%**

> Minio is a Multi-Cloud Object Storage framework. Prior to RELEASE.2023-03-20T20-16-18Z, an attacker can use crafted requests to bypass metadata bucket name checking and put an object into any bucket while processing `PostPolicyBucket`. To carry out this attack, the attacker requi…

### CVE-2026-33634
**Aquasecurity Trivy Embedded Malicious Code Vulnerability**
- **Signals:** CVSS
- **Asset:** aquasec setup-trivy
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T18:50:38.270
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-23)

> Trivy is a security scanner. On March 19, 2026, a threat actor used compromised credentials to publish a malicious Trivy v0.69.4 release, force-push 76 of 77 version tags in `aquasecurity/trivy-action` to credential-stealing malware, and replace all 7 tags in `aquasecurity/setup-…

### CVE-2006-4379
**ipswitch imail_plus Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ipswitch imail_plus
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 71.2% (2026-02-11) → 83.9% (2026-03-23), Δ +12.7%**

> Stack-based buffer overflow in the SMTP Daemon in Ipswitch Collaboration 2006 Suite Premium and Standard Editions, IMail, IMail Plus, and IMail Secure allows remote attackers to execute arbitrary code via a long string located after an '@' character and before a ':' character.

### CVE-2025-60949
**csprousers csweb**
- **Signals:** CVSS
- **Asset:** csprousers csweb
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T21:06:59.330
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-23)

> Census CSWeb 8.0.1 allows "app/config" to be reachable via HTTP in some deployments. A remote, unauthenticated attacker could send requests to configuration files and obtain leaked secrets. Fixed in 8.1.0 alpha.

### CVE-2026-0898
**An arbitrary file-write vulnerability in Pega Browser Extension (PBE) affects Pega Robot Studio developers who are automating Google Chro...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-24T15:54:09.400
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-23)

> An arbitrary file-write vulnerability in Pega Browser Extension (PBE) affects Pega Robot Studio developers who are automating Google Chrome and Microsoft Edge using either version 22.1 or R25. This vulnerability does not affect Robot Runtime users. A bad actor could create a webs…

### CVE-2026-2298
**Improper Neutralization of Argument Delimiters in a Command ('Argument Injection') vulnerability in Salesforce Marketing Cloud Engagement...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-24T15:54:09.400
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-23)

> Improper Neutralization of Argument Delimiters in a Command ('Argument Injection') vulnerability in Salesforce Marketing Cloud Engagement allows Web Services Protocol Manipulation. This issue affects Marketing Cloud Engagement: before January 30th, 2026.

### CVE-2026-3055
**Citrix NetScaler Out-of-Bounds Read Vulnerability**
- **Signals:** CVSS
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T13:18:14.213
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-23)

> Insufficient input validation in NetScaler ADC and NetScaler Gateway when configured as a SAML IDP leading to memory overread

### CVE-2026-30849
**mantisbt mantisbt Auth Bypass**
- **Signals:** CVSS
- **Asset:** mantisbt mantisbt
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T13:59:26.947
- **CWE:** CWE-305
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-23)

> Mantis Bug Tracker (MantisBT) is an open source issue tracker. Versions prior to 2.28.1 running on MySQL family databases are affected by an authentication bypass vulnerability in the SOAP API, as a result of an improper type checking on the password parameter. Other database bac…

### CVE-2026-33502
**wwbn avideo**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-24T17:01:02.653
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-23)

> WWBN AVideo is an open source video platform. In versions up to and including 26.0, an unauthenticated server-side request forgery vulnerability in `plugin/Live/test.php` allows any remote user to make the AVideo server send HTTP requests to arbitrary URLs. This can be used to pr…

### CVE-2026-33716
**wwbn avideo**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T15:05:05.063
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-23)

> WWBN AVideo is an open source video platform. In versions up to and including 26.0, the standalone live stream control endpoint at `plugin/Live/standAloneFiles/control.json.php` accepts a user-supplied `streamerURL` parameter that overrides where the server sends token verificati…

### CVE-2026-4404
**Use of hard coded credentials in GoHarbor Harbor version 2.15.0 and below, allows attackers to use the default password and gain access t...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-24T16:16:36.507
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-23)

> Use of hard coded credentials in GoHarbor Harbor version 2.15.0 and below, allows attackers to use the default password and gain access to the web UI.

### CVE-2026-4681
**A critical remote code execution (RCE) vulnerability has been reported in PTC Windchill and PTC FlexPLM.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-24T15:53:48.067
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-23)

> A critical remote code execution (RCE) vulnerability has been reported in PTC Windchill and PTC FlexPLM. The vulnerability may be exploited through the deserialization of untrusted data.

This issue affects Windchill PDMLink: 11.0 M030, 11.1 M020, 11.2.1.0, 12.0.2.0, 12.1.2.0, 13…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-23*
