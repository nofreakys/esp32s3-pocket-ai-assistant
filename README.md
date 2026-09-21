# ESP32-S3 Pocket AI Assistant 🧠🤖

A compact, pocket-sized hardware AI assistant built on the **ESP32-S3 Super Mini**, featuring voice recognition, облачную/локальную обработку данных, and a custom 3D-printed enclosure.

---

## 🛠️ Hardware Specifications (Bill of Materials)

Here is the current hardware setup for the prototype:

- [x] **MCU:** ESP32-S3 Super Mini (Dual-core, 240MHz, built-in Wi-Fi & BLE)
- [x] **Display Prototype:** 0.96" OLED Display (SSD1306, I2C interface)
- [ ] **Main Display:** Custom IPS/OLED Display *(Ordered / In Transit)*
- [ ] **Microphone Prototype:** 2-pin analog electret microphone with custom amplifier
- [ ] **Digital Microphone:** INMP441 (Digital I2S microphone for clean audio input) *(Planned)*
- [x] **Enclosure:** Custom 3D-printed black Kingroon PETG chassis (0.16mm layer height, printed on Ender 3 V3 SE)
- [x] **Controls:** 2x tactile buttons for navigation and Push-to-Talk (PTT) function
- [ ] **Power:** Li-Po battery charging circuit for full portability

---

## 🚀 Key Features

- **Modular Display Driver:** Firmware architecture supports switching between 0.96" OLED and custom IPS screens.
- **Voice-Activated AI:** Streams clean audio to a local backend server or AI API via Wi-Fi.
- **Ultra-Compact Design:** Custom engineered 3D chassis to fit comfortably in a pocket.
- **Eco-System Ready:** Integrated to work with a local **Dell OptiPlex 7040** home server.

---

## 📅 Project Status

- [x] Repository initialized & architecture planned.
- [x] Ender 3 V3 SE calibrated and 3D printing profile optimized.
- [ ] Firmware development (I2C/SPI display drivers setup).
- [ ] Hardware assembly and soldering.
