# Daily Threat Intelligence — December 19, 2025

**Digest window (UTC):** 2025-12-19
**Generated:** 2026-06-02T07:34:00Z

## Threat brief

WatchGuard Firebox added to CISA KEV — confirmed in-the-wild exploitation. · Arista Dcs-7050cx3-32s-r Firmware — exploitation likelihood rose sharply (EPSS 67% → 78% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WatchGuard Firebox added to CISA KEV — confirmed in-the-wild exploitation.
- Arista Dcs-7050cx3-32s-r Firmware — exploitation likelihood rose sharply (EPSS 67% → 78% · rising (+11%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-14733
**WatchGuard Firebox Out of Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** watchguard fireware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-23T11:34:46.317
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-12-19

> An Out-of-bounds Write vulnerability in WatchGuard Fireware OS may allow a remote unauthenticated attacker to execute arbitrary code. This vulnerability affects both the Mobile User VPN with IKEv2 and the Branch Office VPN using IKEv2 when configured with a dynamic gateway peer.T…

### CVE-2020-9015
**arista dcs-7050cx3-32s-r_firmware**
- **Signals:** EPSS
- **Asset:** arista dcs-7050qx-32s-r_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:39:49.993
- **Risk score:** 84
- **EPSS 67.5% (2025-11-21) → 78.4% (2025-12-19), Δ +10.9%**

> Arista DCS-7050QX-32S-R 4.20.9M, DCS-7050CX3-32S-R 4.20.11M, and DCS-7280SRAM-48C6-R 4.22.0.1F devices (and possibly other products) allow attackers to bypass intended TACACS+ shell restrictions via a | character. NOTE: the vendor reports that this is a configuration issue relati…

### CVE-2025-68613
**n8n Improper Control of Dynamically-Managed Code Resources Vulnerability**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T19:40:09.533
- **CWE:** CWE-913
- **CWE:** CWE-913
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-19)

> n8n is an open source workflow automation platform. Versions starting with 0.211.0 and prior to 1.120.4, 1.121.1, and 1.122.0 contain a critical Remote Code Execution (RCE) vulnerability in their workflow expression evaluation system. Under certain conditions, expressions supplie…

### CVE-2023-53948
**Lilac-Reloaded for Nagios 2.0.8 contains a remote code execution vulnerability in the autodiscovery feature that allows attackers to inje...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-19)

> Lilac-Reloaded for Nagios 2.0.8 contains a remote code execution vulnerability in the autodiscovery feature that allows attackers to inject arbitrary commands. Attackers can exploit the lack of input filtering in the nmap_binary parameter to execute a reverse shell by sending a c…

### CVE-2023-53950
**InnovaStudio WYSIWYG Editor 5.4 contains an unrestricted file upload vulnerability that allows attackers to bypass file extension restric...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-19)

> InnovaStudio WYSIWYG Editor 5.4 contains an unrestricted file upload vulnerability that allows attackers to bypass file extension restrictions through filename manipulation. Attackers can upload malicious ASP shells by using null byte techniques and alternate file extensions to c…

### CVE-2023-53951
**Ever Gauzy v0.281.9 contains a JWT authentication vulnerability that allows attackers to exploit weak HMAC secret key implementation.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-19)

> Ever Gauzy v0.281.9 contains a JWT authentication vulnerability that allows attackers to exploit weak HMAC secret key implementation. Attackers can leverage the exposed JWT token to authenticate and gain unauthorized access with administrative permissions.

### CVE-2024-49587
**Glutton V1 service endpoints were exposed without any authentication on Gotham stacks, this could have allowed users that did not have an...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-305
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-19)

> Glutton V1 service endpoints were exposed without any authentication on Gotham stacks, this could have allowed users that did not have any permission to hit glutton backend directly and read/update/delete data. The affected service has been patched and automatically deployed to a…

### CVE-2025-14964
**totolink t10_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink t10_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T18:16:07.343
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-19)

> A vulnerability has been found in TOTOLINK T10 4.1.8cu.5083_B20200521. This affects the function sprintf of the file /cgi-bin/cstecgi.cgi. Such manipulation of the argument loginAuthUrl leads to stack-based buffer overflow. The attack may be performed from remote.

### CVE-2025-1928
**restajet online_food_delivery_system**
- **Signals:** CVSS
- **Asset:** restajet online_food_delivery_system
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-03-26T08:16:19.620
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-19)

> Improper Restriction of Excessive Authentication Attempts vulnerability in Restajet Information Technologies Inc. Online Food Delivery System allows Password Recovery Exploitation.This issue affects Online Food Delivery System: through 19122025. NOTE: The vendor was contacted ear…

### CVE-2025-34433
**AVideo versions 14.3.1 prior to 20.1 contain an unauthenticated remote code execution vulnerability caused by predictable generation of a...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-19)

> AVideo versions 14.3.1 prior to 20.1 contain an unauthenticated remote code execution vulnerability caused by predictable generation of an installation salt using PHP uniqid(). The installation timestamp is exposed via a public endpoint, and a derived hash identifier is accessibl…

### CVE-2025-63665
**gtedge gt_edge_ai**
- **Signals:** CVSS
- **Asset:** gtedge gt_edge_ai
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-05T17:58:58.503
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-19)

> An issue in GT Edge AI Community Edition Versions before v2.0.12 allows attackers to execute arbitrary code via injecting a crafted JSON payload into the Prompt window.

### CVE-2025-66580
**openagentplatform dive XSS**
- **Signals:** CVSS
- **Asset:** openagentplatform dive
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-02T19:15:17.203
- **CWE:** CWE-94
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-19)

> Dive is an open-source MCP Host Desktop Application that enables integration with function-calling LLMs. A critical Stored Cross-Site Scripting (XSS) vulnerability exists in versions prior to 0.11.1 in the Mermaid diagram rendering component. The application allows the execution …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-19*
