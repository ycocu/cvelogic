# Daily Threat Intelligence — November 10, 2025

**Digest window (UTC):** 2025-11-10
**Generated:** 2026-06-02T07:33:45Z

## Threat brief

Samsung Mobile Devices added to CISA KEV — confirmed in-the-wild exploitation. · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Samsung Mobile Devices added to CISA KEV — confirmed in-the-wild exploitation.
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2025-21042
**Samsung Mobile Devices Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** samsung android
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T14:32:28.317
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-11-10

> Out-of-bounds write in libimagecodec.quram.so prior to SMR Apr-2025 Release 1 allows remote attackers to execute arbitrary code.

### CVE-2021-4462
**skittles employee_records_system**
- **Signals:** CVSS
- **Asset:** skittles employee_records_system
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T12:57:17.830
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-10)

> Employee Records System version 1.0 contains an unrestricted file upload vulnerability that allows a remote unauthenticated attacker to upload arbitrary files via the uploadID.php endpoint; uploaded files can be executed because the application does not perform proper server-side…

### CVE-2025-12868
**New Site Server developed by CyberTutor has a Use of Client-Side Authentication vulnerability, allowing unauthenticated remote attackers...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-603
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-10)

> New Site Server developed by CyberTutor has a Use of Client-Side Authentication vulnerability, allowing unauthenticated remote attackers to modify the frontend code to gain administrator privileges on the website.

### CVE-2025-12480
**Gladinet Triofox Improper Access Control Vulnerability**
- **Signals:** CVSS
- **Asset:** gladinet triofox
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T02:00:02.350
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-10)

> Triofox versions prior to 16.7.10368.56560, are vulnerable to an Improper Access Control flaw that allows access to initial setup pages even after setup is complete.

### CVE-2025-12866
**EIP Plus developed by Hundred Plus has a Weak Password Recovery Mechanism vulnerability, allowing unauthenticated remote attacker to pred...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-640
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-10)

> EIP Plus developed by Hundred Plus has a Weak Password Recovery Mechanism vulnerability, allowing unauthenticated remote attacker to predict or brute-force the 'forgot password' link, thereby successfully resetting any user's password.

### CVE-2025-64513
**Milvus is an open-source vector database built for generative AI applications.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-10)

> Milvus is an open-source vector database built for generative AI applications. An unauthenticated attacker can exploit a vulnerability in versions prior to 2.4.24, 2.5.21, and 2.6.5 to bypass all authentication mechanisms in the Milvus Proxy component, gaining full administrative…

### CVE-2025-64522
**charm soft_serve SSRF**
- **Signals:** CVSS
- **Asset:** charm soft_serve
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T17:54:07.507
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-10)

> Soft Serve is a self-hostable Git server for the command line. Versions prior to 0.11.1 have a SSRF vulnerability where webhook URLs are not validated, allowing repository administrators to create webhooks targeting internal services, private networks, and cloud metadata endpoint…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-10*
