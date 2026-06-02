# Daily Threat Intelligence — April 28, 2026

**Digest window (UTC):** 2026-04-28
**Generated:** 2026-06-02T07:35:02Z

## Threat brief

Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation. · Nsclient\+\+ — exploitation likelihood rose sharply (EPSS 56% → 73% · rising (+17%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation.
- Nsclient\+\+ — exploitation likelihood rose sharply (EPSS 56% → 73% · rising (+17%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2024-1708
**ConnectWise ScreenConnect Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** connectwise screenconnect
- **Attack:** Path Traversal
- **CVSS max:** 8.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-28T21:44:53.770
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-04-28

> ConnectWise ScreenConnect 23.9.7 and prior are affected by path-traversal vulnerability, which may allow an attacker 

the ability to execute remote code or directly impact confidential data or critical systems.

### CVE-2025-34079
**nsclient nsclient\+\+ RCE**
- **Signals:** EPSS
- **Asset:** nsclient nsclient\+\+
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-16T19:53:27.970
- **CWE:** CWE-94
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 56.0% (2026-03-18) → 73.1% (2026-04-28), Δ +17.1%**

> An authenticated remote code execution vulnerability exists in NSClient++ version 0.5.2.35 when the web interface and ExternalScripts module are enabled. A remote attacker with the administrator password can authenticate to the web interface (default port 8443), inject arbitrary …

### CVE-2025-60889
**stellar-group hpx Deserialization**
- **Signals:** CVSS
- **Asset:** stellar-group hpx
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T18:23:32.877
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-28)

> Insecure deserialization of untrusted input in StellarGroup HPX 1.11.0 under certain conditions may allow attackers to execute arbitrary code or other unspecified impacts.

### CVE-2021-45811
**enhancesoft osticket SQL Injection**
- **Signals:** EPSS
- **Asset:** enhancesoft osticket
- **Attack:** SQL Injection
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:33:05.103
- **CWE:** CWE-89
- **Risk score:** 78
- **EPSS 53.1% (2026-04-04) → 63.1% (2026-04-28), Δ +10.0%**

> A SQL injection vulnerability in the "Search" functionality of "tickets.php" page in osTicket 1.15.x allows authenticated attackers to execute arbitrary SQL commands via the "keywords" and "topic_id" URL parameters combination.

### CVE-2026-24178
**nvidia nvflare Code Execution**
- **Signals:** CVSS
- **Asset:** nvidia nvflare
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-04T14:34:01.557
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-28)

> NVIDIA NVFlare Dashboard contains a vulnerability in the user management and authentication system where an unauthenticated attacker may cause authorization bypass through user-controlled key. A successful exploit of this vulnerability may lead to privilege escalation, data tampe…

### CVE-2026-32202
**Microsoft Windows Protection Mechanism Failure Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 4.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T20:00:21.270
- **CWE:** CWE-693
- **Risk score:** 88
- **KEV:** added 2026-04-28

> Protection mechanism failure in Windows Shell allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-40976
**vmware spring_boot**
- **Signals:** CVSS
- **Asset:** vmware spring_boot
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-30T13:54:12.847
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-28)

> In certain circumstances, Spring Boot's default web security is ineffective allowing unauthorized access to all endpoints. For an application to be vulnerable, it must: be a servlet-based web application; have no Spring Security configuration of its own and rely on the default we…

### CVE-2026-41386
**openclaw openclaw Privilege Escalation**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-01T15:52:35.320
- **CWE:** CWE-648
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-28)

> OpenClaw before 2026.3.22 contains a privilege escalation vulnerability where bootstrap setup codes are not bound to intended device roles and scopes during pairing. Attackers can exploit this during first-use device pairing to escalate privileges beyond their intended role and s…

### CVE-2026-41446
**Snap One WattBox 800 and 820 series firmware versions prior to 2.10.0.0 contain undisclosed diagnostic HTTP endpoints that require only t...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-30T15:48:26.580
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-28)

> Snap One WattBox 800 and 820 series firmware versions prior to 2.10.0.0 contain undisclosed diagnostic HTTP endpoints that require only the device MAC address and service tag for authentication, both of which are printed in plaintext on the physical device label. Attackers with a…

### CVE-2026-41873
**apache pony_mail**
- **Signals:** CVSS
- **Asset:** apache pony_mail
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T13:16:51.850
- **CWE:** CWE-444
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-28)

> ** UNSUPPORTED WHEN ASSIGNED ** Inconsistent Interpretation of HTTP Requests ('HTTP Request/Response Smuggling') vulnerability in Pony Mail leading to admin account takeover.

This issue affects all versions of the Lua implementation of Pony Mail. There is a Python implementation…

### CVE-2026-5779
**agilonhealth minerva**
- **Signals:** CVSS
- **Asset:** agilonhealth minerva
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T14:20:48.227
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-28)

> An insecure direct object reference (IDOR) vulnerability in MphRx's Minerva V3.6.0, specifically in the '/minerva/user/updateUserProfile' endpoint. This allows an authenticated user to modify the information of other registered users. Successful exploitation of this vulnerability…

### CVE-2026-7321
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-01T17:54:04.827
- **CWE:** CWE-120
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-28)

> Sandbox escape due to incorrect boundary conditions in the WebRTC: Networking component. This vulnerability was fixed in Firefox 150, Thunderbird 150, Firefox ESR 140.10.1, and Thunderbird 140.10.1.

### CVE-2026-7333
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-30T18:30:10.083
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-28)

> Use after free in GPU in Google Chrome prior to 147.0.7727.138 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-28*
