# Web Security Academy — lab notes

Working through the [PortSwigger Web Security Academy](https://portswigger.net/web-security),
building toward the Burp Suite Certified Practitioner exam.

All testing is performed against PortSwigger's own deliberately vulnerable lab
instances. Nothing in this repository targets any other system.

Related: [security review of my own Django project](https://github.com/MyCallAngel0/bluevoyage) — findings from applying this material to code I wrote.

---

## Progress

Stage 1 

| # | Topic | Labs | Apprentice done | Notes |
|---|-------|------|-----------------|-------|
| 1 | SQL injection | 18 | | |
| 2 | Authentication | 14 | | |
| 3 | Access control | 13 | | |

Stage 2 — the rest of server-side

| # | Topic | Labs | Apprentice done | Notes |
|---|-------|------|-----------------|-------|
| 4 | Path traversal | 6 | | |
| 5 | Command injection | 5 | | |
| 6 | Information disclosure | 5 | | |
| 7 | Business logic | 11 | | |
| 8 | File upload | 7 | | |
| 9 | SSRF | 7 | | |
| 10 | XXE injection | 9 | | |

Stage 3 — client-side

| # | Topic | Labs | Apprentice done | Notes |
|---|-------|------|-----------------|-------|
| 11 | Cross-site scripting | 30 | | |
| 12 | CSRF | 12 | | |
| 13 | CORS | 3 | | |
| 14 | Clickjacking | 5 | | |
| 15 | DOM-based vulnerabilities | 7 | | |
| 16 | WebSockets | 3 | | |

Stage 4 — my stack

| # | Topic | Labs | Apprentice done | Notes |
|---|-------|------|-----------------|-------|
| 17 | JWT attacks | 8 | | |
| 18 | OAuth authentication | 6 | | |
| 19 | API testing | 5 | | |
| 20 | Race conditions | 6 | | |

Stage 5 — advanced (after Stages 1–4)

NoSQL injection (4) · GraphQL (5) · SSTI (7) · Insecure deserialization (10) ·
Prototype pollution (10) · HTTP Host header (7) · Web cache poisoning (13) ·
Web cache deception (5) · Essential skills (2) · Request smuggling (22, last)

Stage 6 — exam: all Apprentice + Practitioner labs → mystery labs → practice exam → BSCP

---

## Tools

Small scripts written while solving labs. See [`tools/`](tools/).

---

## Write-up format

One commit per study session, 3 sessions per week.


