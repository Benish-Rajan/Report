
---

## 📌 Objectives

- Install and use **Wireshark** to monitor network activity.
- Capture traffic during simple browsing and pinging.
- Filter traffic by protocol (DNS, TCP, HTTPS).
- Analyze the purpose of captured packets.
- Export and share `.pcap` capture for review.

---

## 🔧 Steps Followed

1. Installed **Wireshark** from the official website.
2. Started a capture on the active network interface.
3. Visited `https://www.wikipedia.org` in a browser.
4. Pinging `8.8.8.8` from command line to generate ICMP traffic.
5. Stopped capture after 1 minute.
6. Filtered captured traffic by:
   - `dns`
   - `tcp`
   - `http` / `https`
7. Identified common protocols and traffic flows.
8. Exported results as `.pcap`.

---

## 🔍 Protocols Identified

| Protocol | Description                             |
|----------|-----------------------------------------|
| TCP      | Transmission Control Protocol – for web and secure traffic |
| DNS      | Resolves domain names like `wikipedia.org` |
| HTTPS    | Secure browsing data (TLS handshake visible) |

---

## 📈 Key Findings

- **DNS queries** are in plaintext and show visited domains.
- **HTTPS** data is encrypted, but IPs and handshake info are visible.
- **TCP handshakes** demonstrate session establishment.

---

## 🧾 Files

| File                | Description                                  |
|---------------------|----------------------------------------------|
| `network_capture.pcap` | Captured packets for browsing and ping     |
| `Wireshark_Network_Capture_Report.md` | Markdown report of analysis |
| `capture_screenshot.png` | Screenshot of filtered traffic in Wireshark |

---

## 🧠 Learnings

- Network protocols reveal a lot about system activity.
- Encryption hides content but not metadata.
- DNS and TCP are always foundational for web traffic.

---

## 📌 Requirements

- [Wireshark](https://www.wireshark.org/download.html)
- Basic understanding of network protocols

---

## 🧑‍💻 Author

**Name**: Benish Rajan S 
**Date**: July 2025

---

## ✅ License

This project is open for educational and learning purposes.
