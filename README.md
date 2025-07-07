# 🔐 ESP32 Self-Destructive Keylogger 

A hardware-based keylogger designed using the ESP32 microcontroller for ethical red team penetration testing. This project simulates real-world adversarial tactics, including stealth data exfiltration and forensic evasion via self-destruction.

---

## 📄 Project Summary

This patent-worthy invention functions as a covert USB device capable of:
- 🔑 Capturing keystrokes via HID emulation
- 💾 Storing encrypted logs on a hidden SD card partition
- 🌐 Exfiltrating data over the TOR network using host internet
- 💣 Triggering self-destruction on forensic detection (via voltage/current anomalies or remote command)

> **Note:** Developed strictly for educational, research, and ethical red team operations only.

---

## 🧠 Key Features

| Feature                      | Description |
|-----------------------------|-------------|
| 🔒 Encrypted Log Storage     | AES encryption ensures confidentiality of captured keystrokes |
| 🧰 Stealth USB Emulation     | Appears as a generic 32GB flash drive while operating as a keylogger |
| 🌐 TOR-based Data Exfil      | Uses host's internet connection to send logs through the TOR network |
| 💥 Auto Self-Destruct        | High-voltage pulse via transformer fries SD card and ESP32 controller on threat detection |
| 🕵️ Forensic Evasion         | Detects USB analysis tools or voltage anomalies to trigger wipe |
| 📡 Remote IoT Commands       | Supports remote trigger via hidden TOR-based command-and-control |

---

## ⚙️ System Components

- **Microcontroller**: ESP32-WROOM-32
- **Storage**: MicroSD (≥32GB)
- **Interface**: USB HID + Mass Storage Emulation (TinyUSB)
- **Power Source**: 5V from USB
- **Self-Destruct Module**: Step-up transformer circuit (up to 100V)
- **Firmware**: Python, Bash, FreeRTOS
---

## 👥 Authors

- **Viyanka Kamble** (`kitsune0104`)
- **Arindom Barman**

---

## 🏷️ Tags

`ESP32` `Keylogger` `TOR` `Cybersecurity` `Ethical Hacking` `Red Teaming` `Self-Destruct USB` `HID` `IoT` `Anti-Forensics`

---

## 🚨 Disclaimer

Use responsibly. The authors and contributors are **not liable** for any misuse of this project or its code.

