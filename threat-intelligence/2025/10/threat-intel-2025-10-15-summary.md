# Daily Threat Intelligence — October 15, 2025

**Digest window (UTC):** 2025-10-15
**Generated:** 2026-06-02T07:33:36Z

## Threat brief

Adobe Experience Manager (AEM) Forms added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · Redhat Foreman — exploitation likelihood rose sharply (EPSS 22% → 47% · rising (+25%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Experience Manager (AEM) Forms added to CISA KEV — confirmed in-the-wild exploitation.
- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
- Redhat Foreman — exploitation likelihood rose sharply (EPSS 22% → 47% · rising (+25%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-54253
**Adobe Experience Manager Forms Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** adobe experience_manager_forms
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T14:51:25.423
- **CWE:** CWE-863
- **Risk score:** 88
- **KEV:** added 2025-10-15

> Adobe Experience Manager versions 6.5.23 and earlier are affected by a Misconfiguration vulnerability that could result in arbitrary code execution. An attacker could leverage this vulnerability to bypass security mechanisms and execute code. Exploitation of this issue does not r…

### CVE-2013-2113
**redhat foreman privilege escalation**
- **Signals:** EPSS
- **Asset:** redhat openstack
- **Attack:** privilege escalation
- **CVSS max:** 6.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-264
- **Risk score:** 80
- **EPSS 22.1% (2025-09-20) → 47.4% (2025-10-15), Δ +25.4%**

> The create method in app/controllers/users_controller.rb in Foreman before 1.2.0-RC2 allows remote authenticated users with permissions to create or edit other users to gain privileges by (1) changing the admin flag or (2) assigning an arbitrary role.

### CVE-2025-11832
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T17:49:51.360
- **CWE:** CWE-770
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-15)

> Allocation of Resources Without Limits or Throttling vulnerability in Azure Access Technology BLU-IC2, Azure Access Technology BLU-IC4 allows Flooding.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2004-0733
**ollydbg ollydbg DoS**
- **Signals:** EPSS
- **Asset:** ollydbg ollydbg
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 19.3% (2025-03-30) → 44.3% (2025-10-15), Δ +24.9%**

> Format string vulnerability in OllyDbg 1.10 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via format string specifiers that are directly provided to the OutputDebugString function call.

### CVE-2013-2121
**redhat foreman**
- **Signals:** EPSS
- **Asset:** redhat openstack
- **CVSS max:** 6.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-94
- **Risk score:** 80
- **EPSS 44.3% (2025-09-20) → 60.9% (2025-10-15), Δ +16.6%**

> Eval injection vulnerability in the create method in the Bookmarks controller in Foreman before 1.2.0-RC2 allows remote authenticated users with permissions to create bookmarks to execute arbitrary code via a controller name attribute.

### CVE-2023-7304
**Ruijie RG-UAC Application Management Gateway contains a command injection vulnerability via the 'nmc_sync.php' interface.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-15)

> Ruijie RG-UAC Application Management Gateway contains a command injection vulnerability via the 'nmc_sync.php' interface. An unauthenticated attacker able to reach the affected endpoint can inject shell commands via crafted request data, causing the application to execute arbitra…

### CVE-2023-7305
**SmartBI V8, V9, and V10 contain an unrestricted file upload vulnerability via the RMIServlet request handling logic.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-15)

> SmartBI V8, V9, and V10 contain an unrestricted file upload vulnerability via the RMIServlet request handling logic. Under certain configurations or usage patterns, attackers can send specially crafted requests that cause the application to perform sensitive operations or execute…

### CVE-2023-7311
**BYTEVALUE Intelligent Flow Control Router contains a command injection vulnerability via the /goform/webRead/open endpoint.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-15)

> BYTEVALUE Intelligent Flow Control Router contains a command injection vulnerability via the /goform/webRead/open endpoint. The `path` parameter is not properly validated and is echoed into a shell context, allowing an attacker to inject and execute arbitrary shell commands on th…

### CVE-2025-10041
**The Flex QR Code Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in thesave_qr...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-15)

> The Flex QR Code Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in thesave_qr_code_to_db() function in all versions up to, and including, 1.2.5. This makes it possible for unauthenticated attackers to upload arbitrary fi…

### CVE-2025-10294
**The OwnID Passwordless Login plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.3.4.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-15)

> The OwnID Passwordless Login plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.3.4. This is due to the plugin not properly checking if the ownid_shared_secret value is empty prior to authenticating a user via JWT. This makes it po…

### CVE-2025-53521
**F5 BIG-IP Stack-Based Buffer Overflow Vulnerability**
- **Signals:** CVSS
- **Asset:** f5 big-ip_access_policy_manager
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T19:00:01.543
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-15)

> When a BIG-IP APM access policy is configured on a virtual server, specific malicious traffic can lead to Remote Code Execution (RCE).  

Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

### CVE-2025-56749
**creativeitem academy_lms Auth Bypass**
- **Signals:** CVSS
- **Asset:** creativeitem academy_lms
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-21T19:24:31.560
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-15)

> Creativeitem Academy LMS up to and including 6.14 uses a hardcoded default JWT secret for token signing. This predictable secret allows attackers to forge valid JWT tokens, leading to authentication bypass and unauthorized access to any user account.

### CVE-2025-62410
**In versions before 20.0.2, it was found that --disallow-code-generation-from-strings is not sufficient for isolating untrusted JavaScript...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-15)

> In versions before 20.0.2, it was found that --disallow-code-generation-from-strings is not sufficient for isolating untrusted JavaScript in happy-dom. The untrusted script and the rest of the application still run in the same Isolate/process, so attackers can deploy prototype po…

### CVE-2025-9967
**The Orion SMS OTP Verification plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-15)

> The Orion SMS OTP Verification plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.1.7. This is due to the plugin not properly validating a user's identity prior to updating their password. This makes it possible…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-15*
