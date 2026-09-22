# ESP32-S3 Pocket AI Assistant 🧠🤖

A compact, pocket-sized hardware AI assistant built on the **ESP32-S3 Super Mini**, featuring voice recognition, cloud/local data processing, and a custom 3D-printed enclosure.

---

## 🛠️ Hardware Specifications (Bill of Materials)

Current components selected for the prototype:

- [x] **MCU:** ESP32-S3 Super Mini (Dual-core, 240MHz, built-in Wi-Fi & BLE)
- [x] **Main Display:** 2.0" Color IPS Display (ST7789V driver, 240x320 resolution, 7-pin SPI interface)
- [x] **Display Prototype:** 0.96" OLED Display (SSD1306, I2C interface) for dual-stage testing
- [ ] **Camera Module:** 18-pin standalone OV2640 camera board (with built-in 12MHz oscillator) *(Planned)*
- [ ] **Microphone Module:** 6-pin digital microphone module (INMP441, I2S interface) *(Planned)*
- [x] **Inputs:** 3x tactile buttons connected via a custom resistor ladder to a single analog GPIO (ADC Pin Optimization)
- [x] **Enclosure:** Custom 3D-printed chassis (Black Kingroon PETG, 0.2mm layer height, printed on Ender 3 V3 SE)
- [x] **Network:** Seamless mobile hot-spot routing (No local servers required for portability)


---

## 🚀 Key Features

- **Gemini AI Core:** Powered by Google's Gemini API for advanced multimodal text and vision processing.
- **Multilingual Support:** Native real-time processing of both Russian (🇷🇺) and English (🇺🇸) languages.
- **Vision & Silent Mode:** Captures images via the 18-pin OV2640 camera to perform OCR and visual analysis on text/objects without voice triggers.
- **Analog Pin Optimization:** Reads three physical control buttons through a single analog pin using a voltage divider circuit.
- **Ultra-Portable Bridge:** Direct secure HTTP streaming to cloud APIs over local smartphone Wi-Fi hotspot.
- **Push-to-talk:** Hold microphone button and talk without camera.

---

## 📅 Project Status

- [x] Repository initialized & architecture planned.
- [x] Ender 3 V3 SE calibrated and 3D printing profile optimized.
- [ ] Firmware development (I2C/SPI display drivers setup).
- [ ] Hardware assembly and soldering.
