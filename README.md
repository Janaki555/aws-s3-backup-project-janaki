# AWS S3 - Backup & Cost Optimization Project

**Project 3 / 5 - Completed by Janaki**
Bucket Name: `janaki-backup-bucket-2026` | Region: ap-south-1 (Mumbai)
Live Link: https://s3.console.aws.amazon.com/s3/buckets/janaki-backup-bucket-2026

### 📌 Project Goal
To securely store company backup data with high durability, enable versioning for recovery, and reduce storage costs using Lifecycle rules and Budget alerts.

### ✅ What I Implemented (4 Steps)

**1. S3 Bucket Creation**
- Bucket: janaki-backup-bucket-2026
- Region: ap-south-1 (Mumbai)
- Block Public Access: ON (Security Best Practice)

**2. Versioning Enabled**
- Purpose: Restore files if deleted or overwritten by mistake
- Status: Enabled ✅

**3. Lifecycle Rule (Cost Optimization)**
- Rule: Move data from S3 Standard -> S3 Glacier after 30 days
- Result: **30% cost saving** on long-term backup storage
- Use Case: Real-world FinOps practice

**4. AWS Budget & Alert**
- Budget: $5 monthly
- Alert: 80% threshold via SNS Email notification
- Purpose: Avoid unexpected billing

### 🛠️ Tech Stack
AWS S3, S3 Versioning, S3 Lifecycle Management, AWS Budgets, SNS

### 📊 Outcome
- Secure, versioned, cost-optimized backup solution
- Implemented Cloud Financial Management best practices
- Ready for NOC / Cloud Support role

---
**Author:** Jaligam Janaki Lakshmi | AWS Certified Cloud Practitioner | 1 Year @ TCS

## 🎯 Status
**100% COMPLETED, HEALTHY & COST SAFE** 🚀

---
*Created as part of AWS 5 Projects Challenge*
