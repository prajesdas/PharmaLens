# PharmaLens: Portable QR-Based Medicine Identification and Information System

## 📌 Project Overview

**PharmaLens** is a **QR/Barcode-based medicine identification and verification system** designed to enhance **medication safety, authenticity, and accessibility** across diverse healthcare environments. It integrates **high-speed scanning, secure database verification, counterfeit detection, and multilingual drug information retrieval** into a portable, user-friendly solution.

This innovation addresses the challenges of **counterfeit medicines, medication errors, and inaccessible drug information** by enabling **instant access to reliable pharmaceutical details** for patients, caregivers, pharmacists, and healthcare professionals.

---

---
* Figure 1: Example of medicine blister packs with hidden or difficult-to-read expiry details.
* Figure 2: Medicine tablets with embedded QR codes for identification.
* Figure 3: Front view of the PharmaLens handheld QR/Barcode medicine scanner.
* Figure 4: Rear view of the PharmaLens handheld QR/Barcode medicine scanner.
* Figure 5: Internal component layout of PharmaLens showing QR code scanner, LCD, PCB, and battery.
---

## Flowchart
<img width="569" height="1185" alt="image" src="https://github.com/user-attachments/assets/1a6d747f-0a1a-4946-bed3-bed30aa6601a" />



---
## Figure1
<img width="450" height="501" alt="image" src="https://github.com/user-attachments/assets/e2e58df3-2216-4633-88e9-d12f5c56e475" />


---
## Figure2
<img width="317" height="504" alt="image" src="https://github.com/user-attachments/assets/59f162d3-de5d-409a-aeb2-167c47cd536b" />

---
## Figure3

<img width="217" height="491" alt="image" src="https://github.com/user-attachments/assets/a2b8c8f7-aa0c-4dc1-9d22-e8ea43db133a" />



---
## Figure4

<img width="192" height="484" alt="image" src="https://github.com/user-attachments/assets/758f6de4-8aba-4c8e-9aae-df91ca643ebc" />



---
## Figure5
<img width="322" height="499" alt="image" src="https://github.com/user-attachments/assets/686bbcb6-4309-4fac-9ef1-460f7d963cf8" />




## 🚀 Key Features

* **Real-Time Medicine Verification**: Scans QR/barcodes on pharmaceutical packaging for instant drug identification.
* **Counterfeit Detection**: Cross-verifies scanned data with official regulatory/manufacturer databases.
* **Multilingual Accessibility**: Supports multiple languages with both **text and voice-assisted output**.
* **Offline Mode**: Uses locally cached database for uninterrupted operation in low-connectivity areas.
* **Assistive Features**: Large-text high-contrast display and text-to-speech for elderly and visually impaired users.
* **Integration Ready**: Connects with **Electronic Health Records (EHR)**, pharmacy systems, and telemedicine platforms.
* **Secure Data Handling**: Incorporates **encryption and privacy compliance (HIPAA/GDPR-ready)**.
* **Multi-Form Deployment**: Available as a **mobile app, handheld device, or integrated hospital/pharmacy module**.
* **AI-Powered Analytics**: Detects counterfeit drug circulation patterns in real time for regulatory alerts.

---

## 🔧 System Components

| Category               | Component                                   | Utilisation                         |
| ---------------------- | ------------------------------------------- | ----------------------------------- |
| Input & Identification | QR/Barcode Scanner Module                   | Captures and decodes medicine codes |
| Processing & Control   | Microcontroller / SBC (Raspberry Pi, ESP32) | Runs decoding, database queries, UI |
| Data Storage           | Local Memory (SD Card/EEPROM)               | Stores offline medicine database    |
| Connectivity           | Wi-Fi / Bluetooth                           | Syncs with cloud/EHR and updates    |
| User Interface         | LCD Display                                 | Shows drug info, dosage, expiry     |
| User Controls          | Buttons / Touch Input                       | Navigation and interaction          |
| Audio Output           | Speaker / TTS Module                        | Voice-based drug info               |
| Power Supply           | Li-ion Battery (800mAh, 3.7V)               | Portable energy                     |
| Alerts & Notifications | Buzzer / LED                                | Expiry alerts, counterfeit warnings |
| Security               | Batch Verification System                   | Confirms authenticity               |
| Integration            | Mobile App / EHR APIs                       | Healthcare system sync              |
| Sensors                | Temperature/Humidity                        | Ensures proper medicine storage     |
| Enclosure              | Handheld casing                             | Ergonomics and protection           |
| Software               | Embedded firmware                           | Scanning, decoding, encryption      |

---

## 📊 Results & Testing

* **High Accuracy**: Prevented distribution of counterfeit antibiotics in pilot tests.
* **Patient Safety**: Reduced risk of expired/counterfeit drug intake.
* **Accessibility**: Elderly and visually impaired users benefited from voice + large-text modes.
* **Rural Deployment**: Offline mode enabled authentication in no-internet areas.
* **Hospital Integration**: Seamless use with **pharmacy inventory and patient records**.

---

## ✅ Advantages Over Existing Solutions

1. **Active Counterfeit Detection** – Real-time cross-verification with regulatory databases.
2. **Multilingual + TTS Support** – Accessible for diverse and disabled populations.
3. **Offline Capability** – Works in rural/low-connectivity regions.
4. **Comprehensive Data** – Displays brand, strength, dosage, storage, side effects, and interactions.
5. **Batch-Level Authentication** – Prevents duplication of packaging.
6. **Healthcare Integration** – Syncs with EHR/HIS for compliance and tracking.
7. **User-Centric Interface** – Simplified large-text mode for elderly users.
8. **Secure Data Handling** – Encrypted, privacy-compliant.
9. **Multi-Form Deployment** – App, handheld device, or embedded solution.
10. **Public Health Utility** – Analytics to detect counterfeit trends regionally.

---

## 📐 System Flow (Conceptual)

1. **Scan Medicine** → QR/Barcode captured via scanner/camera
2. **Decode Data** → Extract product ID, batch number, authentication key
3. **Verify Database** → Cross-check with regulatory/manufacturer records
4. **Retrieve Info** → Brand, strength, expiry, storage, side effects
5. **Counterfeit Detection** → Flag mismatched/invalid results
6. **Display & Audio Output** → Show on LCD + read aloud if enabled
7. **User Options** → Save to "My Medicines", set reminders, view history
8. **Sync Updates** → Refresh records when online

---

## 📝 Abstract

PharmaLens is a **portable, QR/Barcode-based medicine verification system** that empowers patients and healthcare professionals with **instant, accurate, and accessible pharmaceutical information**. By combining **optical scanning, database verification, counterfeit detection, multilingual accessibility, and EHR integration**, it ensures **safer medication practices, regulatory compliance, and patient empowerment**. Its **offline mode, AI-driven analytics, and assistive accessibility features** make it a **scalable, secure, and inclusive healthcare innovation**.

---

## 👨‍🔬 Inventors

* Prajes Das
* Monjima Dey
* Parthiv Majumder
* Anindo Paul
* Tanmoy Ghosh
---

