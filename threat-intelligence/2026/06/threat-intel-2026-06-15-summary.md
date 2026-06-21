# Daily Threat Intelligence — June 15, 2026

**Digest window (US Eastern, NVD):** 2026-06-15
**Generated:** 2026-06-21T09:42:45Z

## Threat brief

Cisco Catalyst SD-WAN Manager added to CISA KEV — confirmed in-the-wild exploitation. · Ivanti Endpoint Manager — exploitation likelihood rose sharply (EPSS 2.4% → 100% · rising (+97%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Catalyst SD-WAN Manager added to CISA KEV — confirmed in-the-wild exploitation.
- Ivanti Endpoint Manager — exploitation likelihood rose sharply (EPSS 2.4% → 100% · rising (+97%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **22** |


## CVEs

### CVE-2026-20262
**Cisco Catalyst SD-WAN Manager Directory or Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** Path Traversal
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-06-15

> A vulnerability in the web UI of Cisco Catalyst SD-WAN Manager, formerly SD-WAN vManage, could allow an authenticated, remote attacker to create a file or overwrite any file on the filesystem of an affected system.

This vulnerability exists because the affected software does n…

### CVE-2024-29823
**ivanti endpoint_manager SQL Injection**
- **Signals:** EPSS
- **Asset:** ivanti endpoint_manager
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD published:** 2024-05-31
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 2.4% (2026-02-24) → 99.9% (2026-06-15), Δ +97.5%**

> An unspecified SQL Injection vulnerability in Core server of Ivanti EPM 2022 SU5 and prior allows an unauthenticated attacker within the same network to execute arbitrary code.

### CVE-2026-49781
**Unauthenticated PHP Object Injection in OttoKit <= 1.1.27 versions.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-15)

> Unauthenticated PHP Object Injection in OttoKit <= 1.1.27 versions.

### CVE-2012-1422
**cat nod32_antivirus**
- **Signals:** EPSS
- **Asset:** cat quick_heal
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD published:** 2012-03-21
- **NVD modified:** 2026-06-16
- **CWE:** CWE-264
- **Risk score:** 77
- **EPSS 0.2% (2025-06-03) → 94.2% (2026-06-15), Δ +94.0%**

> The TAR file parser in Quick Heal (aka Cat QuickHeal) 11.00, NOD32 Antivirus 5795, Norman Antivirus 6.06.12, and Rising Antivirus 22.83.00.03 allows remote attackers to bypass malware detection via a POSIX TAR file with an initial ITSF character sequence.  NOTE: this may later be…

### CVE-2012-1430
**aladdin anti-virus**
- **Signals:** EPSS
- **Asset:** aladdin esafe
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD published:** 2012-03-21
- **NVD modified:** 2026-06-16
- **CWE:** CWE-264
- **Risk score:** 77
- **EPSS 0.5% (2025-06-03) → 96.1% (2026-06-15), Δ +95.6%**

> The ELF file parser in Bitdefender 7.2, Comodo Antivirus 7424, eSafe 7.0.17.0, F-Secure Anti-Virus 9.0.16160.0, McAfee Anti-Virus Scanning Engine 5.400.0.1158, McAfee Gateway (formerly Webwasher) 2010.1C, nProtect Anti-Virus 2011-01-17.01, Sophos Anti-Virus 4.61.0, and Rising Ant…

### CVE-2012-1431
**aladdin bitdefender**
- **Signals:** EPSS
- **Asset:** aladdin esafe
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD published:** 2012-03-21
- **NVD modified:** 2026-06-16
- **CWE:** CWE-264
- **Risk score:** 77
- **EPSS 0.5% (2025-06-03) → 96.1% (2026-06-15), Δ +95.6%**

> The ELF file parser in Bitdefender 7.2, Command Antivirus 5.2.11.5, Comodo Antivirus 7424, eSafe 7.0.17.0, F-Prot Antivirus 4.6.2.117, F-Secure Anti-Virus 9.0.16160.0, McAfee Gateway (formerly Webwasher) 2010.1C, nProtect Anti-Virus 2011-01-17.01, Sophos Anti-Virus 4.61.0, and Ri…

### CVE-2012-1442
**aladdin avl_sdk**
- **Signals:** EPSS
- **Asset:** aladdin esafe
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD published:** 2012-03-21
- **NVD modified:** 2026-06-16
- **CWE:** CWE-264
- **Risk score:** 77
- **EPSS 2.8% (2025-06-03) → 99.0% (2026-06-15), Δ +96.1%**

> The ELF file parser in Quick Heal (aka Cat QuickHeal) 11.00, McAfee Anti-Virus Scanning Engine 5.400.0.1158, McAfee Gateway (formerly Webwasher) 2010.1C, eSafe 7.0.17.0, Kaspersky Anti-Virus 7.0.0.125, F-Secure Anti-Virus 9.0.16160.0, Sophos Anti-Virus 4.61.0, Antiy Labs AVL SDK …

### CVE-2012-1446
**aladdin avl_sdk**
- **Signals:** EPSS
- **Asset:** aladdin esafe
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD published:** 2012-03-21
- **NVD modified:** 2026-06-16
- **CWE:** CWE-264
- **Risk score:** 77
- **EPSS 2.5% (2025-06-03) → 99.7% (2026-06-15), Δ +97.2%**

> The ELF file parser in Quick Heal (aka Cat QuickHeal) 11.00, McAfee Anti-Virus Scanning Engine 5.400.0.1158, AVEngine 20101.3.0.103 in Symantec Endpoint Protection 11, Norman Antivirus 6.06.12, eSafe 7.0.17.0, Kaspersky Anti-Virus 7.0.0.125, McAfee Gateway (formerly Webwasher) 20…

### CVE-2012-1460
**aladdin antivirus**
- **Signals:** EPSS
- **Asset:** aladdin esafe
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD published:** 2012-03-21
- **NVD modified:** 2026-06-16
- **CWE:** CWE-264
- **Risk score:** 77
- **EPSS 0.6% (2025-06-03) → 94.5% (2026-06-15), Δ +94.0%**

> The Gzip file parser in Antiy Labs AVL SDK 2.0.3.7, Quick Heal (aka Cat QuickHeal) 11.00, Command Antivirus 5.2.11.5, eSafe 7.0.17.0, F-Prot Antivirus 4.6.2.117, Jiangmin Antivirus 13.0.900, K7 AntiVirus 9.77.3565, and VBA32 3.12.14.2 allows remote attackers to bypass malware det…

### CVE-2020-11022
**debian agile_product_lifecycle_management_for_process**
- **Signals:** EPSS
- **Asset:** jquery jquery
- **CVSS max:** 6.9
- **NVD status:** Modified
- **NVD published:** 2020-04-29
- **NVD modified:** 2026-06-16
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 81
- **EPSS 2.4% (2026-06-09) → 99.0% (2026-06-15), Δ +96.6%**

> In jQuery starting with 1.12.0 and before 3.5.0, passing HTML from untrusted sources - even after sanitizing it - to one of jQuery's DOM manipulation methods (i.e. .html(), .append(), and others) may execute untrusted code. This problem is patched in jQuery 3.5.0.

### CVE-2024-29825
**ivanti endpoint_manager SQL Injection**
- **Signals:** EPSS
- **Asset:** ivanti endpoint_manager
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD published:** 2024-05-31
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 2.4% (2026-02-24) → 99.9% (2026-06-15), Δ +97.5%**

> An unspecified SQL Injection vulnerability in Core server of Ivanti EPM 2022 SU5 and prior allows an unauthenticated attacker within the same network to execute arbitrary code.

### CVE-2024-29826
**ivanti endpoint_manager SQL Injection**
- **Signals:** EPSS
- **Asset:** ivanti endpoint_manager
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD published:** 2024-05-31
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 2.4% (2026-02-24) → 99.9% (2026-06-15), Δ +97.5%**

> An unspecified SQL Injection vulnerability in Core server of Ivanti EPM 2022 SU5 and prior allows an unauthenticated attacker within the same network to execute arbitrary code.

### CVE-2026-11832
**Dancer2::Plugin::Auth::OAuth versions before 0.22 for Perl default to a predictable nonce.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-338
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-15)

> Dancer2::Plugin::Auth::OAuth versions before 0.22 for Perl default to a predictable nonce.

The default nonce was generated using an MD5 hash of the epoch time, which is predictable.

### CVE-2026-12087
**Socket versions before 2.041 for Perl have an out-of-bounds heap read.**
- **Signals:** CVSS
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-15)

> Socket versions before 2.041 for Perl have an out-of-bounds heap read.

In Socket.xs, pack_ip_mreq_source() checks the length of its source argument before the argument is read, so the check tests the byte length carried over from the preceding multiaddr argument instead. Both ad…

### CVE-2026-12205
**Crypt::DSA versions before 1.21 for Perl reused the nonce across signatures, leading to private-key recovery.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-323
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-15)

> Crypt::DSA versions before 1.21 for Perl reused the nonce across signatures, leading to private-key recovery.

Crypt::DSA::sign caches the per-signature nonce material in the Key object without ever clearing it.

The first sign() on a Key object picks a nonce, and every later sig…

### CVE-2026-48713
**i18next i18next-fs-backend**
- **Signals:** CVSS
- **Asset:** i18next i18next-fs-backend
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-15)

> Versions prior to 2.6.6 are vulnerable to prototype pollution via crafted missing-key strings when used to persist missing translation keys (e.g. via i18next-http-middleware's missingKeyHandler exposed to untrusted input). Backend.writeFile() splits each queued missing-key string…

### CVE-2026-48714
**i18next i18next-http-middleware**
- **Signals:** CVSS
- **Asset:** i18next i18next-http-middleware
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-18
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-15)

> i18next-http-middleware is a middleware to be used with Node.js web frameworks like express or Fastify and also for Deno. In versions prior to 3.9.7, the missingKeyHandler blocked the literal request-body keys __proto__, constructor, and prototype (added in 3.9.3, see GHSA-5fgg-j…

### CVE-2026-48853
**Deserialization of Untrusted Data and Allocation of Resources Without Limits or Throttling vulnerabilities in elixir-grpc grpc allow unau...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-15)

> Deserialization of Untrusted Data and Allocation of Resources Without Limits or Throttling vulnerabilities in elixir-grpc grpc allow unauthenticated attackers to crash the BEAM node via atom table exhaustion and, when a decoded term flows into a call site that invokes it, achieve…

### CVE-2026-52693
**Unauthenticated SQL Injection in eCommerce Product Catalog <= 3.5.5 versions.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-15)

> Unauthenticated SQL Injection in eCommerce Product Catalog <= 3.5.5 versions.

### CVE-2026-52703
**Unauthenticated Path Traversal in FastDup <= 2.7.2 versions.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-35
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-15)

> Unauthenticated Path Traversal in FastDup <= 2.7.2 versions.

### CVE-2026-54420
**LiteSpeed cPanel Plugin UNIX Symbolic Link (Symlink) Following Vulnerability**
- **Signals:** KEV
- **Asset:** litespeedtech litespeed_cpanel_plugin
- **CVSS max:** 8.5
- **NVD status:** Analyzed
- **NVD published:** 2026-06-14
- **NVD modified:** 2026-06-17
- **CWE:** CWE-61
- **Risk score:** 88
- **KEV:** added 2026-06-15

> LiteSpeed cPanel plugin before 2.4.8 (as distributed in LiteSpeed WHM PlugIn before 5.3.2.0) mishandles symlinks provided by a user with FTP or web shell access on a shared hosting server running CloudLinux/CageFS, as exploited in the wild in May 2026.

### CVE-2026-9691
**Unauthenticated PHP Object Injection in Integration for ActiveCampaign and Contact Form 7, WPForms, Elementor, Ninja Forms <= 1.1.1 versi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD published:** 2026-06-15
- **NVD modified:** 2026-06-17
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-15)

> Unauthenticated PHP Object Injection in Integration for ActiveCampaign and Contact Form 7, WPForms, Elementor, Ninja Forms <= 1.1.1 versions.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-15*
