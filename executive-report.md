# Cyber Risk & Compliance – Executive Summary

**Organization**: PayNex FinTech Pvt. Ltd.  
**Assessment Date**: May 2025  
**Assessor**: [Your Name] (Cybersecurity Risk Analyst)

---

## 🧭 Overview

This report provides an executive-level summary of PayNex’s cyber risk and compliance posture. It evaluates the organization's alignment with the following frameworks:

- **ISO/IEC 27001:2022**
- **NIST Cybersecurity Framework**
- **India’s Digital Personal Data Protection (DPDP) Act 2023**
- **RBI Cybersecurity Framework for Financial Institutions**

---

## 🧩 Key Observations

- **Risks Identified**: 7 critical risks across domains including:
  - Cloud security misconfigurations
  - Improper data handling (PII/Aadhaar)
  - Lack of vendor risk evaluations
  - No formalized incident response procedures

- **Compliance Status**:
  - **ISO/NIST Alignment**: ~70%
  - **DPDP Act Coverage**: ~75%

- **Implemented Policies**:
  - Data Protection Policy
  - Cloud Security Policy
  - Incident Response Policy


---

## 🚩 Gaps Identified

- ❌ No strong **data minimization** controls
- ❌ Lack of **grievance redressal** mechanism
- ❌ No enforced **data retention policy**
- ❌ Absence of automated **risk monitoring** and alerting

---

## 📊 Risk Management Summary

| ID       | Risk Area                     | Residual Risk | Status    | Linked Policy                  |
|----------|-------------------------------|----------------|-----------|--------------------------------|
| RSK-001  | Public S3 bucket (PII leak)   | Medium         | Open      | cloud-security-policy.md       |
| RSK-002  | Unencrypted Aadhaar storage   | High           | Open      | data-protection-policy.md      |
| RSK-003  | Hardcoded Razorpay API keys   | Medium         | Monitoring| data-protection-policy.md      |
| RSK-007  | No IR plan                    | High           | Open      | incident-response-policy.md    |

A complete heatmap is available in `diagrams/risk-heatmap.png`. The full register is in `risk-register-with-policy-mapping.xlsx`.

---

## 📈 Compliance Dashboard

A live Excel dashboard is included at `compliance-dashboard.xlsx` with visualizations to:

- Track open vs mitigated risks
- Monitor risk severity over time
- Link risks to controls and policies

---

## ✅ Recommendations

- Finalize and enforce **DPDP-specific requirements** like data subject rights and retention enforcement.
- Implement automated **log monitoring and alerting** for control validation.
- Conduct quarterly **risk reviews** and executive-level reporting.
- Train employees on updated policies and incident response simulation.

---

## 🔚 Conclusion

PayNex has taken foundational steps toward maturing its cybersecurity program. With critical policies in place and risk identification mechanisms working, the next phase should focus on:

- Closing compliance gaps
- Automating monitoring
- Enabling governance at scale

This living project serves as a benchmark for GRC readiness in the Indian fintech context.

---

