# 🔐 Task 4: Setup and Use a Firewall (Linux)

## 🎯 Objective:
Configure a firewall on a Linux system using UFW to block and allow traffic according to predefined rules.

---

## 🛠️ Tools Used:
- **OS**: Ubuntu 22.04 LTS
- **Firewall**: UFW (Uncomplicated Firewall)

---

## 📝 Configuration Summary:

Commands executed:

```bash
sudo ufw enable
sudo ufw allow ssh
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw deny 21
```

Rules verified using:

```bash
sudo ufw status verbose
```

---

## 📂 Deliverables:

| File Name            | Description                         |
|----------------------|-------------------------------------|
| `firewall_config.md` | Configuration summary and rules     |
| `README.md`          | Task overview and usage instructions|

---

## 🧑 Author: Benish Rajan
**Date**: June 27, 2025
