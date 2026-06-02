# Daily Threat Intelligence — March 02, 2026

**Digest window (UTC):** 2026-03-02
**Generated:** 2026-06-02T07:34:33Z

## Threat brief

Mutiny Standard — exploitation likelihood rose sharply (EPSS 51% → 71% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Mutiny Standard — exploitation likelihood rose sharply (EPSS 51% → 71% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2012-3001
**mutiny standard Command Injection**
- **Signals:** EPSS
- **Asset:** mutiny standard
- **Attack:** Command Injection
- **CVSS max:** 8.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 51.3% (2025-03-30) → 70.6% (2026-03-02), Δ +19.3%**

> Mutiny Standard before 4.5-1.12 allows remote attackers to execute arbitrary commands via the network-interface menu, related to a "command injection vulnerability."

### CVE-2021-40731
**adobe acrobat RCE**
- **Signals:** EPSS
- **Asset:** adobe acrobat_dc
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:24:39.673
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 5.8% (2025-11-21) → 23.7% (2026-03-02), Δ +17.9%**

> Adobe Acrobat Reader DC version 21.007.20095 (and earlier), 21.007.20096 (and earlier), 20.004.30015 (and earlier), and 17.011.30202 (and earlier) is affected by an out-of-bounds write vulnerability when parsing a crafted JPEG2000 file, which could result in arbitrary code execut…

### CVE-2026-0006
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-06T04:16:02.823
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> In multiple locations, there is a possible out of bounds read and write due to a heap buffer overflow. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2004-0882
**conectiva enterprise_linux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** samba samba
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 33.0% (2025-06-20) → 46.8% (2026-03-02), Δ +13.7%**

> Buffer overflow in the QFILEPATHINFO request handler in Samba 3.0.x through 3.0.7 may allow remote attackers to execute arbitrary code via a TRANSACT2_QFILEPATHINFO request with a small "maximum data bytes" value.

### CVE-2011-0096
**microsoft windows_2003_server XSS**
- **Signals:** EPSS
- **Asset:** microsoft windows_2003_server
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 59.2% (2026-02-16) → 70.1% (2026-03-02), Δ +10.9%**

> The MHTML protocol handler in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, R2, and R2 SP1, and Windows 7 Gold and SP1 does not properly handle a MIME format in a request for content blocks in a document, whic…

### CVE-2012-4172
**adobe shockwave_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe shockwave_player
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.2% (2025-03-30) → 16.9% (2026-03-02), Δ +11.6%**

> Buffer overflow in Adobe Shockwave Player before 11.6.8.638 allows attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2012-4173, CVE-2012-4174, CVE-2012-4175, and CVE-2012-5273.

### CVE-2012-4173
**adobe shockwave_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe shockwave_player
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.2% (2025-03-30) → 16.9% (2026-03-02), Δ +11.6%**

> Buffer overflow in Adobe Shockwave Player before 11.6.8.638 allows attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2012-4172, CVE-2012-4174, CVE-2012-4175, and CVE-2012-5273.

### CVE-2012-4174
**adobe shockwave_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe shockwave_player
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.2% (2025-03-30) → 16.9% (2026-03-02), Δ +11.6%**

> Buffer overflow in Adobe Shockwave Player before 11.6.8.638 allows attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2012-4172, CVE-2012-4173, CVE-2012-4175, and CVE-2012-5273.

### CVE-2012-4175
**adobe shockwave_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe shockwave_player
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.2% (2025-03-30) → 16.9% (2026-03-02), Δ +11.6%**

> Buffer overflow in Adobe Shockwave Player before 11.6.8.638 allows attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2012-4172, CVE-2012-4173, CVE-2012-4174, and CVE-2012-5273.

### CVE-2012-4176
**adobe shockwave_player**
- **Signals:** EPSS
- **Asset:** adobe shockwave_player
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 5.1% (2025-03-30) → 15.9% (2026-03-02), Δ +10.8%**

> Array index error in Adobe Shockwave Player before 11.6.8.638 allows attackers to execute arbitrary code via unspecified vectors.

### CVE-2012-5273
**adobe shockwave_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe shockwave_player
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 3.7% (2025-03-30) → 15.3% (2026-03-02), Δ +11.6%**

> Buffer overflow in Adobe Shockwave Player before 11.6.8.638 allows attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2012-4172, CVE-2012-4173, CVE-2012-4174, and CVE-2012-4175.

### CVE-2025-48609
**google android Path Traversal**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** Path Traversal
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-03-06T04:15:58.680
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-02)

> In multiple functions of MmsProvider.java, there is a possible way to arbitrarily delete files which affect telephony, SMS, and MMS functionalities due to a path traversal error. This could lead to local denial of service with no additional execution privileges needed. User inter…

### CVE-2026-26705
**oretnom23 pharmacy_point_of_sale_system SQL Injection**
- **Signals:** CVSS
- **Asset:** oretnom23 pharmacy_point_of_sale_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T15:38:33.790
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> sourcecodester Pharmacy Point of Sale System v1.0 is vulnerable to SQL Injection in /pharmacy/view_product.php.

### CVE-2026-26706
**oretnom23 pharmacy_point_of_sale_system SQL Injection**
- **Signals:** CVSS
- **Asset:** oretnom23 pharmacy_point_of_sale_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T21:15:59.683
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> sourcecodester Pharmacy Point of Sale System v1.0 is vulnerable to SQL Injection in /pharmacy/view_receipt.php.

### CVE-2026-26707
**oretnom23 pharmacy_point_of_sale_system SQL Injection**
- **Signals:** CVSS
- **Asset:** oretnom23 pharmacy_point_of_sale_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T21:15:59.870
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> sourcecodester Pharmacy Point of Sale System v1.0 is vulnerable to SQL Injection in /pharmacy/view_supplier.php.

### CVE-2026-26709
**carmelo simple_gym_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** carmelo simple_gym_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T19:21:09.487
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> code-projects Simple Gym Management System v1.0 is vulnerable to SQL Injection in /gym/trainer_search.php.

### CVE-2026-26710
**carmelo simple_food_order_system SQL Injection**
- **Signals:** CVSS
- **Asset:** carmelo simple_food_order_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T16:16:21.417
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> code-projects Simple Food Order System v1.0 is vulnerable to SQL Injection in /food/routers/edit-orders.php.

### CVE-2026-26711
**carmelo simple_food_order_system SQL Injection**
- **Signals:** CVSS
- **Asset:** carmelo simple_food_order_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T16:16:21.593
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> code-projects Simple Food Order System v1.0 is vulnerable to SQL Injection in /food/view-ticket.php.

### CVE-2026-26712
**carmelo simple_food_order_system SQL Injection**
- **Signals:** CVSS
- **Asset:** carmelo simple_food_order_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T16:16:21.767
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> code-projects Simple Food Order System v1.0 is vulnerable to SQL Injection in /food/view-ticket-admin.php.

### CVE-2026-26713
**carmelo simple_food_order_system SQL Injection**
- **Signals:** CVSS
- **Asset:** carmelo simple_food_order_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T16:16:21.940
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-02)

> code-projects Simple Food Order System v1.0 is vulnerable to SQL Injection in /food/routers/cancel-order.php.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-02*
