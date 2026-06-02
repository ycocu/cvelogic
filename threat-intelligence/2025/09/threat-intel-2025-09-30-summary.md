# Daily Threat Intelligence — September 30, 2025

**Digest window (UTC):** 2025-09-30
**Generated:** 2026-06-02T07:33:30Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-7063
**widzialni pad_cms RCE**
- **Signals:** CVSS
- **Asset:** widzialni pad_cms
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T14:42:30.940
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-30)

> Due to client-controlled permission check parameter, PAD CMS's file upload functionality allows an unauthenticated remote attacker to upload files of any type and extension without restriction, which can then be executed leading to Remote Code Execution. This issue affects all 3 …

### CVE-2025-7065
**widzialni pad_cms RCE**
- **Signals:** CVSS
- **Asset:** widzialni pad_cms
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T14:42:14.750
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-30)

> Due to client-controlled permission check parameter, PAD CMS's photo upload functionality allows an unauthenticated remote attacker to upload files of any type and extension without restriction, which can then be executed leading to Remote Code Execution. This issue affects all 3…

### CVE-2025-8120
**widzialni pad_cms RCE**
- **Signals:** CVSS
- **Asset:** widzialni pad_cms
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T14:37:44.743
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-30)

> Due to client-controlled permission check parameter, PAD CMS's upload photo functionality allows an unauthenticated remote attacker to upload files of any type and extension without restriction, which can then be executed leading to Remote Code Execution.This issue affects all 3 …

### CVE-2025-10659
**The Telenium Online Web Application is vulnerable due to a PHP endpoint accessible to unauthenticated network users that improperly handl...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-30)

> The Telenium Online Web Application is vulnerable due to a PHP endpoint accessible to unauthenticated network users that improperly handles user-supplied input. This vulnerability occurs due to the insecure termination of a regular expression check within the endpoint. Because th…

### CVE-2025-10725
**A flaw was found in Red Hat Openshift AI Service.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-30)

> A flaw was found in Red Hat Openshift AI Service. A low-privileged attacker with access to an authenticated account, for example as a data scientist using a standard Jupyter notebook, can escalate their privileges to a full cluster administrator. This allows for the complete comp…

### CVE-2025-34217
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-07T14:02:24.590
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-30)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host and Application (VA/SaaS deployments) contain an undocumented 'printerlogic' user with a hardcoded SSH public key in '~/.ssh/authorized_keys' and a sudoers rule granting the printerlogic_ssh group 'NOPASSWD: ALL'. Posses…

### CVE-2025-56513
**nicehash quickminer RCE**
- **Signals:** CVSS
- **Asset:** nicehash quickminer
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-11T16:17:27.477
- **CWE:** CWE-494
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-30)

> NiceHash QuickMiner 6.12.0 perform software updates over HTTP without validating digital signatures or hash checks. An attacker capable of intercepting or redirecting traffic to the update url and can hijack the update process and deliver arbitrary executables that are automatica…

### CVE-2025-7493
**A privilege escalation flaw from host to domain administrator was found in FreeIPA.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1220
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-30)

> A privilege escalation flaw from host to domain administrator was found in FreeIPA. This vulnerability is similar to CVE-2025-4404, where it fails to validate the uniqueness of the krbCanonicalName. While the previously released version added validations for the admin@REALM crede…

### CVE-2025-8625
**The Copypress Rest API plugin for WordPress is vulnerable to Remote Code Execution via copyreap_handle_image() Function in versions 1.1 t...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-30)

> The Copypress Rest API plugin for WordPress is vulnerable to Remote Code Execution via copyreap_handle_image() Function in versions 1.1 to 1.2. The plugin falls back to a hard-coded JWT signing key when no secret is defined and does not restrict which file types can be fetched an…

### CVE-2025-9762
**The Post By Email plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the save_attachment...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-30)

> The Post By Email plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the save_attachments function in all versions up to, and including, 1.0.4b. This makes it possible for unauthenticated attackers to upload arbitrary files on the …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-30*
