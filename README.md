# 📊 ESP32 Benchmark App

![Platform](https://img.shields.io/badge/platform-ESP32-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Display](https://img.shields.io/badge/display-SSD1306%20OLED-lightgrey.svg)

A lightweight benchmark utility for ESP32 that tests **CPU performance**, **RAM usage**, and **simulated Flash I/O speed**. If connected, a 0.96" **SSD1306 OLED** display will show a **real-time progress bar** and final results.

---

## 🚀 Features

- ✅ **CPU Math Benchmark**
- ✅ **RAM Allocation Benchmark**
- ✅ **Simulated Flash I/O Benchmark**
- ✅ **OLED Progress Bar & Results**
- ✅ **Serial Monitor Logging**

---

## 🧰 Requirements

### Hardware
- ESP32 board (DevKit or similar)
- 0.96" OLED Display (SSD1306, 128x64, I2C)

### Libraries
Install via **Arduino Library Manager**:
- [Adafruit SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
- [Adafruit GFX](https://github.com/adafruit/Adafruit-GFX-Library)

---

## 🔌 Wiring (I2C OLED)

| OLED Pin | ESP32 Pin |
|----------|-----------|
| VCC      | 3.3V      |
| GND      | GND       |
| SDA      | GPIO 21   |
| SCL      | GPIO 22   |

---

## 📦 Installation

1. Clone or download this repository.
2. Open the `.ino` sketch in **Arduino IDE**.
3. Connect your ESP32 and OLED as described.
4. Upload the code.
5. Open **Serial Monitor** at `115200 baud`.

---

## 🧪 Output Example

Done:
RAM Used: 0 bytes
CPU Time: 1.45 sec
Flash I/O: 0.10 sec


