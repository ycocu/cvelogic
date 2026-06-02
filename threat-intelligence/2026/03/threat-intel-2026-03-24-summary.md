# Daily Threat Intelligence — March 24, 2026

**Digest window (UTC):** 2026-03-24
**Generated:** 2026-06-02T07:34:44Z

## Threat brief

Canonical Bind — exploitation likelihood rose sharply (EPSS 55% → 69% · rising (+14%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Canonical Bind — exploitation likelihood rose sharply (EPSS 55% → 69% · rising (+14%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2016-1285
**canonical bind DoS**
- **Signals:** EPSS
- **Asset:** isc bind
- **Attack:** DoS
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 81
- **EPSS 55.0% (2026-03-04) → 69.0% (2026-03-24), Δ +14.0%**

> named in ISC BIND 9.x before 9.9.8-P4 and 9.10.x before 9.10.3-P4 does not properly handle DNAME records when parsing fetch reply messages, which allows remote attackers to cause a denial of service (assertion failure and daemon exit) via a malformed packet to the rndc (aka contr…

### CVE-2009-1627
**sdp_multimedia streaming_download_project Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sdp_multimedia streaming_download_project
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 27.6% (2026-01-05) → 39.6% (2026-03-24), Δ +12.0%**

> Stack-based buffer overflow in Streaming Download Project (SDP) Downloader 2.3.0 allows remote attackers to execute arbitrary code via a long .asf URL in the HREF attribute of a REF element in a .asx file.

### CVE-2026-4725
**mozilla firefox Use-After-Free**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:44.903
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-24)

> Sandbox escape due to use-after-free in the Graphics: Canvas2D component. This vulnerability was fixed in Firefox 149 and Thunderbird 149.

### CVE-2025-33244
**NVIDIA APEX for Linux contains a vulnerability where an unauthorized attacker could cause a deserialization of untrusted data.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-25T15:41:58.280
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-24)

> NVIDIA APEX for Linux contains a vulnerability where an unauthorized attacker could cause a deserialization of untrusted data. This vulnerability affects environments that use PyTorch versions earlier than 2.6. A successful exploit of this vulnerability might lead to code executi…

### CVE-2026-2417
**A Missing Authentication for Critical Function vulnerability in Pharos Controls Mosaic Show Controller firmware version 2.15.3 could allo...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-25T15:41:58.280
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-24)

> A Missing Authentication for Critical Function vulnerability in Pharos Controls Mosaic Show Controller firmware version 2.15.3 could allow an unauthenticated attacker to bypass authentication and execute arbitrary commands with root privileges.

### CVE-2026-33322
**minio minio**
- **Signals:** CVSS
- **Asset:** minio minio
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T19:05:00.710
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-24)

> MinIO is a high-performance object storage system. From RELEASE.2022-11-08T05-27-07Z to before RELEASE.2026-03-17T21-25-16Z, a JWT algorithm confusion vulnerability in MinIO's OpenID Connect authentication allows an attacker who knows the OIDC ClientSecret to forge arbitrary iden…

### CVE-2026-33340
**lollms lollms_web_ui SSRF**
- **Signals:** CVSS
- **Asset:** lollms lollms_web_ui
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-20T20:22:05.330
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-24)

> LoLLMs WEBUI provides the Web user interface for Lord of Large Language and Multi modal Systems. A critical Server-Side Request Forgery (SSRF) vulnerability has been identified in all known existing versions of `lollms-webui`. The `@router.post("/api/proxy")` endpoint allows unau…

### CVE-2026-33419
**minio minio**
- **Signals:** CVSS
- **Asset:** minio minio
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T19:00:39.203
- **CWE:** CWE-204
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-24)

> MinIO is a high-performance object storage system. Prior to RELEASE.2026-03-17T21-25-16Z, MinIO AIStor's STS (Security Token Service) AssumeRoleWithLDAPIdentity endpoint is vulnerable to LDAP credential brute-forcing due to two combined weaknesses: (1) distinguishable error respo…

### CVE-2026-4721
**mozilla firefox Memory Corruption**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:44.200
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-24)

> Memory safety bugs present in Firefox ESR 115.33, Firefox ESR 140.8, Thunderbird ESR 140.8, Firefox 148 and Thunderbird 148. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary cod…

### CVE-2026-4723
**mozilla firefox Use-After-Free**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:44.557
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-24)

> Use-after-free in the JavaScript Engine component. This vulnerability was fixed in Firefox 149 and Thunderbird 149.

### CVE-2026-4724
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:44.733
- **CWE:** CWE-758
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-24)

> Undefined behavior in the Audio/Video component. This vulnerability was fixed in Firefox 149 and Thunderbird 149.

### CVE-2026-4729
**mozilla firefox Memory Corruption**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:45.597
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-24)

> Memory safety bugs present in Firefox 148 and Thunderbird 148. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability was fixed in Firefox 149 and Thunderbird…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-24*
