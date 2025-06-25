# 🛡️ Phishing Email Analysis Report

## 📌 Task Objective
Analyze a suspicious phishing email using its header and metadata to identify malicious traits.

---

## 📧 Email Summary

- **Subject**: Microsoft account unusual signin activity  
- **From Address**: "Microsoft account team" <no-reply@access-accsecurity.com>  
- **Reply-To**: sotrecognizd@gmail.com  
- **Return-Path**: bounce@thcullartfdes.co.uk  
- **Date**: Fri, 8 Sep 2023 05:47:04 +0000  
- **Message-ID**: `<032672b4-77ca-42f8-a036-9711e91bd1f3@DB8EUR06FT032.eop-eur06.prod.protection.outlook.com>`

---

## 🔍 Phishing Indicators Identified

### 1. Sender Spoofing
- **Domain**: `access-accsecurity.com` mimics Microsoft.
- **Analysis**: Not a legitimate Microsoft domain.

### 2. Reply-To Mismatch
- **Reply-To**: Free Gmail address (`sotrecognizd@gmail.com`) — not corporate.

### 3. Return-Path Mismatch
- **Return-Path**: Unrelated UK domain (`thcullartfdes.co.uk`).

### 4. Message-ID Anomaly
- Message-ID appears Microsoft-based but is inconsistent with Return-Path.

### 5. No Email Authentication
- SPF/DKIM/DMARC headers are missing or failed.

---

## ✅ Summary of Phishing Traits

| No. | Indicator               | Description |
|-----|--------------------------|-------------|
| 1   | Fake sender domain       | Uses lookalike Microsoft domain |
| 2   | Misleading display name  | "Microsoft account team" |
| 3   | Reply-To mismatch        | Gmail address not related to Microsoft |
| 4   | Return-Path mismatch     | Uses suspicious third-party domain |
| 5   | No authentication records| Lacks SPF/DKIM/DMARC headers |

---

## 🧠 Conclusion

This email is a **confirmed phishing attempt**.  
Avoid clicking links or downloading attachments.

---

## 🛠️ Tools Used

- MxToolbox Email Header Analyzer  
- WHOIS Domain Lookup  
- Manual Header Review  

---

## 📝 Author

**Name**: Benish Rajan  
**Date**: June 24, 2025  
**Institution**: Annamalai Univeristy
