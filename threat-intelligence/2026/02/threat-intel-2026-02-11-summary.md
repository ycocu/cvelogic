# Daily Threat Intelligence — February 11, 2026

**Digest window (UTC):** 2026-02-11
**Generated:** 2026-06-02T07:34:24Z

## Threat brief

Motioneye Project Motioneye: public exploit or PoC linked (Code Execution) · Cozmoslabs User Profile Picture — exploitation likelihood rose sharply (EPSS 29% → 42% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Motioneye Project Motioneye: public exploit or PoC linked (Code Execution)
- Cozmoslabs User Profile Picture — exploitation likelihood rose sharply (EPSS 29% → 42% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2023-4911
**GNU C Library Buffer Overflow Vulnerability**
- **Signals:** EXP
- **Asset:** netapp bootstrap_os
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T16:24:45.860
- **CWE:** CWE-122
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2026-02-11

> A buffer overflow was discovered in the GNU C Library's dynamic loader ld.so while processing the GLIBC_TUNABLES environment variable. This issue could allow a local attacker to use maliciously crafted GLIBC_TUNABLES environment variables when launching binaries with SUID permiss…

### CVE-2025-60787
**motioneye_project motioneye Code Execution**
- **Signals:** EXP
- **Asset:** motioneye_project motioneye
- **Attack:** Code Execution
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T16:22:30.703
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2026-02-11

> MotionEye v0.43.1b4 and before is vulnerable to OS Command Injection in configuration parameters such as image_file_name. Unsanitized user input is written to Motion configuration files, allowing remote authenticated attackers with admin access to achieve code execution when Moti…

### CVE-2021-24170
**cozmoslabs user_profile_picture**
- **Signals:** EPSS
- **Asset:** cozmoslabs user_profile_picture
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:52:30.893
- **CWE:** CWE-200
- **CWE:** CWE-200
- **Risk score:** 82
- **EPSS 28.7% (2025-11-21) → 42.1% (2026-02-11), Δ +13.5%**

> The REST API endpoint get_users in the User Profile Picture WordPress plugin before 2.5.0 returned more information than was required for its functionality to users with the upload_files capability. This included password hashes, hashed user activation keys, usernames, emails, an…

### CVE-2000-0257
**novell netware Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell netware
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 79
- **EPSS 4.9% (2025-03-30) → 15.0% (2026-02-11), Δ +10.1%**

> Buffer overflow in the NetWare remote web administration utility allows remote attackers to cause a denial of service or execute commands via a long URL.

### CVE-2014-9119
**db_backup_project db_backup Directory Traversal**
- **Signals:** EPSS
- **Asset:** db_backup_project db_backup
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 38.1% (2025-11-26) → 51.1% (2026-02-11), Δ +13.1%**

> Directory traversal vulnerability in download.php in the DB Backup plugin 4.5 and earlier for Wordpress allows remote attackers to read arbitrary files via a .. (dot dot) in the file parameter.

### CVE-2020-23697
**monstra monstra_cms cross-site scripting**
- **Signals:** EPSS
- **Asset:** monstra monstra_cms
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:14:00.633
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 13.9% (2026-02-02) → 26.4% (2026-02-11), Δ +12.5%**

> Cross Site Scripting vulnerabilty in Monstra CMS 3.0.4 via the page feature in admin/index.php.

### CVE-2020-37186
**Chevereto 3.13.4 Core contains a remote code execution vulnerability that allows attackers to inject malicious code during database confi...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-11)

> Chevereto 3.13.4 Core contains a remote code execution vulnerability that allows attackers to inject malicious code during database configuration installation. Attackers can manipulate the database table prefix parameter to write a PHP shell file and execute arbitrary system comm…

### CVE-2025-24054
**Microsoft Windows NTLM Hash Disclosure Spoofing Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T21:25:23.527
- **CWE:** CWE-73
- **Risk score:** 78
- **EXP:** ref published 2026-02-11

> External control of file name or path in Windows NTLM allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-67135
**Weak Security in the PF-50 1.2 keyfob of PGST PG107 Alarm System 1.25.05.hf allows attackers to compromise access control via a code repl...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-294
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-11)

> Weak Security in the PF-50 1.2 keyfob of PGST PG107 Alarm System 1.25.05.hf allows attackers to compromise access control via a code replay attack.

### CVE-2025-69872
**DiskCache (python-diskcache) through 5.6.3 uses Python pickle for serialization by default.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-11)

> DiskCache (python-diskcache) through 5.6.3 uses Python pickle for serialization by default. An attacker with write access to the cache directory can achieve arbitrary code execution when a victim application reads from the cache.

### CVE-2025-69874
**unjs nanotar Path Traversal**
- **Signals:** CVSS
- **Asset:** unjs nanotar
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T11:32:27.587
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-11)

> nanotar through 0.2.0 has a path traversal vulnerability in parseTar() and parseTarGzip() that allows remote attackers to write arbitrary files outside the intended extraction directory via a crafted tar archive containing path traversal sequence.

### CVE-2025-70085
**opensatkit opensatkit**
- **Signals:** CVSS
- **Asset:** opensatkit opensatkit
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T15:02:22.943
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-11)

> An issue was discovered in OpenSatKit 2.2.1. The EventErrStr buffer has a fixed size of 256 bytes. The code uses sprintf to format two filenames (Source1Filename and the string returned by FileUtil_FileStateStr) into this buffer without any length checking and without using bound…

### CVE-2026-20677
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple ipados
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:21:21.663
- **CWE:** CWE-362
- **CWE:** CWE-367
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-02-11)

> A race condition was addressed with improved handling of symbolic links. This issue is fixed in iOS 18.7.5 and iPadOS 18.7.5, iOS 26.3 and iPadOS 26.3, macOS Sonoma 14.8.4, macOS Tahoe 26.3, visionOS 26.3. A shortcut may be able to bypass sandbox restrictions.

### CVE-2026-24789
**An unprotected API endpoint allows an attacker to remotely change the device password without providing authentication.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-11)

> An unprotected API endpoint allows an attacker to remotely change the device password without providing authentication.

### CVE-2026-25084
**Authentication for ZLAN5143D can be bypassed by directly accessing internal URLs.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-11)

> Authentication for ZLAN5143D can be bypassed by directly accessing internal URLs.

### CVE-2026-26021
**set-in_project set-in**
- **Signals:** CVSS
- **Asset:** set-in_project set-in
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T21:43:27.900
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-11)

> set-in provides the set value of nested associative structure given array of keys. A prototype pollution vulnerability exists in the the npm package set-in (>=2.0.1, < 2.0.5). Despite a previous fix that attempted to mitigate prototype pollution by checking whether user input con…

### CVE-2026-26215
**manga-image-translator version beta-0.3 and prior in shared API mode contains an unsafe deserialization vulnerability that can lead to un...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-11)

> manga-image-translator version beta-0.3 and prior in shared API mode contains an unsafe deserialization vulnerability that can lead to unauthenticated remote code execution. The FastAPI endpoints /simple_execute/{method} and /execute/{method} deserialize attacker-controlled reque…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-11*
