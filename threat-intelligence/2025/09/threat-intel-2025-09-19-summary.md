# Daily Threat Intelligence — September 19, 2025

**Digest window (UTC):** 2025-09-19
**Generated:** 2026-06-02T07:33:26Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-34205
**vasion virtual_appliance_application SQL injection**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-02T22:15:37.383
- **CWE:** CWE-561
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host versions prior to 22.0.843 and Application prior to 20.0.1923 (VA and SaaS deployments) contains dangerous PHP dead code present in multiple Docker-hosted PHP instances. A script named /var/www/app/resetroot.php (found i…

### CVE-2025-34192
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-02T22:15:36.300
- **CWE:** CWE-1104
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host versions prior to 22.0.893 and Application versions prior to 20.0.2140 (macOS/Linux client deployments) are built against OpenSSL 1.0.2h-fips (released May 2016), which has been end-of-life since 2019 and is no longer su…

### CVE-2025-34198
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-02T22:15:36.847
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host versions prior to 22.0.951 and Application prior to 20.0.2368 (VA and SaaS deployments) contain shared, hardcoded SSH host private keys in the appliance image. The same private host keys (RSA, ECDSA, and ED25519) are pre…

### CVE-2022-4980
**General Bytes Crypto Application Server (CAS) beginning with version 20201208 prior to 20220531.38 (backport) and 20220725.22 (mainline)...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> General Bytes Crypto Application Server (CAS) beginning with version 20201208 prior to 20220531.38 (backport) and 20220725.22 (mainline) contains an authentication bypass in the admin web interface. An unauthenticated attacker could invoke the same URL used by the product's defau…

### CVE-2024-13990
**MicroWorld eScan AV's update mechanism failed to ensure authenticity and integrity of updates: update packages were delivered and accepte...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> MicroWorld eScan AV's update mechanism failed to ensure authenticity and integrity of updates: update packages were delivered and accepted without robust cryptographic verification. As a result, an on-path attacker could perform a man-in-the-middle (MitM) attack and substitute ma…

### CVE-2025-34199
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-11-25T15:15:51.467
- **CWE:** CWE-295
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host versions prior to 22.0.1049 and Application versions prior to 20.0.2786 (VA and SaaS deployments) contain insecure defaults and code patterns that disable TLS/SSL certificate verification for communications to printers a…

### CVE-2025-34203
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-02T22:15:37.257
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host versions prior to 22.0.1002 and Application versions prior to 20.0.2614 (VA and SaaS deployments) contain multiple Docker containers that include outdated, end-of-life, unsupported, or otherwise vulnerable third-party co…

### CVE-2025-34206
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-24T18:46:15.250
- **CWE:** CWE-312
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-19)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host and Application (VA and SaaS deployments) mount host configuration and secret material under /var/www/efs_storage into many Docker containers with overly-permissive filesystem permissions. Files such as secrets.env, GPG-…

### CVE-2025-48703
**CWP Control Web Panel OS Command Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** control-webpanel webpanel
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T14:07:33.610
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-19)

> CWP (aka Control Web Panel or CentOS Web Panel) before 0.9.8.1205 allows unauthenticated remote code execution via shell metacharacters in the t_total parameter in a filemanager changePerm request. A valid non-root username must be known.

### CVE-2025-57644
**accela automation_platform RCE**
- **Signals:** CVSS
- **Asset:** accela automation_platform
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T14:21:55.657
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-19)

> Accela Automation Platform 22.2.3.0.230103 contains multiple vulnerabilities in the Test Script feature. An authenticated administrative user can execute arbitrary Java code on the server, resulting in remote code execution. In addition, improper input validation allows for arbit…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-19*
