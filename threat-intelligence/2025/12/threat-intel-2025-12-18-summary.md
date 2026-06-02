# Daily Threat Intelligence — December 18, 2025

**Digest window (UTC):** 2025-12-18
**Generated:** 2026-06-02T07:34:00Z

## Threat brief

Dbsoftlab Vimp X — exploitation likelihood rose sharply (EPSS 6.9% → 20% · rising (+14%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Dbsoftlab Vimp X — exploitation likelihood rose sharply (EPSS 6.9% → 20% · rising (+14%)).
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

### CVE-2008-4750
**dbsoftlab vimp_x Buffer Overflow**
- **Signals:** EPSS
- **Asset:** dbsoftlab vimp_x
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 6.9% (2025-12-17) → 20.5% (2025-12-18), Δ +13.5%**

> Stack-based buffer overflow in the VImpX.VImpAX ActiveX control (VImpX.ocx) 4.8.8.0 in DB Software Laboratory VImp X, possibly 4.7.7, allows remote attackers to execute arbitrary code via a long LogFile property.

### CVE-2025-65041
**microsoft partner_center privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft partner_center
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-06T16:05:51.513
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-18)

> Improper authorization in Microsoft Partner Center allows an unauthorized attacker to elevate privileges over a network.

### CVE-2025-65037
**microsoft azure_container_apps**
- **Signals:** CVSS
- **Asset:** microsoft azure_container_apps
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T21:55:28.097
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-18)

> Improper control of generation of code ('code injection') in Azure Container Apps allows an unauthorized attacker to execute code over a network.

### CVE-2023-53941
**easyphp webserver Command Injection**
- **Signals:** CVSS
- **Asset:** easyphp webserver
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-26T16:55:17.263
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-18)

> EasyPHP Webserver 14.1 contains an OS command injection vulnerability that allows unauthenticated attackers to execute arbitrary system commands by injecting malicious payloads through the app_service_control parameter. Attackers can send POST requests to /index.php?zone=settings…

### CVE-2023-53942
**leefish file_thingie**
- **Signals:** CVSS
- **Asset:** leefish file_thingie
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T17:22:07.157
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-18)

> File Thingie 2.5.7 contains an authenticated file upload vulnerability that allows remote attackers to upload malicious PHP zip archives to the web server. Attackers can create a custom PHP payload, upload and unzip it, and then execute arbitrary system commands through a crafted…

### CVE-2025-56157
**langgenius dify**
- **Signals:** CVSS
- **Asset:** langgenius dify
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-29T18:16:07.950
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-18)

> Default credentials in Dify thru 1.5.1. PostgreSQL username and password specified in the docker-compose.yaml file included in its source code. NOTE: the Supplier reports that the Docker configuration does not make PostgreSQL (on TCP port 5432) exposed by default in version 1.0.1…

### CVE-2025-63388
**langgenius dify**
- **Signals:** CVSS
- **Asset:** langgenius dify
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-01-28T17:16:07.980
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-18)

> A Cross-Origin Resource Sharing (CORS) misconfiguration vulnerability exists in Dify v1.9.1 in the /console/api/system-features endpoint. The endpoint implements an overly permissive CORS policy that reflects arbitrary Origin headers and sets Access-Control-Allow-Credentials: tru…

### CVE-2025-63389
**ollama ollama Auth Bypass**
- **Signals:** CVSS
- **Asset:** ollama ollama
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-22T18:16:43.500
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-18)

> A critical authentication bypass vulnerability exists in Ollama platform's API endpoints in versions prior to and including v0.12.3. The platform exposes multiple API endpoints without requiring authentication, enabling remote attackers to perform unauthorized model management op…

### CVE-2025-64236
**Authentication Bypass Using an Alternate Path or Channel vulnerability in AmentoTech Tuturn tuturn allows Authentication Abuse.This issue...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:35:05.857
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-18)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in AmentoTech Tuturn tuturn allows Authentication Abuse.This issue affects Tuturn: from n/a through < 3.6.

### CVE-2025-64663
**microsoft azure_language privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_language
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-16T19:53:36.677
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-18)

> Custom Question Answering Elevation of Privilege Vulnerability

### CVE-2025-68398
**weblate weblate**
- **Signals:** CVSS
- **Asset:** weblate weblate
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-02-06T20:16:08.620
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-18)

> Weblate is a web based localization tool. In versions prior to 5.15.1, it was possible to overwrite Git configuration remotely and override some of its behavior. Version 5.15.1 fixes the issue.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-18*
