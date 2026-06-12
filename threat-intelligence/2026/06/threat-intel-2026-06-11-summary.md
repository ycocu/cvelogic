# Daily Threat Intelligence — June 11, 2026

**Digest window (UTC):** 2026-06-11
**Generated:** 2026-06-12T11:04:16Z

## Threat brief

Ivanti Sentry added to CISA KEV — confirmed in-the-wild exploitation. · Liferay Digital Experience Platform — exploitation likelihood rose sharply (EPSS 13% → 32% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Sentry added to CISA KEV — confirmed in-the-wild exploitation.
- Liferay Digital Experience Platform — exploitation likelihood rose sharply (EPSS 13% → 32% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2026-10520
**Ivanti Sentry OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** Ivanti Sentry
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-11T20:16:22.427
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2026-06-11

> An OS Command Injection vulnerability in Ivanti Sentry before the R10.5.2, R10.6.2 and R10.7.1 versions allows a remote unauthenticated user to achieve root-level remote code execution

### CVE-2022-42118
**liferay digital_experience_platform XSS**
- **Signals:** EPSS
- **Asset:** liferay liferay_portal
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-05-13T18:17:51.450
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 13.2% (2026-02-18) → 32.4% (2026-06-11), Δ +19.2%**

> A Cross-site scripting (XSS) vulnerability in the Portal Search module in Liferay Portal 7.1.0 through 7.4.2, and Liferay DXP 7.1 before fix pack 27, 7.2 before fix pack 15, and 7.3 before service pack 3 allows remote attackers to inject arbitrary web script or HTML via the `tag`…

### CVE-2026-45060
**ClipBucket v5 is an open source video sharing platform.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-11T23:16:23.797
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-11)

> ClipBucket v5 is an open source video sharing platform. Prior to version 5.5.3 - #129, the actions/progress_video.php endpoint is vulnerable to blind SQL injection. Any unauthenticated user can exploit the ids parameter to execute SQL queries and exfiltrate sensitive data. This i…

### CVE-2012-3576
**jquindlen wpstorecart**
- **Signals:** EPSS
- **Asset:** jquindlen wpstorecart
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-264
- **Risk score:** 86
- **EPSS 25.7% (2026-05-08) → 38.6% (2026-06-11), Δ +12.8%**

> Unrestricted file upload vulnerability in php/upload.php in the wpStoreCart plugin before 2.5.30 for WordPress allows remote attackers to execute arbitrary code by uploading a file with an executable extension, then accessing it via a direct request to the file in uploads/wpstore…

### CVE-2020-19295
**jeesns jeesns XSS**
- **Signals:** EPSS
- **Asset:** jeesns jeesns
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:09:07.167
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 8.8% (2026-05-23) → 21.7% (2026-06-11), Δ +12.9%**

> A reflected cross-site scripting (XSS) vulnerability in the /weibo/topic component of Jeesns 1.4.2 allows attackers to execute arbitrary web scripts or HTML.

### CVE-2021-37704
**phpfastcache phpfastcache**
- **Signals:** EPSS
- **Asset:** phpfastcache phpfastcache
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:15:44.877
- **CWE:** CWE-200
- **CWE:** CWE-668
- **Risk score:** 79
- **EPSS 47.8% (2026-05-10) → 61.1% (2026-06-11), Δ +13.3%**

> PhpFastCache is a high-performance backend cache system (packagist package phpfastcache/phpfastcache). In versions before 6.1.5, 7.1.2, and 8.0.7 the `phpinfo()` can be exposed if the `/vendor` is not protected from public access. This is a rare situation today since the vendor d…

### CVE-2025-54574
**squid-cache squid RCE**
- **Signals:** EPSS
- **Asset:** squid-cache squid
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-05T17:15:43.620
- **CWE:** CWE-122
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 9.3% (2026-05-28) → 19.9% (2026-06-11), Δ +10.5%**

> Squid is a caching proxy for the Web. In versions 6.3 and below, Squid is vulnerable to a heap buffer overflow and possible remote code execution attack when processing URN due to incorrect buffer management. This has been fixed in version 6.4. To work around this issue, disable …

### CVE-2026-39494
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in WBW Plugins Product Filter by WBW a...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD modified:** 2026-06-11T22:16:56.207
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-11)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in WBW Plugins Product Filter by WBW allows Blind SQL Injection.

This issue affects Product Filter by WBW: from n/a through 3.1.2.

### CVE-2026-41005
**Cloud Foundry UAA incorrectly treated XML encryption to the Service Provider (confidentiality) as a substitute for XML signatures from th...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Received
- **NVD modified:** 2026-06-11T21:16:21.807
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-11)

> Cloud Foundry UAA incorrectly treated XML encryption to the Service Provider (confidentiality) as a substitute for XML signatures from the Identity Provider (authenticity) in two SAML flows: the OAuth 2.0 SAML2 bearer grant (token endpoint) and browser SSO (ACS) when wantAssertio…

### CVE-2026-42647
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Beardev JoomSport allows Blind SQL...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD modified:** 2026-06-11T22:16:56.447
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-11)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Beardev JoomSport allows Blind SQL Injection.

This issue affects JoomSport: from n/a through 5.7.7.

### CVE-2026-42846
**ClipBucket v5 is an open source video sharing platform.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-11T23:16:23.203
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-11)

> ClipBucket v5 is an open source video sharing platform. Prior to version 5.5.3 - #140, ClipBucket's Remote Play feature allows any authenticated user to add a video by importing an external URL as the source. Some shell commands are run with the URL as a parameter. The URL is con…

### CVE-2026-45171
**Incomplete input validation and improperly configured folder permissions within Idira Privileged Session Manager (PSM) versions prior to...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD modified:** 2026-06-11T22:16:57.140
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-11)

> Incomplete input validation and improperly configured folder permissions within Idira Privileged Session Manager (PSM) versions prior to 15.0.3, 14.6.3, 14.2.5, and 14.0.5, an authenticated, low-privileged user could potentially execute arbitrary code. CyberArk Security Bulletin:…

### CVE-2026-47172
**Quest Bot is an opensource modern Discord Bot built for moderation, utilities and support.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-06-11T20:58:18.123
- **CWE:** CWE-829
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-11)

> Quest Bot is an opensource modern Discord Bot built for moderation, utilities and support. Prior to version 1.0.3, the repository has a privileged deploy workflow that runs after the unprivileged build workflow completes. The build workflow runs on pull requests, and the deploy w…

### CVE-2026-47174
**In Duck Site before version 1.0.1, the repository has a deploy workflow that runs after the build workflow completes.**
- **Signals:** CVSS
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-06-11T21:16:22.033
- **CWE:** CWE-829
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-11)

> In Duck Site before version 1.0.1, the repository has a deploy workflow that runs after the build workflow completes. The build workflow runs on pull requests, while the deploy workflow runs with package-write permissions and deployment secrets. If an attacker can make a pull req…

### CVE-2026-49060
**Incorrect Privilege Assignment vulnerability in Hippoo Mobile App for WooCommerce allows Privilege Escalation.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-11T22:16:57.737
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-11)

> Incorrect Privilege Assignment vulnerability in Hippoo Mobile App for WooCommerce allows Privilege Escalation.

This issue affects Hippoo Mobile App for WooCommerce: from n/a through 1.9.4.

### CVE-2026-49973
**Hermes WebUI before version 0.51.358 contains an improper access control vulnerability that allows unauthenticated remote attackers to hi...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-06-11T20:50:49.480
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-11)

> Hermes WebUI before version 0.51.358 contains an improper access control vulnerability that allows unauthenticated remote attackers to hijack initial setup by submitting the _set_password parameter to the settings API endpoint without any network origin restriction. Attackers on …

### CVE-2026-9290
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-06-08T14:57:14.757
- **CWE:** CWE-22
- **Risk score:** 81
- **EPSS 0.4% (2026-06-06) → 11.7% (2026-06-11), Δ +11.3%**

> The WP User Manager – User Profile Builder & Membership plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 2.9.17 via the (profile template scope) function. This makes it possible for unauthenticated attackers to include and execute a…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-11*
