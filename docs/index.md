<link rel="stylesheet" href="style.css">


# 🌲 ForestCore™  
**Your indoor forest therapy station.**

<img src="docs/banner.png" alt="ForestCore Banner" style="width:100%; border-radius:12px; margin:1rem 0;"/>

A compact, AI-regulated microclimate station designed to bring the stress-relieving effects of forest bathing into your home through phytoncide diffusion and immersive environmental simulation.

---

## 🔧 Features
- 💨 Smart phytoncide diffusion (alpha-pinene, limonene, etc.)
- 🌡️ Environmental sensors (temperature, humidity, light, VOCs)
- 🎨 Mood + circadian-responsive NeoPixel lighting
- 🔊 Forest sound playback (DFPlayer Mini)
- 📱 Mobile BLE control app (React Native)
- 🖥️ Web dashboard (React)
- 📐 Open hardware: Arduino + Fritzing + BOM

---

## 📦 Components
- Arduino Nano 33 IoT
- DHT22, BH1750, MQ-135
- WS2812B LED strip
- Ultrasonic mist maker
- DFPlayer Mini + speaker
- Atomizers + solenoid valves

---

## 🛠 Setup Instructions
1. Flash Arduino using `hardware/firmware/`
2. Wire components using `hardware/circuit_diagram.png`
3. Power using a 5V 2A USB-C adapter
4. Run the web dashboard from `src/`
5. Launch the mobile app in `mobile-app/` via Expo Go or React Native CLI

---

> _"Breath meets tech"_ — ForestCore simulates the stress-relieving power of trees by diffusing phytoncides, projecting circadian lighting, and sensing your environment in real-time.

---

### 🧠 What It Does
- 💨 Diffuses stress-reducing forest chemicals (alpha-pinene, limonene)
- 🌡️ Monitors environment: temperature, humidity, light, VOCs
- 🎨 Adjusts ambient light & sounds to mimic forest cycles
- 🧘 Responds to biofeedback and mood conditions

---

### 🛠 Built With
- Arduino Nano 33 IoT
- React + React Native
- BLE, WS2812 LEDs, DFPlayer Mini
- Sensors: DHT22, BH1750, MQ-135

---

### 🚀 Try the Beta
- [🧪 Setup Guide](../README.md)  
- [📦 Download Testing Card](forestcore_testing_card.png)

---

### 🔭 Roadmap to v1.0
- Printable STL enclosure  
- EEPROM memory + usage history  
- Cloud connectivity (MQTT, webhooks)

---

**Open Source Wellness**  
[View on GitHub](https://github.com/williambevans/forestcore)
