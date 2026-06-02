# Daily Threat Intelligence — January 29, 2026

**Digest window (UTC):** 2026-01-29
**Generated:** 2026-06-02T07:34:18Z

## Threat brief

Ivanti Endpoint Manager Mobile (EPMM) added to CISA KEV — confirmed in-the-wild exploitation. · Applied Watch Technologies Applied Watch Command Center — exploitation likelihood rose sharply (EPSS 4.1% → 20% · rising (+16%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Endpoint Manager Mobile (EPMM) added to CISA KEV — confirmed in-the-wild exploitation.
- Applied Watch Technologies Applied Watch Command Center — exploitation likelihood rose sharply (EPSS 4.1% → 20% · rising (+16%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2026-1281
**Ivanti Endpoint Manager Mobile (EPMM) Code Injection Vulnerability**
- **Signals:** KEV, CVSS
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T13:28:18.610
- **CWE:** CWE-94
- **Risk score:** 97
- **KEV:** added 2026-01-29
- **CVSS critical:** 9.8 (disclosed 2026-01-29)

> A code injection in Ivanti Endpoint Manager Mobile allowing attackers to achieve unauthenticated remote code execution.

### CVE-2003-0974
**applied_watch_technologies applied_watch_command_center**
- **Signals:** EPSS
- **Asset:** applied_watch_technologies applied_watch_command_center
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 4.1% (2025-08-06) → 19.7% (2026-01-29), Δ +15.6%**

> Applied Watch Command Center allows remote attackers to conduct unauthorized activities without authentication, such as (1) add new users to a console, as demonstrated using appliedsnatch.c, or (2) add spurious IDS rules to sensors, as demonstrated using addrule.c.

### CVE-2025-69929
**n3uron web_user_interface privilege escalation**
- **Signals:** CVSS
- **Asset:** n3uron web_user_interface
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-27T18:16:09.217
- **CWE:** CWE-327
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-29)

> An issue in N3uron Web User Interface v.1.21.7-240207.1047 allows a remote attacker to escalate privileges via the password hashing on the client side using the MD5 algorithm over a predictable string format

### CVE-2003-0128
**ximian evolution Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ximian evolution
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 76
- **EPSS 24.4% (2025-11-22) → 34.5% (2026-01-29), Δ +10.2%**

> The try_uudecoding function in mail-format.c for Ximian Evolution Mail User Agent 1.2.2 and earlier allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a malicious uuencoded (UUE) header, possibly triggering a heap-based buffer ove…

### CVE-2009-0885
**mediacommands media_commands Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mediacommands media_commands
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 39.3% (2026-01-02) → 50.7% (2026-01-29), Δ +11.4%**

> Multiple heap-based buffer overflows in Media Commands 1.0 allow remote attackers to execute arbitrary code or cause a denial of service (application crash) via a long string in a (1) M3U, (2) M3l, (3) TXT, and (4) LRC playlist file.

### CVE-2020-37012
**Tea LaTex 1.0 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary shell commands th...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-29)

> Tea LaTex 1.0 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary shell commands through the /api.php endpoint. Attackers can craft a malicious LaTeX payload with shell commands that are executed when processed by the applicat…

### CVE-2026-1340
**Ivanti Endpoint Manager Mobile (EPMM) Code Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T14:03:31.767
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-29)

> A code injection in Ivanti Endpoint Manager Mobile allowing attackers to achieve unauthenticated remote code execution.

### CVE-2026-1453
**A missing authentication for critical function vulnerability in KiloView Encoder Series could allow an unauthenticated attacker to create...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-29)

> A missing authentication for critical function vulnerability in KiloView Encoder Series could allow an unauthenticated attacker to create or delete administrator accounts. This vulnerability can grant the attacker full administrative control over the product.

### CVE-2026-22806
**vCluster Platform provides a Kubernetes platform for managing virtual clusters, multi-tenancy, and cluster sharing.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-29)

> vCluster Platform provides a Kubernetes platform for managing virtual clusters, multi-tenancy, and cluster sharing. Prior to versions 4.6.0, 4.5.4, 4.4.2, and 4.3.10, when an access key is created with a limited scope, the scope can be bypassed to access resources outside of it. …

### CVE-2026-25047
**sharpred deephas**
- **Signals:** CVSS
- **Asset:** sharpred deephas
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T15:13:28.610
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-29)

> deepHas provides a test for the existence of a nested object key and optionally returns that key. A prototype pollution vulnerability exists in version 1.0.7 of the deephas npm package that allows an attacker to modify global object behavior. This issue was fixed in version 1.0.8…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-29*
