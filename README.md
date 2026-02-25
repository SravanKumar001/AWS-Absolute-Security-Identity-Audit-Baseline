# AWS Absolute Security – Identity & Audit Baseline

## 📌 Overview
This project establishes a secure AWS Identity and Audit Baseline by implementing IAM hardening, encrypted logging, monitoring, and exposure detection mechanisms.

The goal is to secure account access, enforce authentication controls, and ensure traceability of all AWS account activities.

---

## 🏗️ Security Architecture

The architecture consists of four security layers:

1. **Identity Layer** – IAM users, groups, MFA enforcement
2. **Audit Layer** – CloudTrail logging with encrypted S3 storage
3. **Monitoring Layer** – CloudWatch alarms, VPC Flow Logs
4. **Compliance & Exposure Detection** – Access Analyzer & Trusted Advisor

---

## 🔐 Implemented AWS Services

- IAM (Users, Groups, Policies, MFA, Password Policy)
- S3 (Secure Logging Bucket with Encryption & Versioning)
- CloudTrail (Multi-region logging + Log Validation)
- IAM Access Analyzer
- CloudWatch Alarms
- VPC Flow Logs
- Trusted Advisor

---

## 🚨 Security Scenarios Simulated

### 1️⃣ Unauthorized Console Login Attempt
CloudTrail captured failed login attempts.
CloudWatch triggered alerts.
MFA prevented account compromise.

### 2️⃣ Accidental Public S3 Bucket
IAM Access Analyzer detected exposure.
Public access was blocked immediately.

### 3️⃣ Missing Audit Logs
CloudTrail log validation detected disruption.
Bucket permissions were corrected.

---

## 🔒 Security Controls Implemented

- Root user MFA enabled
- Least privilege access model
- Encrypted log storage (SSE-S3)
- Multi-region audit logging
- Public access block enforced
- Continuous monitoring & alerting

---

## 🚀 Future Enhancements

- AWS Config integration
- AWS Security Hub
- Amazon GuardDuty
- Centralized compliance dashboard

---

## 👨‍💻 Author

C. Sravan Kumar  
B.Tech CSE – SRM University-AP  
Cybersecurity Enthusiast
