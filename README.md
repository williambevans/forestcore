# 🌲 ForestCore™ Station

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

## 🧪 Quick Start
- 📄 [Download Testing Card](docs/forestcore_testing_card.png)  
- 📐 [View Circuit Diagram](hardware/circuit_diagram.png)

---

## 🌍 Deployment Notes
- GitHub Pages: `docs/index.md`
- Custom style: `docs/style.css`
- Auto-release workflow: `.github/workflows/release.yml`

---

## 📁 Folder Overview
ForestCore/
├── hardware/ # Arduino firmware + schematics
├── src/ # React dashboard interface
├── mobile-app/ # React Native BLE app
├── docs/ # GitHub Pages launch + test docs
├── .github/workflows/ # GitHub Action for release automation
├── README.md # Project introduction
├── CHANGELOG.md # Development history
├── RELEASE.md # GitHub release content


---

## 🧭 Roadmap to v1.0.0
- 🖨️ STL printable enclosure
- 💾 EEPROM memory storage
- 🧠 Usage-based schedule engine
- ☁️ MQTT/webhook cloud integrations

---

## 🛡️ License
This project is licensed under the **Open Hardware License**.

---

**ForestCore™ is open-source wellness tech bridging nature and neuroscience.**
