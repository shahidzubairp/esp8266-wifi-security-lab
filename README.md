# ESP8266 WiFi Security Lab 🔬📡

An educational embedded systems project demonstrating
how WiFi protocol weaknesses and captive portals can be
abused in unsecured environments.

This repository is designed as a **learning and awareness lab**,
not a production attack tool.

---

## 📌 Purpose

The goal of this project is to:
- Understand how ESP8266 handles WiFi AP + STA modes
- Study captive portal behavior at the protocol level
- Learn how users can be misled on insecure networks
- Highlight why modern WiFi protections matter

---

## 🧠 What This Demonstrates

- DNS redirection behavior
- Captive portal mechanics
- Access point impersonation risks
- Limitations of user-side trust indicators
- Embedded networking constraints

---

## 🛠️ Platform

- ESP8266 (NodeMCU)
- Arduino framework
- Embedded web server
- DNS server handling

---
## 🔧 Development Environment Setup

This project uses the Arduino framework for ESP8266-based development.

### Board Manager Configuration

To compile and study the firmware in a local lab environment:

1. Open **Arduino IDE**
2. Go to **File → Preferences**
3. In **Additional Boards Manager URLs**,  add:https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
4. Open **Tools → Board → Boards Manager**
5. Install the required ESP8266 board definitions

> Note: This configuration is documented for educational and research purposes only.

----
## 📐 Architecture (High Level)

1. ESP8266 operates in AP + STA mode
2. Nearby networks are scanned
3. A captive portal simulates a recovery interface
4. User interaction demonstrates trust failure scenarios

No automated exploitation is intended.

---

## ⚠️ Ethical Notice

This project is:
- Tested only on owned hardware
- Intended strictly for education
- Not designed for real-world attacks

Misuse of this code may be illegal.
The author does not support or encourage misuse.

---

## 📓 Learning Outcomes

- Embedded WiFi stack behavior
- DNS-based traffic redirection
- Security implications of legacy WiFi designs
- Importance of WPA3, PMF, and user awareness

---

## 🔭 Future Work

- Defensive countermeasures
- Detection techniques
- Secure captive portal design
- Integration into hardware security labs

---

## 👤 Author

Shahid Subair  
ECE Engineer | Cybersecurity & Hardware Security Learner
