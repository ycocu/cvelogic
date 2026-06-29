# Daily Threat Intelligence — June 26, 2026

**Digest window (US Eastern, NVD):** 2026-06-26
**Generated:** 2026-06-29T10:33:12Z

## Threat brief

Exploitation likelihood rose sharply (EPSS 35% → 47% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Exploitation likelihood rose sharply (EPSS 35% → 47% · rising (+12%)).
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

### CVE-2025-2011
**SQL Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD published:** 2025-05-06
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **Risk score:** 81
- **EPSS 35.1% (2026-06-21) → 46.7% (2026-06-26), Δ +11.6%**

> The Slider & Popup Builder by Depicter plugin for WordPress is vulnerable to generic SQL Injection via the ‘s' parameter in all versions up to, and including, 3.6.1 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL …

### CVE-2026-49869
**Kestra is an open-source, event-driven orchestration platform.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-26)

> Kestra is an open-source, event-driven orchestration platform. Prior to 1.0.45 and 1.3.21, AuthenticationFilter in Kestra OSS uses request.getPath().endsWith("/configs") to whitelist the public configuration endpoint from Basic Auth. Because the check is a suffix match rather tha…

### CVE-2026-53576
**Kestra is an open-source, event-driven orchestration platform.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-26)

> Kestra is an open-source, event-driven orchestration platform. Prior to 1.0.45 and 1.3.21, the authentication filter for the REST API (@Filter("/api/v1/**")) treats any request whose path ends in /configs as the public instance-config endpoint and forwards it without a credential…

### CVE-2026-28701
**Various versions of Daktronics Controller Firmware could allow authenticated and unauthenticated remote users to escape the intended dire...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-26)

> Various versions of Daktronics Controller Firmware could allow authenticated and unauthenticated remote users to escape the intended directory and enumerate arbitrary file system paths.

### CVE-2026-31928
**The DMP-5000 devices are shipped with a default administrative web account with weak authentication controls, which are not required to b...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-26)

> The DMP-5000 devices are shipped with a default administrative web account with weak authentication controls, which are not required to be changed during initial configuration or operation. Using these accounts provides full system access.

### CVE-2026-52780
**OpenProject is open-source, web-based project management software.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-27
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-26)

> OpenProject is open-source, web-based project management software. Prior to 17.3.3 and 17.4.1, cache store poisoning leads to Remote Code Execution (RCE). This vulnerability is fixed in 17.3.3 and 17.4.1.

### CVE-2026-52782
**OpenProject is open-source, web-based project management software.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-26)

> OpenProject is open-source, web-based project management software. Prior to 17.3.3 and 17.4.1, there is an IDOR through /projects/<A>/settings/project_storages/<A_ps_id> via PATCH parameter "storages_project_storage[project_folder_id]" leads to Access to Unauthorized Resources. A…

### CVE-2026-52785
**OpenProject is open-source, web-based project management software.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-26)

> OpenProject is open-source, web-based project management software. Prior to 17.3.3 and 17.4.1, there is a SQL injection in timestamps functionality. OpenProject baseline comparison allows callers to request historic work-package attributes using the timestamps parameter. This vul…

### CVE-2026-53309
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-28
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-26)

> In the Linux kernel, the following vulnerability has been resolved:

ocfs2/dlm: fix off-by-one in dlm_match_regions() region comparison

The local-vs-remote region comparison loop uses '<=' instead of '<',
causing it to read one entry past the valid range of qr_regions.  The
othe…

### CVE-2026-54350
**Budibase is an open-source low-code platform.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-26
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-26)

> Budibase is an open-source low-code platform. Prior to 3.39.12,  an unauthenticated visitor of any published Budibase app reads every document of the backing MongoDB, CouchDB, Elasticsearch, DynamoDB-PartiQL, or REST-with-JSON-body collection and, where the builder has published …

### CVE-2026-54352
**Budibase is an open-source low-code platform.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Received
- **NVD published:** 2026-06-26
- **NVD modified:** 2026-06-27
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-26)

> Budibase is an open-source low-code platform. Prior to 3.39.9, `POST /api/pwa/process-zip` at packages/server/src/api/routes/static.ts:24 accepts a builder-uploaded .zip, extracts it with extract-zip@2.0.1 into a temp directory, then for each entry listed in icons.json validates …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-26*
