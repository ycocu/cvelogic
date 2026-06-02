# Daily Threat Intelligence — March 27, 2026

**Digest window (UTC):** 2026-03-27
**Generated:** 2026-06-02T07:34:46Z

## Threat brief

F5 BIG-IP added to CISA KEV — confirmed in-the-wild exploitation. · Microfocus Rumba — exploitation likelihood rose sharply (EPSS 34% → 51% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- F5 BIG-IP added to CISA KEV — confirmed in-the-wild exploitation.
- Microfocus Rumba — exploitation likelihood rose sharply (EPSS 34% → 51% · rising (+18%)).
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

### CVE-2025-53521
**F5 BIG-IP Stack-Based Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** f5 big-ip_access_policy_manager
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T19:00:01.543
- **CWE:** CWE-121
- **Risk score:** 88
- **KEV:** added 2026-03-27

> When a BIG-IP APM access policy is configured on a virtual server, specific malicious traffic can lead to Remote Code Execution (RCE).  

Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

### CVE-2016-5228
**microfocus rumba Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microfocus rumba
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 33.7% (2025-03-30) → 51.2% (2026-03-27), Δ +17.5%**

> Stack-based buffer overflow in the PlayMacro function in ObjectXMacro.ObjectXMacro in WdMacCtl.ocx in Micro Focus Rumba 9.x before 9.3 HF 11997 and 9.4.x before 9.4 HF 12815 allows remote attackers to execute arbitrary code via a long MacroName argument. NOTE: some references men…

### CVE-2026-30533
**oretnom23 online_food_ordering_system SQL Injection**
- **Signals:** CVSS
- **Asset:** oretnom23 online_food_ordering_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T18:17:38.850
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-27)

> A SQL Injection vulnerability exists in SourceCodester Online Food Ordering System v1.0 in the admin/manage_product.php file via the "id" parameter.

### CVE-2019-25651
**Ubiquiti UniFi Network Controller prior to 5.10.12 (excluding 5.6.42), UAP FW prior to 4.0.6, UAP-AC, UAP-AC v2, and UAP-AC Outdoor FW pr...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-327
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-27)

> Ubiquiti UniFi Network Controller prior to 5.10.12 (excluding 5.6.42), UAP FW prior to 4.0.6, UAP-AC, UAP-AC v2, and UAP-AC Outdoor FW prior to 3.8.17, USW FW prior to 4.0.6, USG FW prior to 4.4.34 uses AES-CBC encryption for device-to-controller communication, which contains cry…

### CVE-2026-33867
**wwbn avideo SQL Injection**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T16:43:15.033
- **CWE:** CWE-312
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-27)

> WWBN AVideo is an open source video platform. In versions up to and including 26.0, AVideo allows content owners to password-protect individual videos. The video password is stored in the database in plaintext — no hashing, salting, or encryption is applied. If an attacker gains …

### CVE-2026-33873
**langflow langflow**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T17:03:54.760
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-27)

> Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to version 1.9.0, the Agentic Assistant feature in Langflow executes LLM-generated Python code during its validation phase. Although this phase appears intended to validate generated component co…

### CVE-2026-33875
**gematik authenticator**
- **Signals:** CVSS
- **Asset:** gematik authenticator
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-03T16:16:40.093
- **CWE:** CWE-940
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-27)

> Gematik Authenticator securely authenticates users for login to digital health applications. Versions prior to 4.16.0 are vulnerable to authentication flow hijacking, potentially allowing attackers to authenticate with the identities of victim users who click on a malicious deep …

### CVE-2026-33937
**handlebarsjs handlebars**
- **Signals:** CVSS
- **Asset:** handlebarsjs handlebars
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T17:49:05.807
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-27)

> Handlebars provides the power necessary to let users build semantic templates. In versions 4.0.0 through 4.7.8, `Handlebars.compile()` accepts a pre-parsed AST object in addition to a template string. The `value` field of a `NumberLiteral` AST node is emitted directly into the ge…

### CVE-2026-33976
**streetwriters notesnook_desktop RCE**
- **Signals:** CVSS
- **Asset:** streetwriters notesnook_desktop
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T18:21:36.440
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-27)

> Notesnook is a note-taking app. Prior to version 3.3.11 on Web/Desktop and 3.3.17 on Android/iOS, a stored XSS in the Web Clipper rendering flow can be escalated to remote code execution in the desktop app. The root cause is that the clipper preserves attacker-controlled attribut…

### CVE-2026-33992
**pyload pyload SSRF**
- **Signals:** CVSS
- **Asset:** pyload pyload
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T14:49:16.640
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-27)

> pyLoad is a free and open-source download manager written in Python. Prior to version 0.5.0b3.dev97, PyLoad's download engine accepts arbitrary URLs without validation, enabling Server-Side Request Forgery (SSRF) attacks. An authenticated attacker can exploit this to access inter…

### CVE-2026-34205
**Home Assistant is open source home automation software that puts local control and privacy first.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-30T13:26:29.793
- **CWE:** CWE-923
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-27)

> Home Assistant is open source home automation software that puts local control and privacy first. Home Assistant apps (formerly add-ons) configured with host network mode expose unauthenticated endpoints bound to the internal Docker bridge interface to the local network. On Linux…

### CVE-2026-34374
**wwbn avideo SQL injection**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **Attack:** SQL injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T18:49:13.140
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-27)

> WWBN AVideo is an open source video platform. In versions up to and including 26.0, the `Live_schedule::keyExists()` method constructs a SQL query by interpolating a stream key directly into the query string without parameterization. This method is called as a fallback from `Live…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-27*
