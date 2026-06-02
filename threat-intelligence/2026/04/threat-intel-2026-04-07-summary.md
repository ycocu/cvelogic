# Daily Threat Intelligence — April 07, 2026

**Digest window (UTC):** 2026-04-07
**Generated:** 2026-06-02T07:34:52Z

## Threat brief

Microsoft Office Web Components — exploitation likelihood rose sharply (EPSS 19% → 29% · rising (+10%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Office Web Components — exploitation likelihood rose sharply (EPSS 19% → 29% · rising (+10%)).
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

### CVE-2002-1339
**microsoft office_web_components**
- **Signals:** EPSS
- **Asset:** microsoft office_web_components
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 76
- **EPSS 18.8% (2025-10-23) → 29.0% (2026-04-07), Δ +10.2%**

> The "XMLURL" property in the Spreadsheet component of Office Web Components (OWC) 10 follows redirections, which allows remote attackers to determine the existence of local files based on exceptions, or to read WorkSheet XML files.

### CVE-2002-1340
**microsoft office_web_components**
- **Signals:** EPSS
- **Asset:** microsoft office_web_components
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 76
- **EPSS 18.8% (2025-10-23) → 29.0% (2026-04-07), Δ +10.2%**

> The "ConnectionFile" property in the DataSourceControl component in Office Web Components (OWC) 10 allows remote attackers to determine the existence of local files by detecting an exception.

### CVE-2026-31789
**openssl openssl Code Execution**
- **Signals:** CVSS
- **Asset:** openssl openssl
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-12T13:17:34.570
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-07)

> Issue summary: Converting an excessively large OCTET STRING value to
a hexadecimal string leads to a heap buffer overflow on 32 bit platforms.

Impact summary: A heap buffer overflow may lead to a crash or possibly
an attacker controlled code execution or other undefined behavior…

### CVE-2025-69515
**An issue in JXL 9 Inch Car Android Double Din Player Android v12.0 allows attackers to force the infotainment system into accepting falsi...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-09T15:16:08.863
- **CWE:** CWE-941
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-07)

> An issue in JXL 9 Inch Car Android Double Din Player Android v12.0 allows attackers to force the infotainment system into accepting falsified GPS signals as legitimate, resulting in the device reporting an incorrect or static location.

### CVE-2026-33439
**openidentityplatform openam RCE**
- **Signals:** CVSS
- **Asset:** openidentityplatform openam
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T23:34:32.640
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-07)

> Open Access Management (OpenAM) is an access management solution. Prior to 16.0.6, OpenIdentityPlatform OpenAM is vulnerable to pre-authentication Remote Code Execution (RCE) via unsafe Java deserialization of the jato.clientSession HTTP parameter. This bypasses the WhitelistObje…

### CVE-2026-34078
**flatpak flatpak Code Execution**
- **Signals:** CVSS
- **Asset:** flatpak flatpak
- **Attack:** Code Execution
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T17:50:18.043
- **CWE:** CWE-61
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-07)

> Flatpak is a Linux application sandboxing and distribution framework. Prior to 1.16.4, the Flatpak portal accepts paths in the sandbox-expose options which can be app-controlled symlinks pointing at arbitrary paths. Flatpak run mounts the resolved host path in the sandbox. This g…

### CVE-2026-34580
**botan_project botan**
- **Signals:** CVSS
- **Asset:** botan_project botan
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-17T20:30:02.877
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-07)

> Botan is a C++ cryptography library. In 3.11.0, the function Certificate_Store::certificate_known had a misleading name; it would return true if any certificate in the store had a DN (and subject key identifier, if set) matching that of the argument. It did not check that the cer…

### CVE-2026-39322
**polarlearn polarlearn**
- **Signals:** CVSS
- **Asset:** polarlearn polarlearn
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T18:44:29.327
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-07)

> PolarLearn is a free and open-source learning program. In 0-PRERELEASE-15 and earlier, POST /api/v1/auth/sign-in creates a valid session for banned accounts before verifying the supplied password. That session is then accepted across authenticated /api routes, enabling account da…

### CVE-2026-39382
**dbt enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-16T14:57:08.337
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-07)

> dbt enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications. Inside the reusable workflow dbt-labs/actions/blob/main/.github/workflows/open-issue-in-repo.yml, the prep job uses peter-evans/find-comment…

### CVE-2026-39397
**delmaredigital payload-puck**
- **Signals:** CVSS
- **Asset:** delmaredigital payload-puck
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T20:29:13.700
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-07)

> @delmaredigital/payload-puck is a PayloadCMS plugin for integrating Puck visual page builder. Prior to 0.6.23, all /api/puck/* CRUD endpoint handlers registered by createPuckPlugin() called Payload's local API with the default overrideAccess: true, bypassing all collection-level …

### CVE-2026-39846
**b3log siyuan RCE**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T04:32:01.020
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-04-07)

> SiYuan is a personal knowledge management system. Prior to 3.6.4, a malicious note synced to another user can trigger remote code execution in the SiYuan Electron desktop client. The root cause is that table caption content is stored without safe escaping and later unescaped into…

### CVE-2026-39847
**emmett emmett Path Traversal**
- **Signals:** CVSS
- **Asset:** emmett emmett
- **Attack:** Path Traversal
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T04:31:28.903
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-07)

> Emmett is a full-stack Python web framework designed with simplicity. From 2.5.0 to before 2.8.1, the RSGI static handler for Emmett's internal assets (/__emmett__ paths) is vulnerable to path traversal attacks. An attacker can use ../ sequences (eg /__emmett__/../rsgi/handlers.p…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-07*
