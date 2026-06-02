# Daily Threat Intelligence — February 15, 2026

**Digest window (UTC):** 2026-02-15
**Generated:** 2026-06-02T07:34:25Z

## Threat brief

Macromedia Shockwave — exploitation likelihood rose sharply (EPSS 22% → 56% · rising (+34%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Macromedia Shockwave — exploitation likelihood rose sharply (EPSS 22% → 56% · rising (+34%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2007-1403
**macromedia shockwave Buffer Overflow**
- **Signals:** EPSS
- **Asset:** macromedia shockwave
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 21.5% (2025-10-27) → 55.8% (2026-02-15), Δ +34.2%**

> Multiple stack-based buffer overflows in an ActiveX control in SwDir.dll 10.1.4.20 in Macromedia Shockwave allow remote attackers to cause a denial of service (Internet Explorer 7 crash) and possibly execute arbitrary code via a long (1) BGCOLOR, (2) SRC, (3) AutoStart, (4) Sound…

### CVE-2026-1490
**The Spam protection, Anti-Spam, FireWall by CleanTalk plugin for WordPress is vulnerable to unauthorized Arbitrary Plugin Installation du...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-350
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-15)

> The Spam protection, Anti-Spam, FireWall by CleanTalk plugin for WordPress is vulnerable to unauthorized Arbitrary Plugin Installation due to an authorization bypass via reverse DNS (PTR record) spoofing on the 'checkWithoutToken' function in all versions up to, and including, 6.…

### CVE-2026-26369
**jung-group enet_smart_home Privilege Escalation**
- **Signals:** CVSS
- **Asset:** jung-group enet_smart_home
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-28T01:34:28.150
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-15)

> eNet SMART HOME server 2.2.1 and 2.3.1 contains a privilege escalation vulnerability due to insufficient authorization checks in the setUserGroup JSON-RPC method. A low-privileged user (UG_USER) can send a crafted POST request to /jsonrpc/management specifying their own username …

### CVE-2025-32058
**The Infotainment ECU manufactured by Bosch uses a RH850 module for CAN communication.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-15)

> The Infotainment ECU manufactured by Bosch uses a RH850 module for CAN communication. RH850 is connected to infotainment over the INC interface through a custom protocol. There is a vulnerability during processing requests of this protocol on the V850 side which allows an attacke…

### CVE-2026-26366
**jung-group enet_smart_home**
- **Signals:** CVSS
- **Asset:** jung-group enet_smart_home
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T22:44:42.813
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-15)

> eNet SMART HOME server 2.2.1 and 2.3.1 ships with default credentials (user:user, admin:admin) that remain active after installation and commissioning without enforcing a mandatory password change. Unauthenticated attackers can use these default credentials to gain administrative…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-15*
