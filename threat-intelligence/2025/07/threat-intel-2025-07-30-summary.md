# Daily Threat Intelligence — July 30, 2025

**Digest window (UTC):** 2025-07-30
**Generated:** 2026-06-02T07:33:08Z

## Threat brief

Mcafee Antivirus Engine — exploitation likelihood rose sharply (EPSS 5.4% → 23% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Mcafee Antivirus Engine — exploitation likelihood rose sharply (EPSS 5.4% → 23% · rising (+18%)).
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

### CVE-2005-0643
**mcafee antivirus_engine Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mcafee antivirus_engine
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 5.4% (2025-03-30) → 23.2% (2025-07-30), Δ +17.8%**

> Buffer overflow in McAfee Scan Engine 4320 with DAT version before 4357 allows remote attackers to execute arbitrary code via crafted LHA files.

### CVE-2025-50578
**linuxserver docker-heimdall open redirect**
- **Signals:** CVSS
- **Asset:** linuxserver docker-heimdall
- **Attack:** open redirect
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-25T02:20:27.220
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-30)

> LinuxServer.io heimdall 2.6.3-ls307 contains a vulnerability in how it handles user-supplied HTTP headers, specifically `X-Forwarded-Host` and `Referer`. An unauthenticated remote attacker can manipulate these headers to perform Host Header Injection and Open Redirect attacks. Th…

### CVE-2025-43244
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:56.337
- **CWE:** CWE-362
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-30)

> A race condition was addressed with improved state handling. This issue is fixed in macOS Sequoia 15.6, macOS Sonoma 14.7.7, macOS Ventura 13.7.7. An app may be able to cause unexpected system termination.

### CVE-2025-43245
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:56.473
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-30)

> A downgrade issue was addressed with additional code-signing restrictions. This issue is fixed in macOS Sequoia 15.6, macOS Sonoma 14.7.7, macOS Ventura 13.7.7. An app may be able to access protected user data.

### CVE-2025-43253
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:57.620
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-30)

> This issue was addressed with improved input validation. This issue is fixed in macOS Sequoia 15.6, macOS Sonoma 14.7.7. A malicious app may be able to launch arbitrary binaries on a trusted device.

### CVE-2025-43261
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:58.513
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-30)

> A logic issue was addressed with improved checks. This issue is fixed in macOS Sequoia 15.6, macOS Sonoma 14.7.7, macOS Ventura 13.7.7. An app may be able to break out of its sandbox.

### CVE-2025-43273
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:20:18.307
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-30)

> A permissions issue was addressed with additional sandbox restrictions. This issue is fixed in macOS Sequoia 15.6, macOS Sonoma 14.8. A sandboxed process may be able to circumvent sandbox restrictions.

### CVE-2025-43275
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:59.657
- **CWE:** CWE-362
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-30)

> A race condition was addressed with additional validation. This issue is fixed in macOS Sequoia 15.6, macOS Sonoma 14.7.7, macOS Ventura 13.7.7. An app may be able to break out of its sandbox.

### CVE-2025-46811
**A Missing Authorization vulnerability in SUSE Linux Manager allows anyone with the ability to connect to port 443 of SUSE Manager is able...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-30)

> A Missing Authorization vulnerability in SUSE Linux Manager allows anyone with the ability to connect to port 443 of SUSE Manager is able to run any command as root on any client. This issue affects Container suse/manager/5.0/x86_64/server:5.0.5.7.30.1: from ? before 5.0.27-15060…

### CVE-2025-54430
**dedupe is a python library that uses machine learning to perform fuzzy matching, deduplication and entity resolution quickly on structure...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-30)

> dedupe is a python library that uses machine learning to perform fuzzy matching, deduplication and entity resolution quickly on structured data. Before commit 3f61e79, a critical severity vulnerability has been identified within the .github/workflows/benchmark-bot.yml workflow, w…

### CVE-2025-54576
**oauth2_proxy_project oauth2_proxy**
- **Signals:** CVSS
- **Asset:** oauth2_proxy_project oauth2_proxy
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-10T14:36:50.243
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-30)

> OAuth2-Proxy is an open-source tool that can act as either a standalone reverse proxy or a middleware component integrated into existing reverse proxy or load balancer setups. In versions 7.10.0 and below, oauth2-proxy deployments are vulnerable when using the skip_auth_routes co…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-30*
