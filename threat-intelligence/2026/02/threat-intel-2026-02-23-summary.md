# Daily Threat Intelligence — February 23, 2026

**Digest window (UTC):** 2026-02-23
**Generated:** 2026-06-02T07:34:30Z

## Threat brief

Tesla Model 3 Web Interface — exploitation likelihood rose sharply (EPSS 16% → 33% · rising (+17%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Tesla Model 3 Web Interface — exploitation likelihood rose sharply (EPSS 16% → 33% · rising (+17%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2020-10558
**tesla model_3_web_interface DoS**
- **Signals:** EPSS
- **Asset:** tesla model_3_web_interface
- **Attack:** DoS
- **CVSS max:** 7.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:55:34.670
- **Risk score:** 81
- **EPSS 16.1% (2026-01-18) → 33.5% (2026-02-23), Δ +17.4%**

> The driving interface of Tesla Model 3 vehicles in any release before 2020.4.10 allows Denial of Service to occur due to improper process separation, which allows attackers to disable the speedometer, web browser, climate controls, turn signal visual and sounds, navigation, autop…

### CVE-2009-4932
**mpesch3.de1 1by1 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mpesch3.de1 1by1
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 10.5% (2026-02-17) → 27.8% (2026-02-23), Δ +17.2%**

> Stack-based buffer overflow in 1by1 1.67 (aka 1.6.7.0) allows remote attackers to cause a denial of service (application crash) or possibly execute arbitrary code via a long string in a .m3u playlist file.

### CVE-2026-3062
**google chrome memory safety**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-25T18:23:42.200
- **CWE:** CWE-125
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-23)

> Out of bounds read and write in Tint in Google Chrome on Mac prior to 145.0.7632.116 allowed a remote attacker to perform out of bounds memory access via a crafted HTML page. (Chromium security severity: High)

### CVE-2021-24215
**wpruby controlled_admin_access**
- **Signals:** EPSS
- **Asset:** wpruby controlled_admin_access
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:52:36.693
- **CWE:** CWE-284
- **CWE:** CWE-425
- **Risk score:** 86
- **EPSS 37.4% (2025-11-21) → 54.6% (2026-02-23), Δ +17.2%**

> An Improper Access Control vulnerability was discovered in the Controlled Admin Access WordPress plugin before 1.5.2. Uncontrolled access to the website customization functionality and global CMS settings, like /wp-admin/customization.php and /wp-admin/options.php, can lead to a …

### CVE-2021-24235
**boostifythemes goto XSS**
- **Signals:** EPSS
- **Asset:** boostifythemes goto
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:52:39.400
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 26.7% (2025-11-21) → 43.8% (2026-02-23), Δ +17.1%**

> The Goto WordPress theme before 2.0 does not sanitise the keywords and start_date GET parameter on its Tour List page, leading to an unauthenticated reflected Cross-Site Scripting issue.

### CVE-2025-41002
**SQL injection vulnerability in Infoticketing.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-23)

> SQL injection vulnerability in Infoticketing. This vulnerability allows
 an unauthenticated attacker to retrieve, create, update, and delete the
 database by sending a POST request using the 'code' parameter in '/components/cart/cartApplyDiscount.php'.

### CVE-2025-70043
**An issue pertaining to CWE-295: Improper Certificate Validation was discovered in Ayms node-To master.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-23)

> An issue pertaining to CWE-295: Improper Certificate Validation was discovered in Ayms node-To master. The application disables TLS/SSL certificate validation by setting 'rejectUnauthorized': false in TLS socket options

### CVE-2025-70327
**totolink x5000r_firmware**
- **Signals:** CVSS
- **Asset:** totolink x5000r_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T03:06:04.013
- **CWE:** CWE-88
- **CWE:** CWE-400
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-23)

> TOTOLINK X5000R v9.1.0cu_2415_B20250515 contains an argument injection vulnerability in the setDiagnosisCfg handler of the /usr/sbin/lighttpd executable. The ip parameter is retrieved via websGetVar and passed to a ping command through CsteSystem without validating if the input s…

### CVE-2026-23552
**apache camel**
- **Signals:** CVSS
- **Asset:** apache camel
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T16:46:16.643
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-23)

> Cross-Realm Token Acceptance Bypass in KeycloakSecurityPolicy Apache Camel Keycloak component. 

The Camel-Keycloak KeycloakSecurityPolicy does not validate the iss (issuer) claim of JWT tokens against the configured realm. A token issued by one Keycloak realm is silently accepte…

### CVE-2026-23693
**ElementsKit Elementor Addons – Advanced Widgets & Templates Addons for Elementor (elementskit-lite) WordPress plugin versions prior to 3....**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-23)

> ElementsKit Elementor Addons – Advanced Widgets & Templates Addons for Elementor (elementskit-lite) WordPress plugin versions prior to 3.7.9 expose the REST endpoint /wp-json/elementskit/v1/widget/mailchimp/subscribe without authentication. The endpoint accepts client-supplied Ma…

### CVE-2026-24494
**SQL Injection vulnerability in the /api/integrations/getintegrations endpoint of Order Up Online Ordering System 1.0 allows an unauthenti...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-23)

> SQL Injection vulnerability in the /api/integrations/getintegrations endpoint of Order Up Online Ordering System 1.0 allows an unauthenticated attacker to access sensitive backend database data via a crafted store_id parameter in a POST request.

### CVE-2026-2588
**timlegge crypt::nacl::sodium**
- **Signals:** CVSS
- **Asset:** timlegge crypt\
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T02:23:33.820
- **CWE:** CWE-190
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-23)

> Crypt::NaCl::Sodium versions through 2.001 for Perl has an integer overflow flaw on 32-bit systems.

Sodium.xs casts a STRLEN (size_t) to unsigned long long when passing a length pointer to libsodium functions.  On 32-bit systems size_t is typically 32-bits while an unsigned long…

### CVE-2026-3061
**google chrome memory safety**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-02-25T18:23:42.007
- **CWE:** CWE-125
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-23)

> Out of bounds read in Media in Google Chrome prior to 145.0.7632.116 allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-23*
