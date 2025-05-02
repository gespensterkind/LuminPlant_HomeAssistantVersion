# 🌱 LuminPlant – Smart Plant Lighting System

**LuminPlant** is a sensor-controlled lighting project for indoor plants, using an ESP32, Home Assistant, and ESPHome. It simulates natural sunlight phases based on real-time ambient light conditions and lays the groundwork for future plant care automation.

---

## 🎯 Project Scope

- Automatic light control based on measured brightness
- Natural-looking sunrise–noon–sunset simulation using WS2812 LED ring
- Integration with Home Assistant dashboard
- OTA updates and secure API access
- Modular foundation for upcoming features like:
  - Soil moisture sensing
  - Water level monitoring with alerts
  - Temperature & humidity tracking
  - Automatic irrigation control

---

## 🔧 Hardware Used

| Component                  | Function                                |
|----------------------------|-----------------------------------------|
| ESP32 Dev Kit C V4         | Main controller with WiFi and OTA       |
| WS2812 LED ring (12 LEDs)  | Plant light                             |
| Analog LDR sensor          | Brightness detection                    |
| Power bank or USB adapter  | Power supply                            |

---

## 🧠 Features Implemented

- 🌗 Ambient light detection via analog sensor  
- ☀️ Smooth LED transitions (sunrise → noon → sunset → off)  
- 📟 Script logic written in ESPHome YAML  
- 🔒 Secure communication via encrypted API key  
- 📡 OTA firmware updates via WiFi  
- 📊 Sensor values & control exposed in Home Assistant

---

## 🛠 Tech Stack

- 📦 ESPHome (YAML-based automation)
- 🧠 Home Assistant
- 🧰 PlatformIO (for prototyping)
- 🌐 WiFi-based control & monitoring
- 🔌 Modular expansion capability

---

## 📦 Example Setup

![Wiring](docs/images/luminplant-wiring.jpg) *(optional)*

> `main.yaml` – located in `esphome/` – contains the current working config.

---

## 📄 License

MIT License – use, modify, and share freely.

---

## 💡 Background

This project is part of a practical preparation for an upcoming internship in embedded systems & automation. It aims to combine hands-on electronics with real-world IoT use cases, while deepening understanding of ESP32, Home Assistant, and sensor networks.

---

## 📬 Contact

Project by **Jule E**  
Questions, feedback, or collaboration ideas are welcome!
