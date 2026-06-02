# Daily Threat Intelligence — February 09, 2026

**Digest window (UTC):** 2026-02-09
**Generated:** 2026-06-02T07:34:23Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2026-25893
**frangoteam fuxa Auth Bypass**
- **Signals:** CVSS
- **Asset:** frangoteam fuxa
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:35:25.737
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-09)

> FUXA is a web-based Process Visualization (SCADA/HMI/Dashboard) software. Prior to 1.2.10, an authentication bypass vulnerability in FUXA allows an unauthenticated, remote attacker to gain administrative access via the heartbeat refresh API and execute arbitrary code on the serve…

### CVE-2026-25885
**polarlearn polarlearn**
- **Signals:** CVSS
- **Asset:** polarlearn polarlearn
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T20:47:36.330
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-09)

> PolarLearn is a free and open-source learning program. In 0-PRERELEASE-16 and earlier, the group chat WebSocket at wss://polarlearn.nl/api/v1/ws can be used without logging in. An unauthenticated client can subscribe to any group chat by providing a group UUID, and can also send …

### CVE-2026-25895
**frangoteam fuxa Path Traversal**
- **Signals:** CVSS
- **Asset:** frangoteam fuxa
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:32:48.753
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-02-09)

> FUXA is a web-based Process Visualization (SCADA/HMI/Dashboard) software. A path traversal vulnerability in FUXA allows an unauthenticated, remote attacker to write arbitrary files to arbitrary locations on the server filesystem. This affects FUXA through version 1.2.9. This issu…

### CVE-2026-25812
**prasklatechnology placipy CSRF**
- **Signals:** CVSS
- **Asset:** prasklatechnology placipy
- **Attack:** CSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T20:10:05.293
- **CWE:** CWE-352
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-09)

> PlaciPy is a placement management system designed for educational institutions. In version 1.0.0, the application enables credentialed CORS requests but does not implement any CSRF protection mechanism.

### CVE-2026-25814
**prasklatechnology placipy**
- **Signals:** CVSS
- **Asset:** prasklatechnology placipy
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T20:05:44.870
- **CWE:** CWE-74
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-09)

> PlaciPy is a placement management system designed for educational institutions. In version 1.0.0, User-controlled query parameters are passed directly into DynamoDB query/filter construction without validation or sanitization.

### CVE-2026-25875
**prasklatechnology placipy privilege escalation**
- **Signals:** CVSS
- **Asset:** prasklatechnology placipy
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:42:50.187
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-09)

> PlaciPy is a placement management system designed for educational institutions. In version 1.0.0, The admin authorization middleware trusts client-controlled JWT claims (role and scope) without enforcing server-side role verification.

### CVE-2026-25881
**nyariv sandboxjs**
- **Signals:** CVSS
- **Asset:** nyariv sandboxjs
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T18:07:12.937
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-02-09)

> SandboxJS is a JavaScript sandboxing library. Prior to 0.8.31, a sandbox escape vulnerability allows sandboxed code to mutate host built-in prototypes by laundering the isGlobal protection flag through array literal intermediaries. When a global prototype reference (e.g., Map.pro…

### CVE-2026-25894
**frangoteam fuxa**
- **Signals:** CVSS
- **Asset:** frangoteam fuxa
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:33:42.000
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-02-09)

> FUXA is a web-based Process Visualization (SCADA/HMI/Dashboard) software. An insecure default configuration in FUXA allows an unauthenticated, remote attacker to gain administrative access and execute arbitrary code on the server. This affects FUXA through version 1.2.9 when auth…

### CVE-2026-25938
**frangoteam fuxa Auth Bypass**
- **Signals:** CVSS
- **Asset:** frangoteam fuxa
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:31:47.513
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-02-09)

> FUXA is a web-based Process Visualization (SCADA/HMI/Dashboard) software. From 1.2.8 through 1.2.10, an authentication bypass vulnerability in FUXA allows an unauthenticated, remote attacker to execute arbitrary code on the server when the Node-RED plugin is enabled. This has bee…

### CVE-2026-25939
**frangoteam fuxa privilege escalation**
- **Signals:** CVSS
- **Asset:** frangoteam fuxa
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:31:09.137
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-09)

> FUXA is a web-based Process Visualization (SCADA/HMI/Dashboard) software. From 1.2.8 through version 1.2.10, 
an authorization bypass vulnerability in the FUXA allows an unauthenticated, remote attacker to create and modify arbitrary schedulers, exposing connected ICS/SCADA envir…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-09*
