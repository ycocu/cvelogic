# Daily Threat Intelligence — June 18, 2026

**Digest window (US Eastern, NVD):** 2026-06-18
**Generated:** 2026-06-21T09:42:47Z

## Threat brief

Splunk Enterprise added to CISA KEV — confirmed in-the-wild exploitation. · Linux Kernel — exploitation likelihood rose sharply (EPSS 76% → 94% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Splunk Enterprise added to CISA KEV — confirmed in-the-wild exploitation.
- Linux Kernel — exploitation likelihood rose sharply (EPSS 76% → 94% · rising (+18%)).
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

### CVE-2026-20253
**Splunk Enterprise Missing Authentication for Critical Function Vulnerability**
- **Signals:** KEV
- **Asset:** splunk splunk
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-10
- **NVD modified:** 2026-06-19
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2026-06-18

> In Splunk Enterprise 10.2 versions below 10.2.4 and 10 versions below 10.0.7, an unauthenticated user could create or truncate arbitrary files through a PostgreSQL sidecar service endpoint. The vulnerability exists because the PostgreSQL sidecar service endpoint lacks authenticat…

### CVE-2026-31431
**Linux Kernel Incorrect Resource Transfer Between Spheres Vulnerability**
- **Signals:** EPSS
- **Asset:** linux linux_kernel
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD published:** 2026-04-22
- **NVD modified:** 2026-06-17
- **CWE:** CWE-669
- **Risk score:** 83
- **EPSS 75.5% (2026-06-15) → 94.0% (2026-06-18), Δ +18.5%**

> In the Linux kernel, the following vulnerability has been resolved:

crypto: algif_aead - Revert to operating out-of-place

This mostly reverts commit 72548b093ee3 except for the copying of
the associated data.

There is no benefit in operating in-place in algif_aead since the
so…

### CVE-2026-49257
**mcp-pinot is a Python-based Model Context Protocol (MCP) server for interacting with Apache Pinot.**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-18)

> mcp-pinot is a Python-based Model Context Protocol (MCP) server for interacting with Apache Pinot. In versions 3.0.1 and below, mcp-pinot defaults to running an HTTP MCP server bound to 0.0.0.0:8080 with no authentication enabled. All MCP tools, including SQL query execution, sch…

### CVE-2026-12045
**Read-only transaction bypass in the pgAdmin 4 AI Assistant allows an attacker who can influence database content that the assistant reads...**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-18)

> Read-only transaction bypass in the pgAdmin 4 AI Assistant allows an attacker who can influence database content that the assistant reads to execute arbitrary SQL with the privileges of the pgAdmin user's database role.

The AI Assistant's execute_sql_query tool runs LLM-generate…

### CVE-2026-12046
**Two state-mutating endpoints in pgAdmin 4's SQL Editor blueprint -- DELETE /sqleditor/close/<trans_id> and POST /sqleditor/initialize/sql...**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.5
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-18)

> Two state-mutating endpoints in pgAdmin 4's SQL Editor blueprint -- DELETE /sqleditor/close/<trans_id> and POST /sqleditor/initialize/sqleditor/update_connection/<sgid>/<sid>/<did> -- were the only routes in the module missing the @pga_login_required decorator. Both reach a pickl…

### CVE-2026-12048
**Stored cross-site scripting in pgAdmin 4's error-rendering and plan-node-rendering paths.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-18)

> Stored cross-site scripting in pgAdmin 4's error-rendering and plan-node-rendering paths. Text returned by a PostgreSQL server (ErrorResponse messages, including object names quoted back inside relation-does-not-exist errors and inside EXPLAIN Recheck Cond / Exact Heap Blocks fie…

### CVE-2026-40624
**Improper input validation in AVer PTC500S, PTC115, PTC500+, and PTC115+ cameras may allow a remote, unauthenticated attacker to achieve a...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-552
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-18)

> Improper input validation in AVer PTC500S, PTC115, PTC500+, and PTC115+ 
cameras may allow a remote, unauthenticated attacker to achieve 
arbitrary code execution via a specially crafted web request.

### CVE-2026-47647
**Improper access control in Microsoft Dynamics 365 allows an authorized attacker to elevate privileges over a network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-18)

> Improper access control in Microsoft Dynamics 365 allows an authorized attacker to elevate privileges over a network.

### CVE-2026-47846
**Bitnami Cassandra container images are affected by a retained default superuser vulnerability.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-18)

> Bitnami Cassandra container images are affected by a retained default superuser vulnerability. When a custom administrator account is configured via the CASSANDRA_USER environment variable, the container initialization script creates the new superuser account but fails to drop th…

### CVE-2026-49252
**deepstream is a server that allows clients and backend services to sync data, send messages and make rpcs at scale.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.9
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-18)

> deepstream is a server that allows clients and backend services to sync data, send messages and make rpcs at scale. Versions prior to 10.0.5  are vulnerable to Prototype Pollution. Exploitation can lead to potential privilege escalation from any authenticated user with write perm…

### CVE-2026-49454
**Relyra is a strict-by-default SAML 2.0 Service Provider library for Elixir and Phoenix.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-18)

> Relyra is a strict-by-default SAML 2.0 Service Provider library for Elixir and Phoenix. Versions 1.0.0 and 1.1.0 accept forged SAML signatures because SignatureValue was not cryptographically verified before the library returned a successful authentication result. The XMLDSig tru…

### CVE-2026-54130
**Missing authentication for critical function in M365 Copilot allows an unauthorized attacker to disclose information over a network.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-18
- **NVD modified:** 2026-06-18
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-18)

> Missing authentication for critical function in M365 Copilot allows an unauthorized attacker to disclose information over a network.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-18*
