# 🛡️ Cloud Security Policy

**Effective Date:** [Insert Date]  
**Version:** 1.0  
**Applies To:** All employees, DevOps, Cloud Admins

---

## 1. Purpose

To ensure secure use of cloud platforms such as AWS, Azure, or GCP, by enforcing cloud-native security controls, and aligning with ISO/IEC 27001:2022 controls A.9 (Access), A.12 (Operations), and A.13 (Communications Security).

---

## 2. Scope

All cloud-hosted services, storage, compute, IAM policies, and configuration management.

---

## 3. Policy Statements

- **S3 buckets must be private by default**, with no public access unless explicitly approved.
- IAM policies must follow **least privilege**. Root account usage is prohibited.
- All access logs must be forwarded to a centralized log manager (e.g., Wazuh/Splunk).
- Cloud resources must use **multi-factor authentication (MFA)** and secure key management (e.g., AWS KMS).
- Cloud configs must be audited weekly using AWS Config or GCP Security Command Center.

---

## 4. Roles & Responsibilities

| Role         | Responsibility                                |
|--------------|-----------------------------------------------|
| DevOps Lead  | IAM, audit configs, enforce automation        |
| Cloud Admin  | Secure buckets, implement backup policies     |
| Security Team| Cloud monitoring, log collection, and review  |

---

## 5. Review & Exceptions

- Reviewed annually or during infrastructure change.
- Exceptions require CISO and CTO sign-off.

---

## 6. References

- ISO/IEC 27001:2022 Controls: A.9, A.12, A.13  
- AWS CIS Benchmark v1.5  
