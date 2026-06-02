# Daily Threat Intelligence — March 19, 2026

**Digest window (UTC):** 2026-03-19
**Generated:** 2026-06-02T07:34:41Z

## Threat brief

Cisco Secure Firewall Management Center (FMC) added to CISA KEV — confirmed in-the-wild exploitation. · Debian Linux — exploitation likelihood rose sharply (EPSS 20% → 45% · rising (+25%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Secure Firewall Management Center (FMC) added to CISA KEV — confirmed in-the-wild exploitation.
- Debian Linux — exploitation likelihood rose sharply (EPSS 20% → 45% · rising (+25%)).
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

### CVE-2026-20131
**Cisco Secure Firewall Management Center (FMC) Software and Cisco Security Cloud Control (SCC) Firewall Management Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** cisco secure_firewall_management_center
- **Attack:** Deserialization
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T17:39:46.247
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-03-19

> A vulnerability in the web-based management interface of Cisco Secure Firewall Management Center (FMC) Software could allow an unauthenticated, remote attacker to execute arbitrary Java code as root&nbsp;on an affected device.

This vulnerability is due to insecure deserializat…

### CVE-2020-25681
**debian debian_linux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** thekelleys dnsmasq
- **Attack:** Buffer Overflow
- **CVSS max:** 8.3
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T20:15:56.797
- **CWE:** CWE-122
- **Risk score:** 83
- **EPSS 20.3% (2025-12-28) → 45.4% (2026-03-19), Δ +25.1%**

> A flaw was found in dnsmasq before version 2.83. A heap-based buffer overflow was discovered in the way RRSets are sorted before validating with DNSSEC data. An attacker on the network, who can forge DNS replies such as that they are accepted as valid, could use this flaw to caus…

### CVE-2026-32169
**microsoft azure_cloud_shell SSRF**
- **Signals:** CVSS
- **Asset:** microsoft azure_cloud_shell
- **Attack:** SSRF
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T17:14:41.383
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-19)

> Server-side request forgery (ssrf) in Azure Cloud Shell allows an unauthorized attacker to elevate privileges over a network.

### CVE-2026-22732
**vmware spring_security**
- **Signals:** CVSS
- **Asset:** vmware spring_security
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T04:29:24.503
- **CWE:** CWE-425
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-19)

> When applications specify HTTP response headers for servlet applications using Spring Security, there is the possibility that the HTTP Headers will not be written. 
This issue affects Spring Security Servlet applications using lazy (default) writing of HTTP Headers:

: from 5.7.0…

### CVE-2026-29103
**suitecrm suitecrm RCE**
- **Signals:** CVSS
- **Asset:** suitecrm suitecrm
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-24T14:23:34.037
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-19)

> SuiteCRM is an open-source, enterprise-ready Customer Relationship Management (CRM) software application. A Critical Remote Code Execution (RCE) vulnerability exists in SuiteCRM 7.15.0 and 8.9.2, allowing authenticated administrators to execute arbitrary system commands. This vul…

### CVE-2026-30871
**openwrt openwrt Buffer Overflow**
- **Signals:** CVSS
- **Asset:** openwrt openwrt
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-24T14:07:06.507
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-03-19)

> OpenWrt Project is a Linux operating system targeting embedded devices. In versions prior to 24.10.6 and 25.12.1, the mdns daemon has a Stack-based Buffer Overflow vulnerability in the parse_question function. The issue is  triggered by PTR queries for reverse DNS domains (.in-ad…

### CVE-2026-30872
**openwrt openwrt Buffer Overflow**
- **Signals:** CVSS
- **Asset:** openwrt openwrt
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-24T14:05:07.653
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-03-19)

> OpenWrt Project is a Linux operating system targeting embedded devices. In versions prior to 24.10.6 and 25.12.1, the mdns daemon has a Stack-based Buffer Overflow vulnerability in the match_ipv6_addresses function, triggered when processing PTR queries for IPv6 reverse DNS domai…

### CVE-2026-32038
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-23T17:18:25.310
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-19)

> OpenClaw before 2026.2.24 contains a sandbox network isolation bypass vulnerability that allows trusted operators to join another container's network namespace. Attackers can configure the docker.network parameter with container:<id> values to reach services in target container n…

### CVE-2026-32191
**microsoft bing_images Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft bing_images
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T16:35:56.453
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-19)

> Improper neutralization of special elements used in an os command ('os command injection') in Microsoft Bing Images allows an unauthorized attacker to execute code over a network.

### CVE-2026-32194
**microsoft bing_images Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft bing_images
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T16:35:28.323
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-19)

> Improper neutralization of special elements used in a command ('command injection') in Microsoft Bing Images allows an unauthorized attacker to execute code over a network.

### CVE-2026-32754
**freescout freescout XSS**
- **Signals:** CVSS
- **Asset:** freescout freescout
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-23T19:14:38.140
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-19)

> FreeScout is a free help desk and shared inbox built with PHP's Laravel framework. Versions 1.8.208 and below are vulnerable to Stored Cross-Site Scripting (XSS) through FreeScout's email notification templates. Incoming email bodies are stored in the database without sanitizatio…

### CVE-2026-4428
**A logic error in CRL distribution point validation in AWS-LC before 1.71.0 causes partitioned CRLs to be incorrectly rejected as out of s...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-20T13:39:46.493
- **CWE:** CWE-299
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-19)

> A logic error in CRL distribution point validation in AWS-LC before 1.71.0 causes partitioned CRLs to be incorrectly rejected as out of scope, which allows  a revoked certificate to bypass certificate revocation checks.

To remediate this issue, users should upgrade to AWS-LC 1.7…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-19*
