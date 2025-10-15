---
title: "Incident Response Plan"
organization: "Unloved Supply Co (USC)"
version: "1.0"
author: "Lars Holmstrom"
date: "2025-10-15"
description: "Defines Unloved Supply Co’s process for detecting, reporting, responding to, and learning from information-security incidents in accordance with ISO/IEC 27001:2022 controls A.5.24–A.5.25."
---

# 🚨 Incident Response Plan  
### Unloved Supply Co (USC)

---

## 1. Purpose
This plan establishes a structured approach for identifying, reporting, and managing information-security incidents that could affect **Unloved Supply Co’s (USC)** data, systems, or operations.  
The objective is to minimize impact, restore normal operations quickly, and prevent recurrence.

---

## 2. Scope
Applies to all systems, personnel, vendors, and third parties involved in USC operations, including:
- Shopify, PayPal, Afterpay, and Apliiq systems  
- Cloud services (Apple iCloud, Mailchimp, QuickBooks)  
- Communication platforms and social media accounts  
- Devices or media storing company data  

---

## 3. Definition of an Incident
An **information-security incident** is any event that:
- Compromises confidentiality, integrity, or availability of data  
- Violates company policies or legal obligations  
- Indicates potential unauthorised access or misuse of USC assets  

**Examples:**
- Shopify or social-media account compromise  
- Accidental exposure of customer information  
- Malware infection or ransomware  
- Lost or stolen laptop/phone with company data  
- Unauthorized vendor access or data misuse  

---

## 4. Incident Classification

| Level | Description | Response Priority |
|-------|--------------|------------------|
| **Low** | Minor issue, no sensitive data exposed (e.g. phishing attempt blocked) | Monitor & document |
| **Medium** | Isolated event causing limited disruption | Respond within 24 hours |
| **High** | Confirmed data exposure or major outage | Immediate response, escalate to management |

---

## 5. Roles & Responsibilities

| Role | Responsibility |
|------|----------------|
| **ISMS Lead (Lars Holmstrom)** | Coordinate incident response, classify severity, document investigation, and report to management. |
| **Founders / Management** | Approve escalation decisions and allocate resources for remediation. |
| **Vendors / Partners** | Notify USC promptly of any incidents affecting shared data or operations. |
| **All Personnel** | Report suspected incidents immediately to the ISMS Lead and avoid independent remediation attempts. |

---

## 6. Incident Response Process

| Phase | Description | Key Actions |
|-------|--------------|-------------|
| **1. Identification** | Detect and verify the incident. | Review alerts, logs, and reports; determine scope and severity. |
| **2. Containment** | Limit damage and prevent spread. | Disable compromised accounts, isolate affected systems. |
| **3. Eradication** | Remove cause of incident. | Eliminate malware, revoke access, reset credentials. |
| **4. Recovery** | Restore normal operations. | Verify integrity of systems, restore backups, test services. |
| **5. Lessons Learned** | Review and improve controls. | Document root cause, corrective actions, and update policies. |

---

## 7. Communication & Escalation
- All incidents must be reported to **incident@unlovedsupply.co** (internal alias) or directly to the **ISMS Lead**.  
- **High-severity incidents** must be escalated to management immediately via phone or secure chat.  
- If customer or vendor data may be compromised, assess notification obligations under the **Privacy Act 1988 (Cth)**.

---

## 8. Documentation & Evidence
Each incident record must include:
- Date/time of detection and reporter  
- Systems and data affected  
- Root cause and actions taken  
- Evidence (logs, screenshots, emails)  
- Corrective/preventive measures  
- Residual risk rating  

Records are stored securely in the ISMS repository and referenced in the **Corrective Action Log**.

---

## 9. Post-Incident Review
Within **5 business days** of resolution, the ISMS Lead conducts a debrief to:
- Evaluate response effectiveness  
- Identify lessons learned  
- Recommend control improvements  

Results feed into the next **risk assessment** and **management review**.

---

## 10. Testing & Maintenance
- This plan will be reviewed annually or following any major incident.  
- Table-top simulations may be conducted to validate response capability.

---

## 11. Approval

| Name                 | Role             | Date       | Signature |
| -------------------- | ---------------- | ---------- | --------- |
| **Lars Holmstrom**   | ISMS Lead        | 2025-10-15 | _X_       |
| **Michael Campbell** | CEO / Co-Founder | 2025-10-15 | _X_       |

---

**© Unloved Supply Co — Internal Use / GRC Portfolio Demonstration Only**
