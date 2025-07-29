# 🔐 Encrypted Keylogger with Simulated Exfiltration

## 📌 Objective
Build an educational proof-of-concept keylogger that:
- Captures keystrokes.
- Encrypts logs using symmetric encryption (Fernet).
- Simulates data exfiltration to a localhost server.
- Stores logs with timestamp.
- Adds optional startup persistence and a kill switch.

## 🛠 Tools & Libraries
- Python 3.x
- pynput (keystroke capturing)
- cryptography (AES/Fernet encryption)
- base64 (log encoding)
- requests (HTTP simulation)
- Flask (localhost server)
- Windows batch script (optional persistence)

## 🧪 Features
- **Keystroke Capture:** Records all keyboard input.
- **Encryption:** Encrypts logs using `cryptography.fernet` to protect data.
- **Timestamped Logging:** Each log includes date and time.
- **Simulated Exfiltration:** Sends base64-encoded logs to a Flask server on localhost.
- **Kill Switch:** Pressing `ESC` key will stop the logger and trigger exfiltration.
- **Persistence (optional):** Adds keylogger to startup via batch file (Windows).

## 🛡️ Ethical Consideration
This keylogger is created for **cybersecurity awareness and educational research only**. Never deploy this on machines or networks without **explicit permission**. Unauthorized usage is illegal.

## 📷 Sample Output (Encrypted log snippet)
