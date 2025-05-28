# 📜 Data Protection & Privacy Policy

**Effective Date:** [Insert Date]  
**Version:** 1.0  
**Applies To:** All employees, contractors, third-party vendors

---

## 1. Purpose

This policy establishes guidelines to ensure protection of personally identifiable information (PII), including Aadhaar numbers, PAN data, and payment details, in compliance with India's **Digital Personal Data Protection Act (DPDP Act) 2023** and **ISO/IEC 27001:2022**.

---

## 2. Scope

Covers all data processing systems, databases, APIs, logs, and cloud storage where PII is collected, stored, transmitted, or processed.

---

## 3. Policy Statements

- All Aadhaar and PAN data must be **encrypted at rest and in transit**.
- Logs containing user identifiers or transaction metadata must be masked or sanitized before storage.
- AWS S3 buckets or DB exports must not contain plaintext PII unless encrypted using AES-256.
- Data should be **collected on a “need to know” and “purpose limitation” basis** only.
- **Third-party processors** must sign a Data Processing Agreement (DPA) before onboarding.
- Data retention for financial records must not exceed 7 years unless mandated.

---

## 4. Roles & Responsibilities

| Role              | Responsibility                                      |
|-------------------|------------------------------------------------------|
| CISO              | Policy enforcement and review                        |
| Database Admins   | Enforce encryption and masking                       |
| DevOps Team       | Secure storage, configure KMS and IAM policies       |
| Legal & Compliance| Ensure alignment with DPDP and RBI norms             |

---

## 5. Exceptions

Any exception to this policy must be approved by the CISO in writing.

---

## 6. Review & Revision

- Reviewed every 12 months or upon regulatory change.
- Next review due: [Insert Next Year]

---

## 7. References

- Digital Personal Data Protection Act, India – 2023  
- ISO/IEC 27001:2022 – Controls A.8 (Asset Management), A.12 (Cryptography)
