# Daily Threat Intelligence — December 25, 2025

**Digest window (UTC):** 2025-12-25
**Generated:** 2026-06-02T07:34:03Z

## Threat brief

Ays-pro Quiz Maker: public exploit or PoC linked (SQL Injection)

## Executive summary

- Ays-pro Quiz Maker: public exploit or PoC linked (SQL Injection)

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 0 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2025-10042
**ays-pro quiz_maker SQL Injection**
- **Signals:** EXP
- **Asset:** ays-pro quiz_maker
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T12:38:54.293
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-25

> The Quiz Maker plugin for WordPress is vulnerable to SQL Injection via spoofed IP headers in all versions up to, and including, 6.7.0.56 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possib…

### CVE-2025-14558
**freebsd freebsd**
- **Signals:** EXP
- **Asset:** freebsd freebsd
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T15:55:24.490
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2025-12-25

> The rtsol(8) and rtsold(8) programs do not validate the domain search list options provided in router advertisement messages; the option body is passed to resolvconf(8) unmodified.

resolvconf(8) is a shell script which does not validate its input.  A lack of quoting meant that s…

### CVE-2025-10493
**The Chained Quiz plugin for WordPress is vulnerable to Insecure Direct Object Reference in version 1.3.4 and below via the quiz submissio...**
- **Signals:** EXP
- **CVSS max:** 5.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 78
- **EXP:** ref published 2025-12-25

> The Chained Quiz plugin for WordPress is vulnerable to Insecure Direct Object Reference in version 1.3.4 and below via the quiz submission and completion mechanisms due to missing validation on a user controlled key. This makes it possible for unauthenticated attackers to hijack …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-25*
