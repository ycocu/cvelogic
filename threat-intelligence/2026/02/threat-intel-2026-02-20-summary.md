# Daily Threat Intelligence — February 20, 2026

**Digest window (UTC):** 2026-02-20
**Generated:** 2026-06-02T07:34:28Z

## Threat brief

Roundcube Webmail: 2 CVEs added to CISA KEV today. · Hp Openvms — exploitation likelihood rose sharply (EPSS 11% → 26% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Roundcube Webmail: 2 CVEs added to CISA KEV today.
- Hp Openvms — exploitation likelihood rose sharply (EPSS 11% → 26% · rising (+15%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2025-49113
**RoundCube Webmail Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** roundcube webmail
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T13:24:21.387
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-02-20

> Roundcube Webmail before 1.5.10 and 1.6.x before 1.6.11 allows remote code execution by authenticated users because the _from parameter in a URL is not validated in program/actions/settings/upload.php, leading to PHP Object Deserialization.

### CVE-2008-5120
**hp openvms Buffer Overflow**
- **Signals:** EPSS
- **Asset:** hp openvms
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 10.7% (2026-01-08) → 25.9% (2026-02-20), Δ +15.2%**

> Stack-based buffer overflow in the Process Software MultiNet finger service (aka FINGERD) for HP OpenVMS 8.3 allows remote attackers to execute arbitrary code via a long request string.

### CVE-2021-35402
**PROLiNK PRC2402M 20190909 before 2021-06-13 allows live_api.cgi?page=satellite_list OS command injection via shell metacharacters in the...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-20)

> PROLiNK PRC2402M 20190909 before 2021-06-13 allows live_api.cgi?page=satellite_list OS command injection via shell metacharacters in the ip parameter (for satellite_status).

### CVE-2007-1350
**novell netmail Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell netmail
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 81
- **EPSS 67.6% (2025-10-25) → 81.3% (2026-02-20), Δ +13.6%**

> Stack-based buffer overflow in webadmin.exe in Novell NetMail 3.5.2 allows remote attackers to execute arbitrary code via a long username during HTTP Basic authentication.

### CVE-2008-0947
**mit kerberos_5 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mit kerberos_5
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 32.2% (2025-11-18) → 45.1% (2026-02-20), Δ +12.9%**

> Buffer overflow in the RPC library used by libgssrpc and kadmind in MIT Kerberos 5 (krb5) 1.4 through 1.6.3 allows remote attackers to execute arbitrary code by triggering a large number of open file descriptors.

### CVE-2016-10960
**joomlaserviceprovider wsecure RCE**
- **Signals:** EPSS
- **Asset:** joomlaserviceprovider wsecure
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:45:10.557
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 57.1% (2025-12-21) → 71.1% (2026-02-20), Δ +14.0%**

> The wsecure plugin before 2.4 for WordPress has remote code execution via shell metacharacters in the wsecure-config.php publish parameter.

### CVE-2019-25441
**kostasmitroglou thesystem Command Injection**
- **Signals:** CVSS
- **Asset:** kostasmitroglou thesystem
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-12T16:12:14.967
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-20)

> thesystem 1.0 contains a command injection vulnerability that allows unauthenticated attackers to execute arbitrary system commands by submitting malicious input to the run_command endpoint. Attackers can send POST requests with shell commands in the command parameter to execute …

### CVE-2025-68461
**RoundCube Webmail Cross-site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** roundcube webmail
- **Attack:** XSS
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T13:24:12.310
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2026-02-20

> Roundcube Webmail before 1.5.12 and 1.6 before 1.6.12 is prone to a Cross-Site-Scripting (XSS) vulnerability via the animate tag in an SVG document.

### CVE-2026-2038
**gfi archiver Auth Bypass**
- **Signals:** CVSS
- **Asset:** gfi archiver
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T21:43:04.817
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-20)

> GFI Archiver MArc.Core Missing Authorization Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on affected installations of GFI Archiver. Authentication is not required to exploit this vulnerability.

The specific flaw exists…

### CVE-2026-2039
**gfi archiver Auth Bypass**
- **Signals:** CVSS
- **Asset:** gfi archiver
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T21:42:14.183
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-20)

> GFI Archiver MArc.Store Missing Authorization Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on affected installations of GFI Archiver. Authentication is not required to exploit this vulnerability.

The specific flaw exist…

### CVE-2026-2333
**owlcyberdefense opds-talon Command Injection**
- **Signals:** CVSS
- **Asset:** owlcyberdefense opds-talon
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T23:10:43.847
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-20)

> Improper Neutralization of Special Elements used in a Command ('Command Injection') in Owl opds 2.2.0.4 allows Command Injection via a crafted network request.

### CVE-2026-25896
**naturalintelligence fast-xml-parser**
- **Signals:** CVSS
- **Asset:** naturalintelligence fast-xml-parser
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-02T14:54:02.760
- **CWE:** CWE-185
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-20)

> fast-xml-parser allows users to validate XML, parse XML to JS object, or build XML from JS object without C/C++ based libraries and no callback. From 4.1.3to before 5.3.5, a dot (.) in a DOCTYPE entity name is treated as a regex wildcard during entity replacement, allowing an att…

### CVE-2026-2635
**MLflow Use of Default Password Authentication Bypass Vulnerability.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1393
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-20)

> MLflow Use of Default Password Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on affected installations of MLflow. Authentication is not required to exploit this vulnerability.

The specific flaw exists within the basic_au…

### CVE-2026-26725
**edubusinesssolutions print_shop_pro_webdesk privilege escalation**
- **Signals:** CVSS
- **Asset:** edubusinesssolutions print_shop_pro_webdesk
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-14T19:16:31.257
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-20)

> An issue in edu Business Solutions Print Shop Pro WebDesk v.18.34 (fixed in 19.76) allows a remote attacker to escalate privileges via the AccessID parameter.

### CVE-2026-26747
**monicahq monica**
- **Signals:** CVSS
- **Asset:** monicahq monica
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T02:42:23.743
- **CWE:** CWE-644
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-20)

> A Host Header Poisoning vulnerability exists in Monica 4.1.2 due to improper handling of the HTTP Host header in app/Providers/AppServiceProvider.php, combined with the default misconfiguration where the "app.force_url" is not set and default is "false". The application generates…

### CVE-2026-27112
**akuity kargo**
- **Signals:** CVSS
- **Asset:** akuity kargo
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T18:03:32.900
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-20)

> Kargo manages and automates the promotion of software artifacts. From 1.7.0 to before v1.7.8, v1.8.11, and v1.9.3, the batch resource creation endpoints of both Kargo's legacy gRPC API and newer REST API accept multi-document YAML payloads. Specially crafted payloads can manifest…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-20*
