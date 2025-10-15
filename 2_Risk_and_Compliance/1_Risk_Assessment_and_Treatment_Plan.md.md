---
title: "Risk Assessment & Treatment Plan"
organization: "Unloved Supply Co (USC)"
version: "1.0"
author: "Lars Holmstrom"
date: "2025-10-15"
description: "Identifies and evaluates information-security risks for Unloved Supply Co’s ISMS and outlines treatment actions in accordance with ISO/IEC 27001:2022."
---

# ⚖️ Risk Assessment & Treatment Plan  
### Unloved Supply Co (USC)

---

## 1. Purpose
This document defines the **risk assessment and treatment process** for the Unloved Supply Co (USC) Information Security Management System (ISMS).  
It establishes how information-security risks are identified, evaluated, and treated in alignment with **ISO/IEC 27001:2022 Clauses 6.1.2 and 6.1.3**.

---

## 2. Objective
- Identify and assess risks that could affect the confidentiality, integrity, and availability of USC’s information assets.  
- Determine appropriate controls to mitigate unacceptable risks.  
- Maintain a consistent and repeatable method for evaluating and treating risks.

---

## 3. Methodology
USC applies a **qualitative risk assessment** approach, combining **likelihood** and **impact** on a 5-point scale.

| Rating | Likelihood | Impact | Example Description |
|--------|-------------|---------|--------------------|
| 1 | Rare | Negligible | Unlikely to occur or easily recoverable |
| 2 | Unlikely | Minor | Limited operational impact |
| 3 | Possible | Moderate | Noticeable impact on operations or reputation |
| 4 | Likely | Major | Significant impact or extended downtime |
| 5 | Almost Certain | Severe | Critical business or reputational damage |

**Risk Rating = Likelihood × Impact**  
Risk levels are categorized as:
- **Low (1–5)** — Acceptable, monitor periodically  
- **Medium (6–10)** — Mitigate through controls or process improvements  
- **High (11–25)** — Immediate treatment and management review  

---

## 4. Risk Assessment Results

| # | Risk Description | Asset / Process | Likelihood | Impact | Risk Rating | Treatment | Responsible | ISO Control (Annex A) |
|---|------------------|-----------------|-------------|---------|--------------|------------|--------------|-----------------------|
| **1** | Unauthorized access to Shopify admin account | Shopify / E-commerce | 3 | 5 | 15 (High) | Enable MFA, restrict admin access, review sessions monthly | ISMS Lead | A.5.15 Access Control, A.8.16 Monitoring |
| **2** | Compromise of social media accounts (Instagram, TikTok, Facebook) | Marketing / Brand reputation | 3 | 4 | 12 (High) | Use unique strong passwords, MFA on all platforms, use password manager | ISMS Lead | A.5.15 Access Control, A.5.18 Security of Information in Cloud Services |
| **3** | Data breach from third-party vendor (Apliiq or Mailchimp) | Vendor data handling | 2 | 5 | 10 (Medium) | Review vendor security policies, include confidentiality clauses, ensure data minimization | Founders | A.5.23 Supplier Relationship Security |
| **4** | Loss of design files or business data in iCloud | Cloud storage / Design assets | 2 | 4 | 8 (Medium) | Regular local backups, enable version history, ensure devices are encrypted | ISMS Lead | A.8.12 Data Backup |
| **5** | Payment data exposure via Shopify or PayPal | Customer data | 2 | 5 | 10 (Medium) | Rely on PCI DSS compliance of platforms, maintain secure credentials, monitor breach notifications | Founders | A.5.19 Information Security for Use of Cloud Services |
| **6** | Unintentional disclosure of customer data via email or support | Customer service | 3 | 3 | 9 (Medium) | Employee training, implement “need-to-know” principle, avoid storing customer data locally | ISMS Lead | A.6.3 Information Classification, A.6.8 Data Leakage Prevention |
| **7** | Malware infection or ransomware on design workstation | Local devices | 2 | 4 | 8 (Medium) | Maintain OS updates, enable built-in malware protection, offline backup | ISMS Lead | A.8.8 Protection Against Malware |
| **8** | Downtime or loss of Shopify service | Sales continuity | 3 | 4 | 12 (High) | Monitor Shopify status, communicate outages to customers, prepare contingency communication | Founders | A.5.29 ICT Readiness for Business Continuity |

---

## 5. Risk Treatment Summary

| Treatment Option | Description |
|------------------|-------------|
| **Mitigate** | Implement controls to reduce risk likelihood or impact. |
| **Transfer** | Use contractual or insurance arrangement
