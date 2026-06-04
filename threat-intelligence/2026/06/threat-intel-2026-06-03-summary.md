# Daily Threat Intelligence — June 03, 2026

**Digest window (UTC):** 2026-06-03
**Generated:** 2026-06-04T15:01:49Z

## Threat brief

Mirasvit Full Page Cache Warmer added to CISA KEV — confirmed in-the-wild exploitation. · Linux Kernel — exploitation likelihood rose sharply (EPSS 5.2% → 26% · rising (+21%)). · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- Mirasvit Full Page Cache Warmer added to CISA KEV — confirmed in-the-wild exploitation.
- Linux Kernel — exploitation likelihood rose sharply (EPSS 5.2% → 26% · rising (+21%)).
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2026-45247
**Mirasvit Full Page Cache Warmer Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** mirasvit full_page_cache_warmer
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-03T19:55:00.583
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-06-03

> Mirasvit Full Page Cache Warmer for Magento 2 before version 1.11.12 contains a PHP object injection vulnerability that allows unauthenticated attackers to achieve remote code execution by supplying a crafted serialized PHP object in the CacheWarmer cookie. Attackers can exploit …

### CVE-2022-0492
**Linux Kernel Improper Authentication Vulnerability**
- **Signals:** EPSS
- **Asset:** netapp h300s_firmware
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-03T12:53:31.967
- **CWE:** CWE-287
- **CWE:** CWE-862
- **Risk score:** 83
- **EPSS 5.2% (2026-05-16) → 26.3% (2026-06-03), Δ +21.1%**

> A vulnerability was found in the Linux kernel’s cgroup_release_agent_write in the kernel/cgroup/cgroup-v1.c function. This flaw, under certain circumstances, allows the use of the cgroups v1 release_agent feature to escalate privileges and bypass the namespace isolation unexpecte…

### CVE-2026-36576
**An OS command injection vulnerability in the app.py component of openlabs docker-wkhtmltopdf-aas up to commit 9f50579 allows attackers to...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-03T19:16:26.260
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-03)

> An OS command injection vulnerability in the app.py component of openlabs docker-wkhtmltopdf-aas up to commit 9f50579 allows attackers to execute arbitrary commands via a crafted POST request.

### CVE-1999-0107
**apache http_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 35.6% (2026-05-27) → 51.6% (2026-06-03), Δ +16.0%**

> Buffer overflow in Apache 1.2.5 and earlier allows a remote attacker to cause a denial of service with a large number of GET requests containing a large number of / characters.

### CVE-2008-3655
**ruby-lang ruby**
- **Signals:** EPSS
- **Asset:** ruby-lang ruby
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-264
- **Risk score:** 82
- **EPSS 35.3% (2026-06-01) → 47.5% (2026-06-03), Δ +12.3%**

> Ruby 1.8.5 and earlier, 1.8.6 through 1.8.6-p286, 1.8.7 through 1.8.7-p71, and 1.9 through r18423 does not properly restrict access to critical variables and methods at various safe levels, which allows context-dependent attackers to bypass intended access restrictions via (1) un…

### CVE-2015-8257
**axis network_camera_firmware**
- **Signals:** EPSS
- **Asset:** axis network_camera_firmware
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-77
- **Risk score:** 82
- **EPSS 17.4% (2026-02-25) → 28.1% (2026-06-03), Δ +10.8%**

> The devtools.sh script in AXIS network cameras allows remote authenticated users to execute arbitrary commands via shell metacharacters in the app parameter to (1) app_license.shtml, (2) app_license_custom.shtml, (3) app_index.shtml, or (4) app_params.shtml.

### CVE-2015-8258
**axis axis_communications_firmware**
- **Signals:** EPSS
- **Asset:** axis axis_communications_firmware
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-74
- **Risk score:** 81
- **EPSS 17.4% (2026-02-03) → 29.2% (2026-06-03), Δ +11.8%**

> AXIS Communications products with firmware through 5.80.x allow remote attackers to modify arbitrary files as root via vectors involving Open Script Editor, aka a "resource injection vulnerability."

### CVE-2019-14223
**alfresco alfresco open redirect**
- **Signals:** EPSS
- **Asset:** alfresco alfresco
- **Attack:** open redirect
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:26:13.983
- **CWE:** CWE-601
- **Risk score:** 80
- **EPSS 37.3% (2026-03-24) → 50.3% (2026-06-03), Δ +13.1%**

> An issue was discovered in Alfresco Community Edition versions below 5.2.6, 6.0.N and 6.1.N. The Alfresco Share application is vulnerable to an Open Redirect attack via a crafted POST request. By manipulating the POST parameters, an attacker can redirect a victim to a malicious w…

### CVE-2019-14251
**temenos t24**
- **Signals:** EPSS
- **Asset:** temenos t24
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:26:17.927
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 56.6% (2026-01-18) → 72.5% (2026-06-03), Δ +15.8%**

> An issue was discovered in T24 in TEMENOS Channels R15.01. The login page presents JavaScript functions to access a document on the server once successfully authenticated. However, an attacker can leverage downloadDocServer() to traverse the file system and access files or direct…

### CVE-2019-14312
**aptana jaxer**
- **Signals:** EPSS
- **Asset:** aptana jaxer
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:26:28.333
- **CWE:** CWE-22
- **Risk score:** 79
- **EPSS 55.6% (2026-01-18) → 67.1% (2026-06-03), Δ +11.4%**

> Aptana Jaxer 1.0.3.4547 is vulnerable to a local file inclusion vulnerability in the wikilite source code viewer. This vulnerability allows a remote attacker to read internal files on the server via a tools/sourceViewer/index.html?filename=../ URI.

### CVE-2022-40743
**apache traffic_server cross-site scripting**
- **Signals:** EPSS
- **Asset:** apache traffic_server
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-04-17T15:15:47.180
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 8.2% (2026-03-01) → 19.3% (2026-06-03), Δ +11.1%**

> Improper Input Validation vulnerability for the xdebug plugin in Apache Software Foundation Apache Traffic Server can lead to cross site scripting and cache poisoning attacks.This issue affects Apache Traffic Server: 9.0.0 to 9.1.3. Users should upgrade to 9.1.4 or later versions…

### CVE-2025-3928
**Commvault Web Server Unspecified Vulnerability**
- **Signals:** EPSS
- **Asset:** commvault commvault
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T21:59:08.943
- **Risk score:** 84
- **EPSS 16.2% (2026-04-08) → 28.6% (2026-06-03), Δ +12.5%**

> Commvault Web Server has an unspecified vulnerability that can be exploited by a remote, authenticated attacker. According to the Commvault advisory: "Webservers can be compromised through bad actors creating and executing webshells." Fixed in version 11.36.46, 11.32.89, 11.28.14…

### CVE-2026-35075
**An unauthenticated remote attacker can recover a default, hard coded password from a firmware image and thus gain full access to all affe...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-03T13:16:19.407
- **CWE:** CWE-1393
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-03)

> An unauthenticated remote attacker can recover a default, hard coded password from a firmware image and thus gain full access to all affected devices.

### CVE-2026-36748
**RockRMS v16.13 and before v.17.7.0 is vulnerable to Cross Site Scripting (XSS) via Social Media links in user profile.**
- **Signals:** CVSS
- **Attack:** cross-site scripting
- **CVSS max:** 9.0
- **NVD status:** Received
- **NVD modified:** 2026-06-03T19:16:37.190
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-03)

> RockRMS v16.13 and before v.17.7.0 is vulnerable to Cross Site Scripting (XSS) via Social Media links in user profile.

### CVE-2026-4035
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD modified:** 2026-06-03T14:16:45.847
- **CWE:** CWE-201
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-03)

> A vulnerability in mlflow/mlflow versions prior to 3.11.0 allows for the resolution of environment variables in AI Gateway secrets, which can be exploited to exfiltrate sensitive server-side environment credentials to an attacker-controlled endpoint. This issue arises because the…

### CVE-2026-47065
**ZDRES-232: resolveProxyClass Not Overridden - acceptMatchers Filter Bypass via java.lang.reflect.Proxy Assessment: Fully addressed.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-03T11:16:19.800
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-03)

> ZDRES-232: resolveProxyClass Not Overridden - acceptMatchers Filter Bypass via java.lang.reflect.Proxy


Assessment: Fully addressed.


When the serialised stream contains a TC_PROXYCLASSDESC (the marker 
for a java.lang.reflect.Proxy ), JDK’s ObjectInputStream.readProxyDesc()
 i…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-03*
