# ☁️ AWS S3 - Backup & Cost Optimization Project

**Project 3 / 5 - Completed by Janaki**
**Bucket Name:** `janaki-backup-bucket-2026`
**Live Link:** https://s3.console.aws.amazon.com/s3/buckets/janaki-backup-bucket-2026

## 📌 Project Goal
Company backup data ni safe ga store cheyali, thakkuva cost lo, bill ekkuva raakunda chusukovali.

## ✅ What I Implemented (4 Steps)

### 1. S3 Bucket Creation
- Bucket: `janaki-backup-bucket-2026`
- Region: ap-south-1 (Mumbai)
- Block Public Access: ON (Security)

### 2. Versioning Enabled
- Purpose: File pampora delete ayina malli restore chesukovachu
- Status: Enabled ✅

### 3. Lifecycle Rule
- Rule Name: Move-to-Glacier-Rule
- Condition: 30 days tarvata Standard -> Glacier ki move
- Benefit: Storage cost 80% save avuthundi

### 4. Budget & Alert
- Budget Name: $5 Monthly S3 Budget
- Amount: $5
- Current Status: Healthy & OK ✅
- Alert: Health-quick-setup notification created (2 Configured)

## 📸 Proof Screenshots
1. S3 Bucket Overview
2. Versioning Enabled
3. Lifecycle Rule Configured
4. Budget Dashboard - Healthy
5. Notification Center - Health Notification Created

> Screenshots ni ee folder lo upload chesanu /screenshots

## 💰 Cost Safety
- Lifecycle valla long-term cost thaguthundi
- $5 Budget valla bill $5 datagane email alert vastundi

## 🛠️ Tech Used
- AWS S3
- S3 Versioning
- S3 Lifecycle Management
- AWS Budgets
- AWS User Notifications (Health Dashboard)

## 🎯 Status
**100% COMPLETED, HEALTHY & COST SAFE** 🚀

---
*Created as part of AWS 5 Projects Challenge*
