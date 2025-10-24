# WHOIS & DNS Intelligence Report

## Overview

This document provides a professional OSINT-style summary of domain registration and DNS infrastructure details for **github.com**. It is suitable for security assessments, reconnaissance documentation, and threat intelligence reporting.

## Domain Summary

| Category | Details |
|

## DNS & Infrastructure Analysis

* **Global Load Balancing / CDN** observed via NS1 + AWS Anycast blend
* **No DNSSEC signing** → DNS responses are not cryptographically validated
* **Likely geo-distributed edge IPs** — IP `140.82.121.4` may vary per region
* **High security posture** with strict domain lock statuses (clientTransfer/Update/DeleteProhibited)

---

## Source Commands

```bash
whois github.com
nslookup github.com
```

----------|---------|
| **Domain Name** | github.com |
| **Registrar** | MarkMonitor Inc. (IANA ID 292) |
| **Created On** | 2007-10-09 |
| **Expires On** | 2026-10-09 |
| **Updated On** | 2024-09-07 |
| **Domain Status** | clientUpdateProhibited, clientTransferProhibited, clientDeleteProhibited |
| **Registrant Org** | GitHub, Inc. (US) |
| **Abuse Contact** | [abusecomplaints@markmonitor.com](mailto:abusecomplaints@markmonitor.com) — +1.208.685.1750 |
| **Email (Registrant/Tech)** | Protected via Request Form → [https://domains.markmonitor.com/whois/github.com](https://domains.markmonitor.com/whois/github.com) |
| **Name Servers** | dns1.p08.nsone.net, dns2.p08.nsone.net, dns3.p08.nsone.net, dns4.p08.nsone.net, ns-421.awsdns-52.com, ns-1283.awsdns-32.org, ns-1707.awsdns-21.co.uk, ns-520.awsdns-01.net |
| **DNSSEC** | unsigned |
| **Resolved IP (A record)** | 140.82.121.4 |
| **Infrastructure Note** | Uses hybrid NS1 + AWS DNS (global load balancing/CDN) |

---

Generated from `whois` and `nslookup` queries.
