# Daily Threat Intelligence — June 10, 2025

**Digest window (UTC):** 2025-06-10
**Generated:** 2026-06-02T07:32:51Z

## Threat brief

Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation. · Zohocorp Manageengine Applications Manager — exploitation likelihood rose sharply (EPSS 5.2% → 27% · rising (+22%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation.
- Zohocorp Manageengine Applications Manager — exploitation likelihood rose sharply (EPSS 5.2% → 27% · rising (+22%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-24016
**Wazuh Server Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** wazuh wazuh
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:59:44.790
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-06-10

> Wazuh is a free and open source platform used for threat prevention, detection, and response. Starting in version 4.4.0 and prior to version 4.9.1, an unsafe deserialization vulnerability allows for remote code execution on Wazuh servers. DistributedAPI parameters are a serialize…

### CVE-2022-23050
**zohocorp manageengine_applications_manager**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_applications_manager
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:47:53.210
- **CWE:** CWE-427
- **Risk score:** 82
- **EPSS 5.2% (2025-06-09) → 27.4% (2025-06-10), Δ +22.2%**

> ManageEngine AppManager15 (Build No:15510) allows an authenticated admin user to upload a DLL file to perform a DLL hijack attack inside the 'working' folder through the 'Upload Files / Binaries' functionality.

### CVE-2025-30220
**geotools geonetwork XXE**
- **Signals:** CVSS
- **Asset:** geotools geotools
- **Attack:** XXE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-26T16:10:11.830
- **CWE:** CWE-611
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-10)

> GeoServer is an open source server that allows users to share and edit geospatial data. GeoTools Schema class use of Eclipse XSD library to represent schema data structure is vulnerable to XML External Entity (XXE) exploit. This impacts whoever exposes XML processing with gt-xsd-…

### CVE-2024-34711
**osgeo geoserver**
- **Signals:** CVSS
- **Asset:** osgeo geoserver
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-26T16:24:18.393
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-10)

> GeoServer is an open source server that allows users to share and edit geospatial data. An improper URI validation vulnerability exists that enables an unauthorized attacker to perform XML External Entities (XEE) attack, then send GET request to any HTTP server. By default, GeoSe…

### CVE-2024-57190
**erxes erxes**
- **Signals:** CVSS
- **Asset:** erxes erxes
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-20T13:07:32.170
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-10)

> Erxes <1.6.1 is vulnerable to Incorrect Access Control. An attacker can bypass authentication by providing a "User" HTTP header that contains any user, allowing them to talk to any GraphQL endpoint.

### CVE-2025-2474
**blackberry qnx_software_development_platform Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** blackberry qnx_software_development_platform
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-01T18:05:04.720
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-10)

> Out-of-bounds write in the PCX image codec in QNX SDP versions 8.0, 7.1 and 7.0 could allow an unauthenticated attacker to cause a denial-of-service condition or execute code in the context of the process using the image codec.

### CVE-2025-33053
**Microsoft Windows External Control of File Name or Path Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:12:46.430
- **CWE:** CWE-73
- **Risk score:** 88
- **KEV:** added 2025-06-10

> External control of file name or path in Internet Shortcut Files allows an unauthorized attacker to execute code over a network.

### CVE-2025-36852
**A critical security vulnerability exists in remote cache extensions for common build systems utilizing bucket-based remote cache (such as...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-829
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-10)

> A critical security vulnerability exists in remote cache extensions for common build systems utilizing bucket-based remote cache (such as those using Amazon S3, Google Cloud Storage, or similar object storage) that allows any contributor with pull request privileges to inject com…

### CVE-2025-40585
**A vulnerability has been identified in Energy Services (All versions with G5DFR).**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-276
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-06-10)

> A vulnerability has been identified in Energy Services (All versions with G5DFR). Affected solutions using G5DFR contain default credentials. This could allow an attacker to gain control of G5DFR component and tamper with outputs from the device.

### CVE-2025-40657
**acc dm_corporative_cms SQL Injection**
- **Signals:** CVSS
- **Asset:** acc dm_corporative_cms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-22T14:00:13.857
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-10)

> A SQL injection vulnerability has been found in DM Corporative CMS. This vulnerability allows an attacker to retrieve, create, update and delete databases through the codform parameter in /modules/forms/collectform.asp.

### CVE-2025-43698
**Improper Preservation of Permissions vulnerability in Salesforce OmniStudio (FlexCards) allows bypass of field level security controls fo...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-281
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-10)

> Improper Preservation of Permissions vulnerability in Salesforce OmniStudio (FlexCards) allows bypass of field level security controls for Salesforce objects. 
This impacts OmniStudio: before Spring 2025

### CVE-2025-49455
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in ClickandPledge WordPress-WPJobBoard...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:42.853
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-10)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in ClickandPledge WordPress-WPJobBoard click-pledge-wpjobboard allows Blind SQL Injection.This issue affects WordPress-WPJobBoard: from n/a through <= 25.07010000-WP6.8.1-JB5.11.5.

### CVE-2025-49507
**Deserialization of Untrusted Data vulnerability in LoftOcean CozyStay cozystay allows Object Injection.This issue affects CozyStay: from...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:42.973
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-10)

> Deserialization of Untrusted Data vulnerability in LoftOcean CozyStay cozystay allows Object Injection.This issue affects CozyStay: from n/a through < 1.7.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-10*
