# Daily Threat Intelligence — May 08, 2026

**Digest window (UTC):** 2026-05-08
**Generated:** 2026-06-02T07:03:57Z

## Threat brief

BerriAI LiteLLM added to CISA KEV — confirmed in-the-wild exploitation. · Netgear Prosafe Network Management System — exploitation likelihood rose sharply (EPSS 11% → 59% · rising (+48%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- BerriAI LiteLLM added to CISA KEV — confirmed in-the-wild exploitation.
- Netgear Prosafe Network Management System — exploitation likelihood rose sharply (EPSS 11% → 59% · rising (+48%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2026-42208
**BerriAI LiteLLM SQL Injection Vulnerability**
- **Signals:** KEV
- **Asset:** litellm litellm
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:19:34.537
- **CWE:** CWE-89
- **Risk score:** 88
- **KEV:** added 2026-05-08

> LiteLLM is a proxy server (AI Gateway) to call LLM APIs in OpenAI (or native) format. From version 1.81.16 to before version 1.83.7, a database query used during proxy API key checks mixed the caller-supplied key value into the query text instead of passing it as a separate param…

### CVE-2021-27276
**netgear prosafe_network_management_system**
- **Signals:** EPSS
- **Asset:** netgear prosafe_network_management_system
- **CVSS max:** 7.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:57:44.733
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 10.7% (2026-03-31) → 59.0% (2026-05-08), Δ +48.3%**

> This vulnerability allows remote attackers to delete arbitrary files on affected installations of NETGEAR ProSAFE Network Management System 1.6.0.26. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The spec…

### CVE-2026-42298
**gitroom postiz privilege escalation**
- **Signals:** CVSS
- **Asset:** gitroom postiz
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T16:42:12.873
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-08)

> Postiz is an AI social media scheduling tool. Prior to commit da44801, a "Pwn Request" vulnerability in the Build and Publish PR Docker Image workflow (.github/workflows/pr-docker-build.yml) allows any unauthenticated user to execute arbitrary code during the Docker build process…

### CVE-2006-2458
**libextractor libextractor Buffer Overflow**
- **Signals:** EPSS
- **Asset:** libextractor libextractor
- **Attack:** Buffer Overflow
- **CVSS max:** 4.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 76
- **EPSS 19.1% (2025-04-20) → 31.0% (2026-05-08), Δ +11.8%**

> Multiple heap-based buffer overflows in Libextractor 0.5.13 and earlier allow remote attackers to execute arbitrary code via (1) the asf_read_header function in the ASF plugin (plugins/asfextractor.c), and (2) the parse_trak_atom function in the QT plugin (plugins/qtextractor.c).

### CVE-2021-35590
**netapp mysql_cluster privilege escalation**
- **Signals:** EPSS
- **Asset:** oracle mysql_cluster
- **Attack:** privilege escalation
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:12:35.990
- **CWE:** CWE-787
- **Risk score:** 80
- **EPSS 28.9% (2025-11-21) → 46.9% (2026-05-08), Δ +18.0%**

> Vulnerability in the MySQL Cluster product of Oracle MySQL (component: Cluster: General). Supported versions that are affected are 7.4.33 and prior, 7.5.23 and prior, 7.6.19 and prior and 8.0.26 and prior. Difficult to exploit vulnerability allows high privileged attacker with ac…

### CVE-2021-37573
**tiny_java_web_server_project tiny_java_web_server XSS**
- **Signals:** EPSS
- **Asset:** tiny_java_web_server_project tiny_java_web_server
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:15:27.223
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 24.2% (2026-03-09) → 51.9% (2026-05-08), Δ +27.8%**

> A reflected cross-site scripting (XSS) vulnerability in the web server TTiny Java Web Server and Servlet Container (TJWS) <=1.115 allows an adversary to inject malicious code on the server's "404 Page not Found" error page

### CVE-2026-38360
**Directory Traversal vulnerability in fohrloop dash-uploader v.0.1.0 through v.0.7.0a2 allows a remote attacker to execute arbitrary code...**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T15:10:27.993
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-08)

> Directory Traversal vulnerability in fohrloop dash-uploader v.0.1.0 through v.0.7.0a2 allows a remote attacker to execute arbitrary code via the dash_uploader/httprequesthandler.py, aseHttpRequestHandler.get_temp_root(), BaseHttpRequestHandler._post() components

### CVE-2026-42072
**Nornicdb is a distributed low-latency, Graph+Vector, Temporal MVCC with all sub-ms HNSW search, graph traversal, and writes.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:34:42.677
- **CWE:** CWE-1392
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-08)

> Nornicdb is a distributed low-latency, Graph+Vector, Temporal MVCC with all sub-ms HNSW search, graph traversal, and writes. Prior to version 1.0.42-hotfix, the --address CLI flag (and NORNICDB_ADDRESS / server.host config key) is plumbed through to the HTTP server correctly but …

### CVE-2026-42160
**Data Space Portal is an open-source Software as a Service (SaaS) solution designed to streamline Dataspace management.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T17:24:36.160
- **CWE:** CWE-602
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-08)

> Data Space Portal is an open-source Software as a Service (SaaS) solution designed to streamline Dataspace management. From version 2.1.1 to before version 7.3.2, there is insufficient authorization in the dataspace-portal backend regarding self-registered "PENDING" organization …

### CVE-2026-42193
**Plunk is an open-source email platform built on top of AWS SES.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T16:45:18.893
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-08)

> Plunk is an open-source email platform built on top of AWS SES. Prior to version 0.9.0, the /webhooks/sns endpoint accepts Amazon SNS notification payloads from unauthenticated requests without verifying the SNS signature, certificate, or topic ARN, meaning anyone can forge a val…

### CVE-2026-42287
**Emlog is an open source website building system.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T16:45:18.893
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-08)

> Emlog is an open source website building system. Prior to version 2.6.11, direct SQL injection in article creation and update functions allows attackers to execute arbitrary SQL commands, potentially leading to complete database compromise, data theft, or system destruction. This…

### CVE-2026-42302
**FastGPT is an AI Agent building platform.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T19:16:32.950
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-08)

> FastGPT is an AI Agent building platform. From version 4.14.10 to before version 4.14.13, the agent-sandbox component of FastGPT is vulnerable to unauthenticated Remote Code Execution (RCE). The startup script entrypoint.sh initializes code-server with the --auth none flag and bi…

### CVE-2026-42354
**sentry sentry**
- **Signals:** CVSS
- **Asset:** sentry sentry
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T14:43:16.687
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-08)

> Sentry is an error tracking and performance monitoring tool. From version 21.12.0 to before version 26.4.1, a critical vulnerability was discovered in the SAML SSO implementation of Sentry. The vulnerability allows an attacker to take over any user account by using a malicious SA…

### CVE-2026-42454
**Termix is a web-based server management platform with SSH terminal, tunneling, and file editing capabilities.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T16:40:53.150
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-08)

> Termix is a web-based server management platform with SSH terminal, tunneling, and file editing capabilities. Prior to version 2.1.0, all Docker container management endpoints in Termix interpolate the containerId URL path parameter and WebSocket message field directly into shell…

### CVE-2026-8178
**An issue exists in Amazon Redshift JDBC Driver versions prior to 2.2.2.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-12T14:13:03.510
- **CWE:** CWE-470
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-08)

> An issue exists in Amazon Redshift JDBC Driver versions prior to 2.2.2. Under certain conditions, the driver could load and execute arbitrary classes when processing JDBC connection URL parameters. An actor who can influence the connection URL could potentially execute code in th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-08*
