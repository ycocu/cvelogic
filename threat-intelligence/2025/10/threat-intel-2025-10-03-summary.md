# Daily Threat Intelligence — October 03, 2025

**Digest window (UTC):** 2025-10-03
**Generated:** 2026-06-02T07:33:31Z

## Threat brief

WordPress plugin RCE/exploit activity: 5 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 5 CVEs flagged today.
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

### CVE-2025-49844
**lfprojects redis RCE**
- **Signals:** CVSS
- **Asset:** redis redis
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2026-03-20T14:16:14.130
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-03)

> Redis is an open source, in-memory database that persists on disk. Versions 8.2.1 and below allow an authenticated user to use a specially crafted Lua script to manipulate the garbage collector, trigger a use-after-free and potentially lead to remote code execution. The problem e…

### CVE-2025-10547
**An uninitialized variable in the HTTP CGI request arguments processing component of Vigor Routers running DrayOS may allow an attacker th...**
- **Signals:** CVSS
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-03)

> An uninitialized variable in the HTTP CGI request arguments processing component of Vigor Routers running DrayOS may allow an attacker the ability to perform RCE on the appliance through memory corruption.

### CVE-2025-6388
**The Spirit Framework plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 1.2.14.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-03)

> The Spirit Framework plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 1.2.14. This is due to the custom_actions() function not properly validating a user's identity prior to authenticating them to the site. This makes it possible f…

### CVE-2025-10726
**The WPRecovery plugin for WordPress is vulnerable to SQL Injection via the 'data[id]' parameter in all versions up to, and including, 2.0.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-03)

> The WPRecovery plugin for WordPress is vulnerable to SQL Injection via the 'data[id]' parameter in all versions up to, and including, 2.0. This is due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query. This makes …

### CVE-2025-10728
**When the module renders a Svg file that contains a <pattern> element, it might end up rendering it recursively leading to stack overflow DoS**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-674
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-03)

> When the module renders a Svg file that contains a <pattern> element, it might end up rendering it recursively leading to stack overflow DoS

### CVE-2025-10729
**The module will parse a <pattern> node which is not a child of a structural node.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-03)

> The module will parse a <pattern> node which is not a child of a structural node. The node will be deleted after creation but might be accessed later leading to a use after free.

### CVE-2025-40636
**SQL injection vulnerability in Joomla module mod_vvisit_counter v2.0.4j3.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-03)

> SQL injection vulnerability in Joomla module mod_vvisit_counter v2.0.4j3. This vulnerability allows an attacker to retrieve database content via the ‘cip_vvisitcounter’ cookie at all endpoints where the plugin counts visits.

### CVE-2025-7721
**The JoomSport – for Sports: Team & League, Football, Hockey & more plugin for WordPress is vulnerable to Local File Inclusion in all vers...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-98
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-03)

> The JoomSport – for Sports: Team & League, Football, Hockey & more plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 5.7.3 via the task parameter. This makes it possible for unauthenticated attackers to include and execute arbitrary …

### CVE-2025-9209
**The RestroPress – Online Food Ordering System plugin for WordPress is vulnerable to Authentication Bypass in versions 3.0.0 to 3.1.9.2.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-03)

> The RestroPress – Online Food Ordering System plugin for WordPress is vulnerable to Authentication Bypass in versions 3.0.0 to 3.1.9.2. This is due to the plugin exposing user private tokens and API data via the /wp-json/wp/v2/users REST API endpoint. This makes it possible for u…

### CVE-2025-9286
**The Appy Pie Connect for WooCommerce plugin for WordPress is vulnerable to Privilege Escalation due to missing authorization within the r...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-620
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-03)

> The Appy Pie Connect for WooCommerce plugin for WordPress is vulnerable to Privilege Escalation due to missing authorization within the reset_user_password() REST handler in all versions up to, and including, 1.1.2. This makes it possible for unauthenticated attackers to to reset…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-03*
