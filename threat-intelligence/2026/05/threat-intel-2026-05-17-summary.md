# Daily Threat Intelligence — May 17, 2026

**Digest window (UTC):** 2026-05-17
**Generated:** 2026-06-02T07:04:02Z

## Threat brief

Xwiki — exploitation likelihood rose sharply (EPSS 25% → 54% · rising (+29%)). · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- Xwiki — exploitation likelihood rose sharply (EPSS 25% → 54% · rising (+29%)).
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2023-29525
**xwiki xwiki Privilege Escalation**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **Attack:** Privilege Escalation
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:57:13.917
- **CWE:** CWE-74
- **Risk score:** 86
- **EPSS 25.2% (2026-05-02) → 54.3% (2026-05-17), Δ +29.0%**

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Affected versions of xwiki are subject to code injection in the `since` parameter of the `/xwiki/bin/view/XWiki/Notifications/Code/LegacyNotificationAdministration` endpoint. …

### CVE-2022-36971
**ivanti avalanche**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:11.087
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 84
- **EPSS 62.4% (2026-03-31) → 86.1% (2026-05-17), Δ +23.7%**

> This vulnerability allows remote attackers to execute arbitrary code on affected installations of Ivanti Avalanche 6.3.2.3490. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The specific flaw exists within…

### CVE-2026-8507
**Crypt::OpenSSL::PKCS12 versions through 1.94 for Perl have out-of-bounds (OOB) write flaws.**
- **Signals:** CVSS
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T17:40:45.343
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-17)

> Crypt::OpenSSL::PKCS12 versions through 1.94 for Perl have out-of-bounds (OOB) write flaws.

When parsing a PKCS12 file, with a >= 1 GiB OCTET STRING (or BIT STRING) attribute on a SAFEBAG, via info() or info_as_hash(), a heap out-of-bounds write would be triggered with remote-co…

### CVE-2018-25320
**ACL Analytics versions 11.x through 13.0.0.579 contain an arbitrary code execution vulnerability that allows attackers to execute arbitra...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T19:42:03.353
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-17)

> ACL Analytics versions 11.x through 13.0.0.579 contain an arbitrary code execution vulnerability that allows attackers to execute arbitrary commands by leveraging the EXECUTE function. Attackers can use bitsadmin to download malicious PowerShell scripts and execute them with syst…

### CVE-2018-25332
**gitbucket gitbucket RCE**
- **Signals:** CVSS
- **Asset:** gitbucket gitbucket
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T20:44:54.467
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-17)

> GitBucket 4.23.1 contains an unauthenticated remote code execution vulnerability that allows attackers to execute arbitrary commands by exploiting weak secret token generation and insecure file upload functionality. Attackers can brute-force the Blowfish encryption key, upload a …

### CVE-2018-25335
**WordPress Plugin Peugeot Music 1.0 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malici...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T17:05:46.240
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-17)

> WordPress Plugin Peugeot Music 1.0 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious files by sending POST requests to the upload.php endpoint. Attackers can upload files with arbitrary extensions by manipulating the 'name' …

### CVE-2018-4898
**adobe acrobat**
- **Signals:** EPSS
- **Asset:** adobe acrobat
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:07:40.200
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 4.2% (2025-11-21) → 21.9% (2026-05-17), Δ +17.7%**

> An issue was discovered in Adobe Acrobat Reader 2018.009.20050 and earlier versions, 2017.011.30070 and earlier versions, 2015.006.30394 and earlier versions. The vulnerability is caused by the computation that writes data past the end of the intended buffer; the computation is p…

### CVE-2018-4904
**adobe acrobat memory safety**
- **Signals:** EPSS
- **Asset:** adobe acrobat
- **Attack:** memory safety
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:07:40.880
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 5.2% (2025-11-21) → 28.5% (2026-05-17), Δ +23.3%**

> An issue was discovered in Adobe Acrobat Reader 2018.009.20050 and earlier versions, 2017.011.30070 and earlier versions, 2015.006.30394 and earlier versions. This vulnerability is an instance of a heap overflow vulnerability. The vulnerability is triggered by crafted TIFF data w…

### CVE-2022-36972
**ivanti avalanche SQL injection**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:11.223
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 8.1% (2026-03-31) → 30.9% (2026-05-17), Δ +22.8%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Ivanti Avalanche 6.3.2.3490. The specific flaw exists within the ProfileDaoImpl class. A crafted request can trigger execution of SQL queries composed from a user-supplied string. An …

### CVE-2022-36973
**ivanti avalanche SQL injection**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** SQL injection
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:11.350
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 7.5% (2026-03-31) → 29.1% (2026-05-17), Δ +21.6%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Ivanti Avalanche 6.3.2.3490. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The specific flaw exists within …

### CVE-2022-36975
**ivanti avalanche SQL injection**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:11.597
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 8.1% (2026-03-31) → 30.9% (2026-05-17), Δ +22.8%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Ivanti Avalanche 6.3.2.3490. The specific flaw exists within the ProfileDaoImpl class. A crafted request can trigger execution of SQL queries composed from a user-supplied string. An …

### CVE-2022-36976
**ivanti avalanche SQL injection**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:11.720
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 8.1% (2026-03-31) → 30.9% (2026-05-17), Δ +22.8%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Ivanti Avalanche 6.3.2.3490. The specific flaw exists within the GroupDaoImpl class. A crafted request can trigger execution of SQL queries composed from a user-supplied string. An at…

### CVE-2022-36978
**ivanti avalanche**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:11.963
- **CWE:** CWE-502
- **Risk score:** 86
- **EPSS 62.9% (2026-03-31) → 86.2% (2026-05-17), Δ +23.3%**

> This vulnerability allows remote attackers to execute arbitrary code on affected installations of Ivanti Avalanche 6.3.2.3490. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The specific flaw exists within…

### CVE-2022-36979
**ivanti avalanche SQL injection**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:12.087
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 8.1% (2026-03-31) → 30.9% (2026-05-17), Δ +22.8%**

> This vulnerability allows remote attackers to bypass authentication on affected installations of Ivanti Avalanche 6.3.2.3490. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The specific flaw exists within …

### CVE-2026-8721
**Crypt::OpenSSL::PKCS12 versions through 1.94 for Perl truncates passwords with embedded NULLs.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T17:40:45.343
- **CWE:** CWE-170
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-17)

> Crypt::OpenSSL::PKCS12 versions through 1.94 for Perl truncates passwords with embedded NULLs.

Password parameters in PKCS12.xs are declared char *, which routes through Perl's default typemap to SvPV_nolen.  The Perl length is discarded.

The C code (or OpenSSL internally) call…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-17*
