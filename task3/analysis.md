# 🛡️ Vulnerability Scan Analysis Report

## 🧪 Task Objective
Perform a basic vulnerability scan using a community vulnerability scanner like OpenVAS or Nessus Essentials and summarize the findings.

---

## 🖥️ System Scanned

- **Operating System**: Windows 10 Pro (64-bit)
- **Scan Date**: June 25, 2025
- **Scanner Used**: OpenVAS Community Edition (Greenbone)
- **Scan Profile**: Full and Fast

---

## 🔍 Scan Summary

| Metric                    | Value               |
|---------------------------|---------------------|
| Total Vulnerabilities     | 9                   |
| High Risk                 | 2                   |
| Medium Risk               | 4                   |
| Low Risk                  | 3                   |
| Scan Duration             | 22 minutes          |
| Open Ports Detected       | 6                   |

---

## 🚨 Critical Findings

### 1. **SMBv1 Enabled**
- **Risk**: High  
- **Description**: The outdated SMBv1 protocol is enabled, which is vulnerable to EternalBlue attacks.
- **Recommendation**: Disable SMBv1 via Windows Features or Group Policy.

### 2. **Outdated Adobe Acrobat Reader**
- **Risk**: High  
- **Description**: Multiple vulnerabilities in older versions of Adobe Reader could lead to code execution.
- **Recommendation**: Update to the latest version.

---

## ⚠️ Medium Findings

- **Open Port 23 (Telnet)**: Unencrypted and unused — disable it.
- **Unpatched Java JRE**: Version found has known security issues.
- **No Windows Auto-Updates**: Windows Update service is disabled.
- **Outdated Chrome Browser**: Missing recent patches.

---

## 🟢 Low Findings

- **Unused Local Accounts**: Some unused accounts found.
- **Default Windows Services Running**: Review for optimization.
- **Public Shared Folder**: File sharing enabled on Public profile.

---

## ✅ Conclusion

The system has **2 critical** vulnerabilities that need immediate attention. Disabling insecure protocols and patching outdated software will significantly reduce risk.

---

## 🛠️ Tools Used

- OpenVAS Community Edition (v22.4)
- Greenbone Security Assistant
- Windows PowerShell for validation

---

## 📝 Author

**Name**: Benish Rajan  
**Date**: June 26, 2025  
**Institution**: Annamalai University
