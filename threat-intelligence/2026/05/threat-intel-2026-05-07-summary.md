# Daily Threat Intelligence — May 07, 2026

**Digest window (UTC):** 2026-05-07
**Generated:** 2026-06-02T07:03:57Z

## Threat brief

Ivanti Endpoint Manager Mobile (EPMM) added to CISA KEV — confirmed in-the-wild exploitation. · Bludit: public exploit or PoC linked (RCE) · Maxum Development Corporation Rumpus Ftp Server — exploitation likelihood rose sharply (EPSS 6.9% → 24% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Endpoint Manager Mobile (EPMM) added to CISA KEV — confirmed in-the-wild exploitation.
- Bludit: public exploit or PoC linked (RCE)
- Maxum Development Corporation Rumpus Ftp Server — exploitation likelihood rose sharply (EPSS 6.9% → 24% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 5 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2026-6973
**Ivanti Endpoint Manager Mobile (EPMM) Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** RCE
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T19:18:39.910
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2026-05-07

> An Improper Input Validation in Ivanti EPMM before versions 12.6.1.1, 12.7.0.1, and 12.8.0.1 allows a remotely authenticated user with administrative access to achieve remote code execution.

### CVE-2025-34282
**thingsboard thingsboard SSRF**
- **Signals:** EXP
- **Asset:** thingsboard thingsboard
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:43:12.570
- **CWE:** CWE-918
- **Risk score:** 78
- **EXP:** ref published 2026-05-07

> ThingsBoard versions < 4.2.1 contain a server-side request forgery (SSRF) vulnerability in the dashboard's Image Upload Gallery feature. An attacker can upload a malicious SVG file that references a remote URL. If the server processes the SVG file in a way that parses external re…

### CVE-2007-0019
**maxum_development_corporation rumpus_ftp_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** maxum_development_corporation rumpus_ftp_server
- **Attack:** Buffer Overflow
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 81
- **EPSS 6.9% (2025-09-07) → 24.2% (2026-05-07), Δ +17.4%**

> Multiple heap-based buffer overflows in rumpusd in Rumpus 5.1 and earlier (1) allow remote authenticated users to execute arbitrary code via a long LIST command and other unspecified requests to the FTP service, and (2) allow remote attackers to execute arbitrary code via unspeci…

### CVE-2002-1156
**apache http_server**
- **Signals:** EPSS
- **Asset:** apache http_server
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 26.4% (2026-01-23) → 38.5% (2026-05-07), Δ +12.1%**

> Apache 2.0.42 allows remote attackers to view the source code of a CGI script via a POST request to a directory with both WebDAV and CGI enabled.

### CVE-2006-0710
**isode m-vault_server**
- **Signals:** EPSS
- **Asset:** isode m-vault_server
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 80
- **EPSS 6.2% (2025-03-30) → 17.2% (2026-05-07), Δ +11.0%**

> Double free vulnerability in isode.eddy in Isode M-Vault Server 11.3 allows remote attackers to execute arbitrary code via a crafted LDAP request, as demonstrated by ProtoVer Sample LDAP.

### CVE-2020-2036
**paloaltonetworks pan-os XSS**
- **Signals:** EPSS
- **Asset:** paloaltonetworks pan-os
- **Attack:** XSS
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:24:30.950
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 84
- **EPSS 60.7% (2026-05-03) → 77.6% (2026-05-07), Δ +16.8%**

> A reflected cross-site scripting (XSS) vulnerability exists in the PAN-OS management web interface. A remote attacker able to convince an administrator with an active authenticated session on the firewall management interface to click on a crafted link to that management web inte…

### CVE-2026-25099
**bludit bludit RCE**
- **Signals:** EXP
- **Asset:** bludit bludit
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-01T14:16:35.360
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2026-05-07

> Bludit’s API plugin allows an authenticated attacker with a valid API token to upload files of any type and extension without restriction, which can then be executed, leading to Remote Code Execution.

This issue was fixed in 3.18.4.

### CVE-2026-26980
**ghost ghost**
- **Signals:** EXP
- **Asset:** ghost ghost
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T15:16:24.310
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2026-05-07

> Ghost is a Node.js content management system. Versions 3.24.0 through 6.19.0 allow unauthenticated attackers to perform arbitrary reads from the database. This issue has been fixed in version 6.19.1.

### CVE-2026-32746
**gnu inetutils Out-of-Bounds Write**
- **Signals:** EXP
- **Asset:** gnu inetutils
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T18:15:51.730
- **CWE:** CWE-120
- **Risk score:** 78
- **EXP:** ref published 2026-05-07

> telnetd in GNU inetutils through 2.7 allows an out-of-bounds write in the LINEMODE SLC (Set Local Characters) suboption handler because add_slc does not check whether the buffer is full.

### CVE-2026-33109
**microsoft azure_managed_instance_for_apache_cassandra**
- **Signals:** CVSS
- **Asset:** microsoft azure_managed_instance_for_apache_cassandra
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:48:54.647
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-07)

> Improper access control in Azure Managed Instance for Apache Cassandra allows an authorized attacker to execute code over a network.

### CVE-2026-33823
**microsoft teams privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft teams
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:58:39.137
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-07)

> Improper authorization in Microsoft Teams allows an authorized attacker to disclose information over a network.

### CVE-2026-33844
**microsoft azure_managed_instance_for_apache_cassandra**
- **Signals:** CVSS
- **Asset:** microsoft azure_managed_instance_for_apache_cassandra
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-06-01T19:16:25.740
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-07)

> Improper access control in Azure Managed Instance for Apache Cassandra allows an authorized attacker to execute code over a network.

### CVE-2026-34156
**nocobase nocobase**
- **Signals:** EXP
- **Asset:** nocobase nocobase
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T20:57:55.957
- **CWE:** CWE-913
- **Risk score:** 78
- **EXP:** ref published 2026-05-07

> NocoBase is an AI-powered no-code/low-code platform for building business applications and enterprise solutions. Prior to version 2.0.28, NocoBase's Workflow Script Node executes user-supplied JavaScript inside a Node.js vm sandbox with a custom require allowlist (controlled by W…

### CVE-2026-35428
**microsoft azure_cloud_shell Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft azure_cloud_shell
- **Attack:** Command Injection
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T20:02:29.777
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-07)

> Improper neutralization of special elements used in a command ('command injection') in Azure Cloud Shell allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-37709
**snipeitapp snipe-it**
- **Signals:** CVSS
- **Asset:** snipeitapp snipe-it
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T20:29:20.630
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-07)

> Insecure Permissions vulnerability in grokability snipe-it v.8.4.0 and before and fixed after 2026-03-10 commit 676a9958 allows a remote attacker to execute arbitrary code via the app/Http/Controllers/Api/UploadedFilesController.php component

### CVE-2026-41902
**FreeScout is a free help desk and shared inbox built with PHP's Laravel framework.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-08T22:16:30.810
- **CWE:** CWE-613
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-07)

> FreeScout is a free help desk and shared inbox built with PHP's Laravel framework. Prior to version 1.8.217, the /user-setup/{hash} endpoint accepts a 60-character random invite_hash to set a new user's password. The endpoint performs no expiration check — the hash remains valid …

### CVE-2026-42826
**microsoft azure_devops**
- **Signals:** CVSS
- **Asset:** microsoft azure_devops
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:50:24.040
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-07)

> Exposure of sensitive information to an unauthorized actor in Azure DevOps allows an unauthorized attacker to disclose information over a network.

### CVE-2026-42880
**argoproj argo_cd privilege escalation**
- **Signals:** CVSS
- **Asset:** argoproj argo_cd
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-11T17:46:18.257
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-07)

> Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes. From versions 3.2.0 to before 3.2.11 and 3.3.0 to before 3.3.9, there is a missing authorization and data-masking gap in Argo CD's ServerSideDiff endpoint that allows an attacker with read-only access to ex…

### CVE-2026-7415
**yarbo lawn_mower_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** yarbo lawn_mower_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-14T17:50:35.057
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-07)

> The MQTT broker embedded in Yarbo firmware v2.3.9 is configured to allow anonymous connections with no topic-level read or write ACLs. Any host on the same network can subscribe to sensitive telemetry topics or publish control messages directly to the robot without authentication…

### CVE-2026-7891
**The VerySecureApp made by DIVD using Mendix Studio Pro 11.8.0 Beta allows unintended data exposure due to authorization misconfiguration.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-08T15:37:58.510
- **CWE:** CWE-277
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-07)

> The VerySecureApp made by DIVD using Mendix Studio Pro 11.8.0 Beta allows unintended data exposure due to authorization misconfiguration. The VerySecureApp allows anonymous users of the MyFirstModule with the anonymous user role to gain access to all stored records, even though n…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-07*
