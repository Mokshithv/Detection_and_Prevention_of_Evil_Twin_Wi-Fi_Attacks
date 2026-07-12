# Detection and Prevention of Evil Twin Wi-Fi Attacks

## Overview

This project demonstrates and detects **Evil Twin Wi-Fi Attacks** in a controlled laboratory environment. It combines offensive security techniques for cybersecurity education with defensive mechanisms to help users identify rogue Wi-Fi access points.

The project consists of:

- ESP8266-based Evil Twin Access Point
- Fake Captive Portal Simulation
- Android Detection Application
- TP-Link AC600 Monitor Mode Testing
- Kali Linux Wireless Analysis Tools

> **Note:** This project is intended **only for cybersecurity education, research, and authorized laboratory testing.**

---

## Features

- Scan nearby Wi-Fi networks
- Clone target SSID using ESP8266
- Fake captive portal simulation
- Wi-Fi credential capture demonstration (Lab Only)
- Android application for Evil Twin detection
- SSID & BSSID comparison
- Detection of duplicate SSIDs
- Real-time Wi-Fi scanning
- Educational demonstration of Wi-Fi attacks

---

## Project Structure

```
.
├── Evil-Twin.ino                # ESP8266 source code
├── esp8266_deauther_1mb.bin     # ESP8266 firmware
├── ESP8266Flasher.exe           # Firmware flashing utility
├── Project_Report.pdf           # Mini Project Report
└── README.md
```

---

## Hardware Requirements

- ESP8266 NodeMCU
- TP-Link AC600 Wi-Fi Adapter
- Raspberry Pi / Laptop
- Android Smartphone
- USB Cable

---

## Software Requirements

- Arduino IDE
- ESP8266 Board Package
- Kali Linux
- Aircrack-ng Suite
- Wireshark
- Android Studio

---

## Installation

### Step 1

Install Arduino IDE.

### Step 2

Install ESP8266 Board Package.

### Step 3

Open

```
Evil-Twin.ino
```

Compile and upload it to the ESP8266.

OR

Flash

```
esp8266_deauther_1mb.bin
```

using

```
ESP8266Flasher.exe
```

---

## Usage

1. Flash firmware to ESP8266.
2. Power the ESP8266.
3. Connect to the device.
4. Scan nearby Wi-Fi networks.
5. Select a target SSID.
6. Start the demonstration.
7. Use the Android application to detect cloned Wi-Fi networks.

---

## Detection Method

The Android application checks:

- SSID
- BSSID
- Signal Strength (RSSI)
- Security Type

If two networks have the same SSID but different BSSIDs, the application alerts the user about a possible Evil Twin Attack.

---

## Technologies Used

- ESP8266
- Arduino
- C++
- Android
- Java
- Kotlin
- Kali Linux
- Aircrack-ng
- Wireshark

---

## Educational Purpose

This repository demonstrates:

- Rogue Access Point Creation
- Evil Twin Attack Simulation
- Captive Portal Demonstration
- Wi-Fi Security Awareness
- Evil Twin Detection

The project is designed for cybersecurity learning and research.

---

## Disclaimer

This project is provided **strictly for educational, research, and authorized security testing purposes**.

Do **NOT** use this project against networks, devices, or systems without explicit permission.

The author is **not responsible** for any misuse or illegal activities performed using this code.

---

## Author

**Mokshith V**

BE Computer Science & Engineering (Cyber Security)

Impact College of Engineering and Applied Sciences

Bengaluru, Karnataka

---

## License

This project is released for educational purposes.

Please respect all applicable laws and use responsibly.
