# Daily Threat Intelligence — January 22, 2026

**Digest window (UTC):** 2026-01-22
**Generated:** 2026-06-02T07:34:15Z

## Threat brief

Synacor Zimbra Collaboration Suite (ZCS) added to CISA KEV — confirmed in-the-wild exploitation. · Lfprojects Mlflow — exploitation likelihood rose sharply (EPSS 22% → 33% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Synacor Zimbra Collaboration Suite (ZCS) added to CISA KEV — confirmed in-the-wild exploitation.
- Lfprojects Mlflow — exploitation likelihood rose sharply (EPSS 22% → 33% · rising (+11%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2025-34026
**Versa Concerto Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** versa-networks concerto
- **Attack:** Auth Bypass
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T18:39:24.063
- **CWE:** CWE-288
- **Risk score:** 88
- **KEV:** added 2026-01-22

> The Versa Concerto SD-WAN orchestration platform is vulnerable to an authentication bypass in the Traefik reverse proxy configuration, allowing at attacker to access administrative endpoints. The internal Actuator endpoint can be leveraged for access to heap dumps and trace logs.…

### CVE-2023-6568
**lfprojects mlflow XSS**
- **Signals:** EPSS
- **Asset:** lfprojects mlflow
- **Attack:** XSS
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:44:07.173
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 22.1% (2025-11-21) → 33.4% (2026-01-22), Δ +11.2%**

> A reflected Cross-Site Scripting (XSS) vulnerability exists in the mlflow/mlflow repository, specifically within the handling of the Content-Type header in POST requests. An attacker can inject malicious JavaScript code into the Content-Type header, which is then improperly refle…

### CVE-2026-24306
**microsoft azure_front_door privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_front_door
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T13:44:45.297
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-22)

> Improper access control in Azure Front Door (AFD) allows an unauthorized attacker to elevate privileges over a network.

### CVE-2009-4107
**amplusnet invisible_browsing Buffer Overflow**
- **Signals:** EPSS
- **Asset:** amplusnet invisible_browsing
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 5.0% (2025-04-21) → 15.1% (2026-01-22), Δ +10.0%**

> Buffer overflow in Invisible Browsing 5.0.52 allows user-assisted remote attackers to execute arbitrary code via a crafted .ibkey file containing a long string.

### CVE-2025-31125
**Vite Vitejs Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** vitejs vite
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T18:39:55.027
- **CWE:** CWE-200
- **Risk score:** 88
- **KEV:** added 2026-01-22

> Vite is a frontend tooling framework for javascript. Vite exposes content of non-allowed files using ?inline&import or ?raw?import. Only apps explicitly exposing the Vite dev server to the network (using --host or server.host config option) are affected. This vulnerability is fix…

### CVE-2025-54313
**Prettier eslint-config-prettier Embedded Malicious Code Vulnerability**
- **Signals:** KEV
- **Asset:** prettier eslint-config-prettier
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T18:33:09.503
- **CWE:** CWE-506
- **Risk score:** 88
- **KEV:** added 2026-01-22

> eslint-config-prettier 8.10.1, 9.1.1, 10.1.6, and 10.1.7 has embedded malicious code for a supply chain compromise. Installing an affected package executes an install.js file that launches the node-gyp.dll malware on Windows.

### CVE-2025-54816
**evmapa evmapa Privilege Escalation**
- **Signals:** CVSS
- **Asset:** evmapa evmapa
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T19:56:13.070
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-22)

> This vulnerability occurs when a WebSocket endpoint does not enforce 
proper authentication mechanisms, allowing unauthorized users to 
establish connections. As a result, attackers can exploit this weakness 
to gain unauthorized access to sensitive data or perform unauthorized 
…

### CVE-2025-56590
**apryse html2pdf**
- **Signals:** CVSS
- **Asset:** apryse html2pdf
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T15:01:49.683
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-22)

> An issue was discovered in the InsertFromURL() function of the Apryse HTML2PDF SDK thru 11.10. This vulnerability could allow an attacker to execute arbitrary operating system commands on the local server.

### CVE-2025-68645
**Synacor Zimbra Collaboration Suite (ZCS) PHP Remote File Inclusion Vulnerability**
- **Signals:** KEV
- **Asset:** synacor zimbra_collaboration_suite
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T18:39:33.290
- **CWE:** CWE-98
- **Risk score:** 88
- **KEV:** added 2026-01-22

> A Local File Inclusion (LFI) vulnerability exists in the Webmail Classic UI of Zimbra Collaboration (ZCS) 10.0 and 10.1 because of improper handling of user-supplied request parameters in the RestFilter servlet. An unauthenticated remote attacker can craft requests to the /h/rest…

### CVE-2026-1201
**An Authorization Bypass Through User-Controlled Key vulnerability in Hubitat Elevation home automation controllers prior to version 2.4.2...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-22)

> An Authorization Bypass Through User-Controlled Key vulnerability in Hubitat Elevation home automation controllers prior to version 2.4.2.157 could allow a remote authenticated user to control connected devices outside of their authorized scope via client-side request manipulatio…

### CVE-2026-20750
**gitea gitea**
- **Signals:** CVSS
- **Asset:** gitea gitea
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T21:48:07.563
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-22)

> Gitea does not properly validate project ownership in organization project operations. A user with project write access in one organization may be able to modify projects belonging to a different organization.

### CVE-2026-20897
**gitea gitea**
- **Signals:** CVSS
- **Asset:** gitea gitea
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T22:02:20.170
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-22)

> Gitea does not properly validate repository ownership when deleting Git LFS locks. A user with write access to one repository may be able to delete LFS locks belonging to other repositories.

### CVE-2026-20912
**gitea gitea**
- **Signals:** CVSS
- **Asset:** gitea gitea
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T22:03:58.330
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-22)

> Gitea does not properly validate repository ownership when linking attachments to releases. An attachment uploaded to a private repository could potentially be linked to a release in a different public repository, making it accessible to unauthorized users.

### CVE-2026-21264
**microsoft account XSS**
- **Signals:** CVSS
- **Asset:** microsoft account
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T12:58:31.007
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-22)

> Improper neutralization of input during web page generation ('cross-site scripting') in Microsoft Account allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-24305
**microsoft entra_id privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft entra_id
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T12:46:12.437
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-22)

> Azure Entra ID Elevation of Privilege Vulnerability

### CVE-2026-24307
**microsoft 365_copilot**
- **Signals:** CVSS
- **Asset:** microsoft 365_copilot
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T17:29:54.847
- **CWE:** CWE-1287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-22)

> Improper validation of specified type of input in M365 Copilot allows an unauthorized attacker to disclose information over a network.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-22*
