# Daily Threat Intelligence — July 01, 2025

**Digest window (UTC):** 2025-07-01
**Generated:** 2026-06-02T07:32:59Z

## Threat brief

TeleMessage TM SGNL: 2 CVEs added to CISA KEV today. · Symantec Advanced Threat Protection — exploitation likelihood rose sharply (EPSS 21% → 50% · rising (+29%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- TeleMessage TM SGNL: 2 CVEs added to CISA KEV today.
- Symantec Advanced Threat Protection — exploitation likelihood rose sharply (EPSS 21% → 50% · rising (+29%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-48927
**TeleMessage TM SGNL Initialization of a Resource with an Insecure Default Vulnerability**
- **Signals:** KEV
- **Asset:** smarsh telemessage
- **CVSS max:** 5.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:13.817
- **CWE:** CWE-1188
- **Risk score:** 88
- **KEV:** added 2025-07-01

> The TeleMessage service through 2025-05-05 configures Spring Boot Actuator with an exposed heap dump endpoint at a /heapdump URI, as exploited in the wild in May 2025.

### CVE-2016-2207
**symantec advanced_threat_protection**
- **Signals:** EPSS
- **Asset:** symantec mail_security_for_microsoft_exchange
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 21.4% (2025-04-25) → 50.2% (2025-07-01), Δ +28.9%**

> The AntiVirus Decomposer engine in Symantec Advanced Threat Protection (ATP); Symantec Data Center Security:Server (SDCS:S) 6.x through 6.6 MP1; Symantec Web Gateway; Symantec Endpoint Protection (SEP) before 12.1 RU6 MP5; Symantec Endpoint Protection (SEP) for Mac; Symantec Endp…

### CVE-2025-34054
**An unauthenticated command injection vulnerability exists in AVTECH DVR devices via Search.cgi?action=cgi_query.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-01)

> An unauthenticated command injection vulnerability exists in AVTECH DVR devices via Search.cgi?action=cgi_query. The use of wget without input sanitization allows attackers to inject shell commands through the username or queryb64str parameters, executing commands as root. Exploi…

### CVE-2016-3645
**symantec advanced_threat_protection**
- **Signals:** EPSS
- **Asset:** symantec norton_security
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-189
- **Risk score:** 86
- **EPSS 50.9% (2025-04-25) → 75.6% (2025-07-01), Δ +24.7%**

> Integer overflow in the TNEF unpacker in the AntiVirus Decomposer engine in Symantec Advanced Threat Protection (ATP); Symantec Data Center Security:Server (SDCS:S) 6.x through 6.6 MP1; Symantec Web Gateway; Symantec Endpoint Protection (SEP) before 12.1 RU6 MP5; Symantec Endpoin…

### CVE-2025-34055
**An OS command injection vulnerability exists in AVTECH DVR, NVR, and IP camera devices within the adcommand.cgi endpoint, which interface...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-01)

> An OS command injection vulnerability exists in AVTECH DVR, NVR, and IP camera devices within the adcommand.cgi endpoint, which interfaces with the ActionD daemon. Authenticated users can invoke the DoShellCmd operation, passing arbitrary input via the strCmd parameter. This inpu…

### CVE-2025-34056
**An OS command injection vulnerability exists in AVTECH IP camera, DVR, and NVR devices via the PwdGrp.cgi endpoint, which handles user an...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-01)

> An OS command injection vulnerability exists in AVTECH IP camera, DVR, and NVR devices via the PwdGrp.cgi endpoint, which handles user and group management operations. Authenticated users can supply input through the pwd or grp parameters, which are directly embedded into system …

### CVE-2025-34060
**A PHP objection injection vulnerability exists in the Monero Project’s Laravel-based forum software due to unsafe handling of untrusted i...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-01)

> A PHP objection injection vulnerability exists in the Monero Project’s Laravel-based forum software due to unsafe handling of untrusted input in the /get/image/ endpoint. The application passes a user-supplied link parameter directly to file_get_contents() without validation. MIM…

### CVE-2025-34063
**A cryptographic authentication bypass vulnerability exists in OneLogin AD Connector prior to 6.1.5 due to the exposure of a tenant’s SSO...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-01)

> A cryptographic authentication bypass vulnerability exists in OneLogin AD Connector prior to 6.1.5 due to the exposure of a tenant’s SSO JWT signing key via the /api/adc/v4/configuration endpoint. An attacker in possession of the signing key can craft valid JWT tokens impersonati…

### CVE-2025-34064
**A cloud infrastructure misconfiguration in OneLogin AD Connector results in log data being sent to a hardcoded S3 bucket (onelogin-adc-lo...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-01)

> A cloud infrastructure misconfiguration in OneLogin AD Connector results in log data being sent to a hardcoded S3 bucket (onelogin-adc-logs-production) without validating bucket ownership. An attacker who registers this unclaimed bucket can begin receiving log files from other On…

### CVE-2025-37099
**hpe insight_remote_support RCE**
- **Signals:** CVSS
- **Asset:** hpe insight_remote_support
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-10T15:33:39.910
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-01)

> A remote code execution vulnerability exists in HPE Insight Remote Support (IRS) prior to v7.15.0.646.

### CVE-2025-45006
**Improper mstatus.SUM bit retention (non-zero) in Open-Source RISC-V Processor commit f517abb violates privileged spec constraints, enabli...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-266
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-01)

> Improper mstatus.SUM bit retention (non-zero) in Open-Source RISC-V Processor commit f517abb violates privileged spec constraints, enabling potential physical memory access attacks.

### CVE-2025-48928
**TeleMessage TM SGNL Exposure of Core Dump File to an Unauthorized Control Sphere Vulnerability**
- **Signals:** KEV
- **Asset:** smarsh telemessage
- **CVSS max:** 4.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:25:52.250
- **CWE:** CWE-528
- **CWE:** CWE-552
- **Risk score:** 88
- **KEV:** added 2025-07-01

> The TeleMessage service through 2025-05-05 is based on a JSP application in which the heap content is roughly equivalent to a "core dump" in which a password previously sent over HTTP would be included in this dump, as exploited in the wild in May 2025.

### CVE-2025-52101
**linjiashop <=0.9 is vulnerable to Incorrect Access Control.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-01)

> linjiashop <=0.9 is vulnerable to Incorrect Access Control. When using the default-generated JWT authentication, attackers can bypass the authentication and retrieve the encrypted "password" and "salt". The password can then be obtained through brute-force cracking.

### CVE-2025-53104
**gluestack-ui is a library of copy-pasteable components & patterns crafted with Tailwind CSS (NativeWind).**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-01)

> gluestack-ui is a library of copy-pasteable components & patterns crafted with Tailwind CSS (NativeWind). Prior to commit e6b4271, a command injection vulnerability was discovered in the discussion-to-slack.yml GitHub Actions workflow. Untrusted discussion fields (title, body, et…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-01*
