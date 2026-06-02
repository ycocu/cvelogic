# Daily Threat Intelligence — November 26, 2025

**Digest window (UTC):** 2025-11-26
**Generated:** 2026-06-02T07:33:51Z

## Threat brief

Kame Ipcomp — exploitation likelihood rose sharply (EPSS 28% → 54% · rising (+26%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Kame Ipcomp — exploitation likelihood rose sharply (EPSS 28% → 54% · rising (+26%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2008-0177
**kame ipcomp DoS**
- **Signals:** EPSS
- **Asset:** kame ipcomp
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 83
- **EPSS 28.1% (2025-03-30) → 54.5% (2025-11-26), Δ +26.3%**

> The ipcomp6_input function in sys/netinet6/ipcomp_input.c in the KAME project before 20071201 does not properly check the return value of the m_pulldown function, which allows remote attackers to cause a denial of service (system crash) via an IPv6 packet with an IPComp header.

### CVE-2025-64126
**An OS command injection vulnerability exists due to improper input validation.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-26)

> An OS command injection vulnerability exists due to improper input 
validation. The application accepts a parameter directly from user input
 without verifying it is a valid IP address or filtering potentially 
malicious characters. This could allow an unauthenticated attacker to…

### CVE-2025-64127
**An OS command injection vulnerability exists due to insufficient sanitization of user-supplied input.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-26)

> An OS command injection vulnerability exists due to insufficient 
sanitization of user-supplied input. The application accepts parameters 
that are later incorporated into OS commands without adequate 
validation. This could allow an unauthenticated attacker to execute 
arbitrary…

### CVE-2025-26155
**ncp-e ncp_secure_entry_client**
- **Signals:** CVSS
- **Asset:** ncp-e ncp_secure_entry_client
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T15:41:08.380
- **CWE:** CWE-426
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-26)

> NCP Secure Enterprise Client 13.18 and NCP Secure Entry Windows Client 13.19 have an Untrusted Search Path vulnerability.

### CVE-2025-40934
**xml::sig_project xml::sig**
- **Signals:** CVSS
- **Asset:** xml\ \
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T15:21:37.487
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-26)

> XML-Sig versions 0.27 through 0.67 for Perl incorrectly validates XML files if signatures are omitted.

An attacker can remove the signature from the XML document to make it pass the verification check.

XML-Sig is a Perl module to validate signatures on XML files.  An unsigned X…

### CVE-2025-50433
**monnit imonnit privilege escalation**
- **Signals:** CVSS
- **Asset:** monnit imonnit
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-29T15:46:51.940
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-26)

> An issue was discovered in imonnit.com (2025-04-24) allowing malicious actors to gain escalated privileges via crafted password reset to take over arbitrary user accounts.

### CVE-2025-62593
**Ray is an AI compute engine.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-26)

> Ray is an AI compute engine. Prior to version 2.52.0, developers working with Ray as a development tool can be exploited via a critical RCE vulnerability exploitable via Firefox and Safari. This vulnerability is due to an insufficient guard against browser-based attacks, as the c…

### CVE-2025-64128
**An OS command injection vulnerability exists due to incomplete validation of user-supplied input.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-26)

> An OS command injection vulnerability exists due to incomplete 
validation of user-supplied input. Validation fails to enforce 
sufficient formatting rules, which could permit attackers to append 
arbitrary data. This could allow an unauthenticated attacker to inject 
arbitrary c…

### CVE-2025-64130
**Zenitel TCIV-3+ is vulnerable to a reflected cross-site scripting vulnerability, which could allow a remote attacker to execute arbitrary...**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-26)

> Zenitel TCIV-3+ is vulnerable to a reflected cross-site scripting 
vulnerability, which could allow a remote attacker to execute arbitrary 
JavaScript on the victim's browser.

### CVE-2025-65276
**henzljw hashtech**
- **Signals:** CVSS
- **Asset:** henzljw hashtech
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T15:34:16.817
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-26)

> An unauthenticated administrative access vulnerability exists in the open-source HashTech project (https://github.com/henzljw/hashtech) 1.0 thru commit 5919decaff2681dc250e934814fc3a35f6093ee5 (2021-07-02). Due to missing authentication checks on /admin_index.php, an attacker can…

### CVE-2025-65669
**classroomio classroomio privilege escalation**
- **Signals:** CVSS
- **Asset:** classroomio classroomio
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T20:50:01.060
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-26)

> An issue was discovered in classroomio 0.1.13. Student accounts are able to delete courses from the Explore page without any authorization or authentication checks, bypassing the expected admin-only deletion restriction.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-26*
