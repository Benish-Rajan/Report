# 🔥 Firewall Configuration Summary

## 🖥️ System: Ubuntu 22.04 LTS

## 🔧 Firewall Tool Used: UFW (Uncomplicated Firewall)

## ✅ Commands Executed:

```bash
sudo ufw enable
sudo ufw allow ssh
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw deny 21
sudo ufw status verbose
```

## 🔍 Current Firewall Rules:

| Rule Type | Protocol | Port | Action         |
|-----------|----------|------|----------------|
| Allow     | TCP      | 22   | ALLOW (SSH)    |
| Allow     | TCP      | 80   | ALLOW (HTTP)   |
| Allow     | TCP      | 443  | ALLOW (HTTPS)  |
| Deny      | TCP      | 21   | DENY (FTP)     |

## 📝 Notes:
- SSH is allowed to maintain remote access.
- Blocking FTP helps secure the system by reducing attack surface.
- All other ports are denied by default unless otherwise specified.

## 🧑 Author: Benish Rajan
**Date**: June 27, 2025
