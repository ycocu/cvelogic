# Daily Threat Intelligence — June 10, 2026

**Digest window (UTC):** 2026-06-10
**Generated:** 2026-06-12T11:04:15Z

## Threat brief

Efs Software Easy Chat Server — exploitation likelihood rose sharply (EPSS 45% → 78% · rising (+33%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Efs Software Easy Chat Server — exploitation likelihood rose sharply (EPSS 45% → 78% · rising (+33%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 8 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2004-2466
**efs_software easy_chat_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** efs_software easy_chat_server
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 78
- **EPSS 44.5% (2025-11-13) → 77.8% (2026-06-10), Δ +33.3%**

> chat.ghp in Easy Chat Server 1.2 allows remote attackers to cause a denial of service (server crash) via a long username parameter, possibly due to a buffer overflow.  NOTE: it was later reported that 2.2 is also affected.

### CVE-2022-1711
**diagrams drawio SSRF**
- **Signals:** EPSS
- **Asset:** diagrams drawio
- **Attack:** SSRF
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:41:18.100
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 82
- **EPSS 53.9% (2026-06-09) → 84.4% (2026-06-10), Δ +30.4%**

> Server-Side Request Forgery (SSRF) in GitHub repository jgraph/drawio prior to 18.0.5.

### CVE-2026-46695
**Boxlite is a sandbox service that allows users to create lightweight virtual machines (Boxes) and launch OCI containers within them to ru...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-06-11T15:21:07.370
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-10)

> Boxlite is a sandbox service that allows users to create lightweight virtual machines (Boxes) and launch OCI containers within them to run untrusted code. Prior to version 0.9.0, Boxlite does not restrict the kernel capabilities available inside the container, malicious code can …

### CVE-2022-34190
**jenkins maven_metadata XSS**
- **Signals:** EPSS
- **Asset:** jenkins maven_metadata
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:09:01.933
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 17.5% (2026-05-03) → 29.6% (2026-06-10), Δ +12.0%**

> Jenkins Maven Metadata Plugin for Jenkins CI server Plugin 2.1 and earlier does not escape the name and description of List maven artifact versions parameters on views displaying parameters, resulting in a stored cross-site scripting (XSS) vulnerability exploitable by attackers w…

### CVE-2022-34193
**jenkins package_version XSS**
- **Signals:** EPSS
- **Asset:** jenkins package_version
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:09:02.263
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 17.5% (2026-05-03) → 29.6% (2026-06-10), Δ +12.0%**

> Jenkins Package Version Plugin 1.0.1 and earlier does not escape the name of Package version parameters on views displaying parameters, resulting in a stored cross-site scripting (XSS) vulnerability exploitable by attackers with Item/Configure permission.

### CVE-2022-34194
**jenkins readonly_parameter XSS**
- **Signals:** EPSS
- **Asset:** jenkins readonly_parameter
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:09:02.380
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 17.5% (2026-05-03) → 29.6% (2026-06-10), Δ +12.0%**

> Jenkins Readonly Parameter Plugin 1.0.0 and earlier does not escape the name and description of Readonly String and Readonly Text parameters on views displaying parameters, resulting in a stored cross-site scripting (XSS) vulnerability exploitable by attackers with Item/Configure…

### CVE-2022-34197
**jenkins sauce_ondemand XSS**
- **Signals:** EPSS
- **Asset:** jenkins sauce_ondemand
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:09:02.687
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 9.5% (2026-05-03) → 29.6% (2026-06-10), Δ +20.1%**

> Jenkins Sauce OnDemand Plugin 1.204 and earlier does not escape the name and description of Sauce Labs Browsers parameters on views displaying parameters, resulting in a stored cross-site scripting (XSS) vulnerability exploitable by attackers with Item/Configure permission.

### CVE-2026-20253
**In Splunk Enterprise versions below 10.2.4 and 10.0.7, and Splunk Cloud Platform versions below 10.4.2604.3 and 10.2.2510.14, an unauthen...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-10T18:36:19.463
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-10)

> In Splunk Enterprise versions below 10.2.4 and 10.0.7, and Splunk Cloud Platform versions below 10.4.2604.3 and 10.2.2510.14, an unauthenticated user could create or truncate arbitrary files through a PostgreSQL sidecar service endpoint.<br><br>The vulnerability exists because th…

### CVE-2026-34910
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD modified:** 2026-05-22T02:16:34.527
- **CWE:** CWE-20
- **Risk score:** 86
- **EPSS 0.1% (2026-05-22) → 18.1% (2026-06-10), Δ +18.1%**

> A malicious actor with access to the network could exploit an Improper Input Validation vulnerability found in UniFi OS devices to execute a Command Injection.

### CVE-2026-46614
**Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kuberne...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T19:37:41.437
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-10)

> Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kubernetes. Prior to version 1.23.0, the Fission router registers an internal-style route — /fission-function/<name> and /fission-function/<ns>/<name>…

### CVE-2026-46703
**Boxlite is a sandbox service that allows users to create lightweight virtual machines (Boxes) and launch OCI containers within them to ru...**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-06-11T15:21:07.370
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-10)

> Boxlite is a sandbox service that allows users to create lightweight virtual machines (Boxes) and launch OCI containers within them to run untrusted code. Prior to version 0.9.0, Boxlite allows users to specify the OCI image used by containers in the sandbox. However, when proces…

### CVE-2026-50545
**Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kuberne...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T19:37:41.437
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-10)

> Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kubernetes. Prior to version 1.24.0, the Environment.spec.runtime.podSpec / spec.builder.podSpec passthrough lacked validation, and MergePodSpec propa…

### CVE-2026-50563
**Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kuberne...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T19:37:41.437
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-10)

> Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kubernetes. Prior to version 1.24.0, Fission's Container Executor path lets a tenant supply Function.spec.podspec directly; the executor merges it int…

### CVE-2026-50564
**Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kuberne...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T19:37:41.437
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-10)

> Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kubernetes. Prior to version 1.24.0, Fission's Environment CRD exposes spec.runtime.podSpec and spec.builder.podSpec, which are merged into the Kubern…

### CVE-2026-50566
**Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kuberne...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T19:37:41.437
- **CWE:** CWE-250
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-10)

> Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kubernetes. Prior to version 1.24.0, a tenant with environments.fission.io create/update RBAC can run privileged / allowPrivilegeEscalation / dangerou…

### CVE-2026-50638
**Metrics::Any::Adapter::DogStatsd versions before 0.04 for Perl does not protect against metric injections.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-11T20:16:25.347
- **CWE:** CWE-93
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-10)

> Metrics::Any::Adapter::DogStatsd versions before 0.04 for Perl does not protect against metric injections.

The statsd protocol (and extensions such as dogstatsd) allow mutiple metrics,separated by newlines, to be sent per packet.

Metrics::Any::Adapter::DogStatsd which extends M…

### CVE-2026-5073
**SQL Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-06-02T20:56:20.057
- **CWE:** CWE-89
- **Risk score:** 82
- **EPSS 0.1% (2026-06-03) → 24.5% (2026-06-10), Δ +24.4%**

> The ARMember Premium plugin for WordPress is vulnerable to SQL Injection via the 'order' parameter of the 'arm_directory_paging_action' AJAX action in all versions up to, and including, 7.3.1. This is due to insufficient escaping on the user-supplied 'order' and 'orderby' paramet…

### CVE-2026-53476
**A flaw was found in assisted-migration-agent.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.6
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-10T19:24:04.320
- **CWE:** CWE-59
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-10)

> A flaw was found in assisted-migration-agent. An unauthenticated attacker, located on the same local area network (LAN), can exploit a path traversal vulnerability. By crafting a specially designed gzipped tarball, the attacker can bypass security checks and write arbitrary files…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-10*
