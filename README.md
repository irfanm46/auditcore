# AuditCore

**Professional GRC Audit Simulation Platform — Learn by Doing, Not Reading**

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Offline](https://img.shields.io/badge/offline-first-darkgreen)
![Dependencies](https://img.shields.io/badge/dependencies-zero-orange)

**Live Demo:** [irfanm46.github.io/auditcore](https://irfanm46.github.io/auditcore)

---

## What is AuditCore

AuditCore is a browser-based GRC audit simulation platform that puts you through the full lifecycle of a real engagement — from scoping to findings to management response — across 15 industries and 5 frameworks.

It is built for GRC analysts, audit associates, and security professionals who need practical, scenario-based experience beyond certification prep. No login, no server, no setup — open the file and start auditing.

---

## Why It Exists

Most GRC training stops at theory. You can memorise ISO 27001 Annex A controls or study NIST CSF functions, but nothing in a textbook teaches you how to scope a PCI-DSS engagement, write a credible finding in 4C format, or decide whether to maintain or downgrade a rating after reading a management response.

AuditCore fills that gap by simulating the decisions a junior auditor makes on the floor — through realistic evidence documents, real framework references, and expert feedback on every answer.

---

## Platform Overview

| Component | Count | Detail |
|---|---|---|
| Audit Engagements | 15 | Full 7-phase simulations across 5 industries |
| Frameworks Covered | 5 | ISO 27001:2022, NIST SP 800-53, PCI-DSS v4.0, HIPAA, GDPR |
| ISO 27001:2022 Controls | 93 | All controls A.5–A.8 with descriptions |
| Control Testing Challenges | 20 | Domain-based, expert-explained |
| Risk Scenarios | 25 | With likelihood x impact expert ratings |
| Toolkit Components | 6 | Risk Matrix, Control Library, Findings Builder, CISA Reference, Framework Mapper, Evidence Checklist |
| Progression Ranks | 5 | Analyst, Senior Analyst, Lead Auditor, Principal, Partner |
| Tracked Skills | 6 | Scoping, Control Testing, Risk Assessment, Findings Writing, Compliance Knowledge, Report Quality |

---

## Engagements

| Company | Industry | Framework | Key Risk Area |
|---|---|---|---|
| NexaBank Dubai | Banking | ISO 27001:2022 | Access control, ISMS governance |
| AlphaFinance UK | Banking | PCI-DSS v4.0 | Cardholder data environment, network segmentation |
| GulfTrust Bank KSA | Banking | ISO 27001:2022 | Cryptography, third-party vendor risk |
| MedCore Hospital | Healthcare | HIPAA | ePHI access controls, workforce training |
| CareLink Clinic | Healthcare | HIPAA | Business Associate Agreements, data encryption |
| PharmaSafe Pharmaceuticals | Healthcare | HIPAA + FDA 21 CFR Part 11 | Audit trail integrity, computer system validation |
| GovSec Ministry | Government | NIST SP 800-53 | Privileged access, incident response, patch management |
| SmartCity Authority | Government | ISO 27001:2022 + NIST CSF | IoT security, OT network segmentation, GDPR |
| DefenceData Agency | Government | NIST SP 800-53 | Insider threat, supply chain risk, cryptography |
| RetailX | Retail | PCI-DSS v4.0 + ISO 27001:2022 | PAN storage, CDE segmentation, legacy data |
| ShopNow Platform | Retail | PCI-DSS v4.0 + GDPR | Consent management, legacy card data, DPAs |
| LuxuryMart | Retail | GDPR + ISO 27001:2022 | Breach notification, service account security |
| CloudNine SaaS | Technology | SOC 2 Type II + ISO 27001:2022 | Multi-tenancy isolation, change management, DR |
| DevSecOps Corp | Technology | ISO 27001:2022 + OWASP | Secure SDLC, production data in dev, SAST coverage |
| AIStart Innovations | Technology | GDPR + ISO 27001:2022 + EU AI Act | AI bias, automated decision-making, conformity assessment |

---

## What You Learn

- Run a full audit engagement from scoping to management response, not just individual controls
- Write findings in Big 4 format: Condition, Criteria, Cause, Effect, Recommendation
- Identify in-scope versus out-of-scope systems for a given framework and engagement context
- Rate risks using a 5x5 likelihood x impact matrix and justify your rating against expert analysis
- Assess controls as Effective, Partially Effective, or Ineffective based on evidence review
- Evaluate management responses and make defensible maintain, downgrade, or remove decisions
- Apply ISO 27001:2022, NIST SP 800-53, PCI-DSS v4.0, HIPAA, and GDPR to real-world scenarios
- Map security domains across multiple frameworks — a core skill for multi-standard engagements
- Generate professional audit reports in PDF format with structured findings and auditor declaration

---

## Tech

- Single HTML file — 372 KB, zero build process, works offline out of the box
- jsPDF v2.5.1 loaded from CDN for professional PDF report and certificate generation
- Vanilla JavaScript — no frameworks, no npm, no transpilation required
- localStorage persistence — all progress saved client-side, no account or server needed
- ES6+ — runs in Chrome, Firefox, Safari, Edge (any modern browser)

---

## Screenshots

Screenshots coming soon.

---

## Part of the cyber-tools Portfolio

**[annexa](https://github.com/irfanm46/annexa)** — ISO 27001:2022 Engineer Toolkit. Compliance heatmap, risk register, SoA generator, controls guide, threat mapper, and 2013-to-2022 diff tool. Live at [irfanm46.github.io/annexa](https://irfanm46.github.io/annexa).

**netkill** — Network security reference and analysis tool. Coming soon.

---

AUDITCORE v1.0.0 · Offline-First · Zero Dependencies · Educational Use Only

© 2025 Irfan M — All Rights Reserved
Licensed under CC BY-NC-ND 4.0
Use via irfanm46.github.io/auditcore only
Downloading, copying, or modifying this tool is not permitted
