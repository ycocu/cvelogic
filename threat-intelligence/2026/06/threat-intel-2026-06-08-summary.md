# Daily Threat Intelligence — June 08, 2026

**Digest window (UTC):** 2026-06-08
**Generated:** 2026-06-09T12:39:22Z

## Threat brief

Check Point Security Gateway added to CISA KEV — confirmed in-the-wild exploitation. · Open-emr Openemr: public exploit or PoC linked (privilege escalation) · Adobe Photoshop — exploitation likelihood rose sharply (EPSS 5.8% → 22% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Check Point Security Gateway added to CISA KEV — confirmed in-the-wild exploitation.
- Open-emr Openemr: public exploit or PoC linked (privilege escalation)
- Adobe Photoshop — exploitation likelihood rose sharply (EPSS 5.8% → 22% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **22** |


## CVEs

### CVE-2026-50751
**Check Point Security Gateway Improper Authentication Vulnerability**
- **Signals:** KEV, CVSS
- **Asset:** Check Point Security Gateway
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-08T21:16:49.373
- **CWE:** CWE-287
- **Risk score:** 96
- **KEV:** added 2026-06-08
- **CVSS critical:** 9.3 (disclosed 2026-06-08)

> A logic flow weakness in Remote Access and Mobile Access certificate validation in deprecated IKEv1 key exchange allows an unauthenticated remote attacker to bypass user authentication and establish a remote access VPN connection without a valid user password.

### CVE-2026-24849
**open-emr openemr privilege escalation**
- **Signals:** EXP
- **Asset:** open-emr openemr
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T16:56:53.200
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-06-08

> OpenEMR is a free and open source electronic health records and medical practice management application. Prior to version 7.0.4, the `disposeDocument()` method in `EtherFaxActions.php` allows authenticated users to read arbitrary files from the server filesystem. Any authenticate…

### CVE-2021-28549
**adobe photoshop RCE**
- **Signals:** EPSS
- **Asset:** adobe photoshop
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:59:49.730
- **CWE:** CWE-120
- **Risk score:** 83
- **EPSS 5.8% (2026-05-03) → 22.5% (2026-06-08), Δ +16.7%**

> Adobe Photoshop versions 21.2.6 (and earlier) and 22.3 (and earlier) are affected by a Buffer Overflow vulnerability when parsing a specially crafted JSX file. An unauthenticated attacker could leverage this vulnerability to achieve arbitrary code execution in the context of the …

### CVE-2007-5355
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **CVSS max:** 5.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 80
- **EPSS 27.4% (2026-04-12) → 39.8% (2026-06-08), Δ +12.4%**

> The Web Proxy Auto-Discovery (WPAD) feature in Microsoft Internet Explorer 6 and 7, when a primary DNS suffix with three or more components is configured, resolves an unqualified wpad hostname in a second-level domain outside this configured DNS domain, which allows remote WPAD s…

### CVE-2008-2292
**net-snmp net-snmp Buffer Overflow**
- **Signals:** EPSS
- **Asset:** net-snmp net-snmp
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 80
- **EPSS 15.2% (2026-03-07) → 26.6% (2026-06-08), Δ +11.3%**

> Buffer overflow in the __snprint_value function in snmp_get in Net-SNMP 5.1.4, 5.2.4, and 5.4.1, as used in SNMP.xs for Perl, allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a large OCTETSTRING in an attribute value pair (AVP).

### CVE-2016-0749
**debian debian_linux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** opensuse leap
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 16.0% (2026-03-03) → 29.4% (2026-06-08), Δ +13.5%**

> The smartcard interaction in SPICE allows remote attackers to cause a denial of service (QEMU-KVM process crash) or possibly execute arbitrary code via vectors related to connecting to a guest VM, which triggers a heap-based buffer overflow.

### CVE-2019-25141
**wp-ecommerce easy_wp_smtp privilege escalation**
- **Signals:** EPSS
- **Asset:** wp-ecommerce easy_wp_smtp
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-08T18:17:03.533
- **CWE:** CWE-862
- **CWE:** CWE-862
- **Risk score:** 86
- **EPSS 62.9% (2026-02-15) → 77.9% (2026-06-08), Δ +15.0%**

> The Easy WP SMTP plugin for WordPress is vulnerable to authorization bypass in versions up to, and including, 1.3.9. This is due to missing capability checks on the admin_init() function, in addition to insufficient input validation. This makes it possible for unauthenticated att…

### CVE-2021-46319
**dlink dir-846_firmware RCE**
- **Signals:** EPSS
- **Asset:** dlink dir-846_firmware
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:33:52.443
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 21.0% (2026-02-28) → 32.5% (2026-06-08), Δ +11.5%**

> Remote Code Execution (RCE) vulnerability exists in D-Link Router DIR-846 DIR846A1_FW100A43.bin and DIR846enFW100A53DLA-Retail.bin. Malicious users can use this vulnerability to use "\ " or backticks to bypass the shell metacharacters in the ssid0 or ssid1 parameters to execute a…

### CVE-2024-53900
**mongoosejs mongoose**
- **Signals:** EPSS
- **Asset:** mongoosejs mongoose
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-01T18:24:19.460
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 52.2% (2026-05-21) → 64.2% (2026-06-08), Δ +12.0%**

> Mongoose before 8.8.3 can improperly use $where in match, leading to search injection.

### CVE-2024-58349
**WordPress Theme Travelscape 1.0.3 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicio...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-08T14:59:44.750
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-08)

> WordPress Theme Travelscape 1.0.3 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious files by exploiting insufficient validation in the theme's upload functionality. Attackers can upload arbitrary files to the theme directory…

### CVE-2025-25256
**fortinet fortisiem Command Injection**
- **Signals:** EPSS
- **Asset:** fortinet fortisiem
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-08-15T18:15:27.583
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 39.0% (2026-05-31) → 51.3% (2026-06-08), Δ +12.3%**

> An improper neutralization of special elements used in an OS command ('OS Command Injection') vulnerability [CWE-78] in Fortinet FortiSIEM version 7.3.0 through 7.3.1, 7.2.0 through 7.2.5, 7.1.0 through 7.1.7, 7.0.0 through 7.0.3 and before 6.7.9 allows an unauthenticated attacke…

### CVE-2025-50165
**microsoft windows_11_24h2**
- **Signals:** EPSS
- **Asset:** microsoft windows_11_24h2
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:05:02.893
- **CWE:** CWE-822
- **Risk score:** 85
- **EPSS 11.2% (2026-05-29) → 23.5% (2026-06-08), Δ +12.3%**

> Untrusted pointer dereference in Microsoft Graphics Component allows an unauthorized attacker to execute code over a network.

### CVE-2025-53722
**microsoft windows_10_1507**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-18T16:57:34.573
- **CWE:** CWE-400
- **Risk score:** 82
- **EPSS 22.6% (2026-05-29) → 37.3% (2026-06-08), Δ +14.8%**

> Uncontrolled resource consumption in Windows Remote Desktop Services allows an unauthorized attacker to deny service over a network.

### CVE-2026-11499
**A vulnerability was determined in Tenda HG7HG9 and HG10 300001138_en_xpon.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-06-08T14:57:14.757
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-08)

> A vulnerability was determined in Tenda HG7HG9 and HG10 300001138_en_xpon. This affects the function formDOMAINBLK of the file /boaform/formDOMAINBLK. Executing a manipulation of the argument blkDomain can lead to stack-based buffer overflow. The attack may be performed from remo…

### CVE-2026-25555
**OpenBullet2 through version 0.3.2 contains an authentication bypass vulnerability in the API key authentication middleware that allows un...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-08T17:16:41.080
- **CWE:** CWE-305
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-08)

> OpenBullet2 through version 0.3.2 contains an authentication bypass vulnerability in the API key authentication middleware that allows unauthenticated attackers to gain admin access by supplying an empty X-Api-Key header value. Attackers can exploit the middleware's comparison of…

### CVE-2026-39910
**STACKIT IaaS API contains a missing authorization check vulnerability that allows authenticated, low-privileged attackers to escalate pri...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-08T17:16:42.613
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-08)

> STACKIT IaaS API contains a missing authorization check vulnerability that allows authenticated, low-privileged attackers to escalate privileges to full organization compromise by attaching arbitrary service accounts to virtual machines they control. Attackers can exploit the unv…

### CVE-2026-41448
**AdGuard Home, when started with the --glinet flag, contains an authentication bypass vulnerability that allows unauthenticated attackers...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD modified:** 2026-06-08T17:16:42.847
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-08)

> AdGuard Home, when started with the --glinet flag, contains an authentication bypass vulnerability that allows unauthenticated attackers to gain full admin access by supplying a path traversal sequence in the Admin-Token cookie, exploiting unsanitized string concatenation in the …

### CVE-2026-42271
**BerriAI LiteLLM Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** litellm litellm
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-08T18:16:33.407
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2026-06-08

> LiteLLM is a proxy server (AI Gateway) to call LLM APIs in OpenAI (or native) format. From version 1.74.2 to before version 1.83.7, two endpoints used to preview an MCP server before saving it — POST /mcp-rest/test/connection and POST /mcp-rest/test/tools/list — accepted a full s…

### CVE-2026-44631
**Buffer Underwrite vulnerability in Apache HTTP Server on crafted regular expressions in the configuration.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-08T23:17:24.763
- **CWE:** CWE-124
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-08)

> Buffer Underwrite vulnerability in Apache HTTP Server on crafted regular expressions in the configuration.

This issue affects Apache HTTP Server: from 2.4.0 through 2.4.67.

Users are recommended to upgrade to version 2.4.68, which fixes the issue.

### CVE-2026-46442
**Flowise is a drag & drop user interface to build a customized large language model flow.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD modified:** 2026-06-08T16:16:41.347
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-08)

> Flowise is a drag & drop user interface to build a customized large language model flow. Prior to version 3.1.2, POST /api/v1/node-custom-function lacks route-level authorization, allowing any authenticated user or API key to submit arbitrary JavaScript to the Custom JS Function …

### CVE-2026-47430
**## Summary The iOS implementation of `cordova-plugin-inappbrowser` passes the `id` field from a `WKScriptMessage` body to `commandDelegat...**
- **Signals:** CVSS
- **CVSS max:** 9.5
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-08T14:57:49.490
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-08)

> ## Summary

The iOS implementation of `cordova-plugin-inappbrowser` passes the `id` field from a `WKScriptMessage` body to `commandDelegate sendPluginResult:callbackId:` with no format validation (`CDVWKInAppBrowser.m:560–574`). Any web content loaded inside the InAppBrowser can …

### CVE-2026-52778
**YesWiki is a wiki system written in PHP.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-08T19:16:46.683
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-08)

> YesWiki is a wiki system written in PHP. Prior to version 4.6.6, an unsafe execution vulnerability exists in the Bazar form field calculator (CalcField.php) of YesWiki. The application attempts to sanitize user-defined mathematical formulas using a complex recursive regular expre…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-08*
