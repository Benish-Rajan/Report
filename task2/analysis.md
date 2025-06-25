# 🛡️ Phishing Email Analysis Report

## 📌 Task Objective
Analyze a suspicious phishing email and identify characteristics that confirm it is malicious.

---

## 📧 Email Summary

- **Subject**: Important Notice: Your Account Will Be Suspended
- **Sender Email**: support@amaz0n-secure.com
- **Claimed Brand**: Amazon
- **Attachment**: SecurityUpdate.zip
- **Links in Email**:
  - Displayed: `https://amazon.com/security-update`
  - Actual: `http://amaz0n-secure-login.ru/verify`

---

## 🔍 Phishing Indicators Identified

### 1. Sender Address Spoofing
- **Issue**: Email is from `amaz0n-secure.com` (note the zero).
- **Expected**: `@amazon.com`
- **Indicator**: Typo in domain is a common spoofing method.

### 2. Header Analysis
- **Tool Used**: [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- **Findings**:
  - Sender IP does not match Amazon's servers.
  - SPF/DKIM/DMARC: **Fail**
  - High spam score detected.

### 3. Suspicious Links
- **Displayed URL**: `https://amazon.com/security-update`
- **Real URL (on hover)**: `http://amaz0n-secure-login.ru/verify`
- **Issue**: Mismatch between displayed and actual link.

### 4. Urgent or Threatening Language
- **Example**: "Your account will be suspended within 24 hours if no action is taken."
- **Analysis**: Designed to induce panic and bypass rational thinking.

### 5. Attachment Risk
- **Filename**: `SecurityUpdate.zip`
- **Likely Malware**: Executable inside ZIP is a common trojan delivery method.

### 6. Spelling & Grammar Errors
- **Examples**:
  - "Your acount has beeen flagged."
  - "Click here immediatelly."
- **Conclusion**: Poor language is typical in phishing scams.

---

## ✅ Summary of Phishing Traits

| No. | Indicator                    | Description |
|-----|------------------------------|-------------|
| 1   | Fake sender domain           | Uses lookalike domain name |
| 2   | Failed email authentication  | SPF/DKIM/DMARC failures |
| 3   | Link mismatch                | Hover shows different destination |
| 4   | Urgent language              | Threatens suspension or loss |
| 5   | Malicious attachment         | Unsolicited ZIP file |
| 6   | Poor grammar/spelling        | Multiple typos found |

---

## 🧠 Conclusion

This email is **confirmed phishing**. The presence of spoofed addresses, threatening language, mismatched URLs, and failed authentication checks indicate a high risk of credential theft or malware infection.

---

## 🛠️ Tools Used

- [MxToolbox](https://mxtoolbox.com/EmailHeaders.aspx) – Header analysis
- [VirusTotal](https://www.virustotal.com/) – URL/Attachment check (optional)
- [Whois Lookup](https://who.is/) – Domain verification

---

## 📝 Author

**Name**: _Benish Rajan_   
**Course**: Cybersecurity Intern  
**Date**: June 24, 2025  
**Institution**: _Annamalai University_

