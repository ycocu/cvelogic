# Daily Threat Intelligence — December 28, 2025

**Digest window (UTC):** 2025-12-28
**Generated:** 2026-06-02T07:34:04Z

## Threat brief

Microsoft Internet Information Server — exploitation likelihood rose sharply (EPSS 34% → 89% · rising (+55%)).

## Executive summary

- Microsoft Internet Information Server — exploitation likelihood rose sharply (EPSS 34% → 89% · rising (+55%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2000-0886
**microsoft internet_information_server**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 33.9% (2025-12-27) → 89.2% (2025-12-28), Δ +55.3%**

> IIS 5.0 allows remote attackers to execute arbitrary commands via a malformed request for an executable file whose name is appended with operating system commands, aka the "Web Server File Request Parsing" vulnerability.

### CVE-2000-0408
**microsoft internet_information_server DoS**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 22.4% (2025-12-27) → 74.0% (2025-12-28), Δ +51.6%**

> IIS 4.05 and 5.0 allow remote attackers to cause a denial of service via a long, complex URL that appears to contain a large number of file extensions, aka the "Malformed Extension Data in URL" vulnerability.

### CVE-2016-4553
**canonical linux**
- **Signals:** EPSS
- **Asset:** canonical ubuntu_linux
- **CVSS max:** 8.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-345
- **Risk score:** 84
- **EPSS 39.5% (2025-12-27) → 82.8% (2025-12-28), Δ +43.3%**

> client_side.cc in Squid before 3.5.18 and 4.x before 4.0.10 does not properly ignore the Host header when absolute-URI is provided, which allows remote attackers to conduct cache-poisoning attacks via an HTTP request.

### CVE-2000-0304
**microsoft internet_information_server DoS**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 18.0% (2025-12-27) → 51.7% (2025-12-28), Δ +33.6%**

> Microsoft IIS 4.0 and 5.0 with the IISADMPWD virtual directory installed allows a remote attacker to cause a denial of service via a malformed request to the inetinfo.exe program, aka the "Undelimited .HTR Request" vulnerability.

### CVE-2000-0457
**microsoft internet_information_server**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 38.6% (2025-12-27) → 84.4% (2025-12-28), Δ +45.8%**

> ISM.DLL in IIS 4.0 and 5.0 allows remote attackers to read file contents by requesting the file and appending a large number of encoded spaces (%20) and terminated with a .htr extension, aka the ".HTR File Fragment Reading" or "File Fragment Reading via .HTR" vulnerability.

### CVE-2000-0631
**microsoft internet_information_server DoS**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 15.1% (2025-12-27) → 48.4% (2025-12-28), Δ +33.3%**

> An administrative script from IIS 3.0, later included in IIS 4.0 and 5.0, allows remote attackers to cause a denial of service by accessing the script without a particular argument, aka the "Absent Directory Browser Argument" vulnerability.

### CVE-2001-0096
**microsoft internet_information_server DoS**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 11.1% (2025-12-27) → 55.9% (2025-12-28), Δ +44.8%**

> FrontPage Server Extensions (FPSE) in IIS 4.0 and 5.0 allows remote attackers to cause a denial of service via a malformed form, aka the "Malformed Web Form Submission" vulnerability.

### CVE-2001-0506
**microsoft internet_information_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 32.0% (2025-12-27) → 77.6% (2025-12-28), Δ +45.6%**

> Buffer overflow in ssinc.dll in IIS 5.0 and 4.0 allows local users to gain system privileges via a Server-Side Includes (SSI) directive for a long filename, which triggers the overflow when the directory name is added, aka the "SSI privilege elevation" vulnerability.

### CVE-2001-0663
**microsoft windows_2000 DoS**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 23.1% (2025-12-27) → 55.0% (2025-12-28), Δ +32.0%**

> Terminal Server in Windows NT and Windows 2000 allows remote attackers to cause a denial of service via a sequence of invalid Remote Desktop Protocol (RDP) packets.

### CVE-2002-0224
**microsoft internet_information_services DoS**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_services
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 19.5% (2025-12-27) → 58.3% (2025-12-28), Δ +38.8%**

> The MSDTC (Microsoft Distributed Transaction Service Coordinator) for Microsoft Windows 2000, Microsoft IIS 5.0 and SQL Server 6.5 through SQL 2000 0.0 allows remote attackers to cause a denial of service (crash or hang) via malformed (random) input.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-28*
