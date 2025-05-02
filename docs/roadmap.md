# 🌱 **LuminPlant Project Roadmap**

---

## 🧙‍♂️ **Phase 1: Core Lighting System (Complete)**

### 🌟 Goals:
- Build a functioning light control system based on ambient light
- Simulate natural sunlight phases using an RGB LED ring
- Integrate ESP32 with ESPHome and Home Assistant

### ✅ Tasks Completed:
- ESP32 Dev Kit C V4 configured with WiFi, OTA, API encryption
- WS2812 LED ring wired (GPIO4) and controlled via `neopixelbus`
- Analog LDR sensor connected (GPIO36) and calibrated
- Smooth sunrise–noon–sunset light transitions scripted
- Automatic trigger when ambient light drops below threshold
- Integrated into Home Assistant dashboard for control & monitoring

---

## **Phase 2: Sensor Expansion (In Progress)**

### 🌟 Goals:
- Add environmental monitoring to LuminPlant
- Begin laying the foundation for automation based on real-world conditions

### Features to Implement:
- [ ] Soil moisture sensor integration (analog or capacitive)
- [ ] Water level monitoring (ultrasound)
- [ ] Temperature and humidity sensor (DHT22 or BME280)
- [ ] Display sensor values in Home Assistant
- [ ] Use sensor thresholds to trigger warnings or actions

---

## **Phase 3: System Modularity & Documentation**

### 🌟 Goals:
- Turn LuminPlant into a shareable, modular, open-source system

### 🛠 Tasks:
- [ ] Split ESPHome config into modules (`light`, `sensors`, `irrigation`, etc.)
- [ ] Provide easy enable/disable structure via `!include` system
- [ ] Create `README.md` with clear usage instructions
- [ ] Add wiring diagrams (`docs/wiring.md`)

---

## 🌐 **Phase 4: Remote Control & Visualization**

### 🌟 Goals:
- Make the system more interactive and insightful for users

### Features to Add:
- [ ] Water level alerts via notification
- [ ] “Smart mode” vs “manual mode” toggle
- [ ] Optional webhook or MQTT support

---

## **Phase 5: Automated Watering (Planned)**

### 🌟 Goals:
- Build a reliable, safe self-watering system

### 💧 Key Components:
- [ ] Water pump with relay
- [ ] Soil moisture threshold-based activation
- [ ] Water level check before pumping
- [ ] Emergency stop/failsafe logic
- [ ] Manual watering trigger from dashboard

---

## **Long-Term Vision**

- Enable a complete autonomous plant care system
- Use LuminPlant as a showcase/portfolio project
- Possibly extend to a multi-plant/multi-room system