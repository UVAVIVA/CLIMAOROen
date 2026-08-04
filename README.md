# CLIMAOROen

**Open Source Zonal HVAC Control System**

CLIMAOROen is the English version of CLIMAORO, a complete system for centralized heating and cooling control in buildings with underfloor heating and heat pumps, adaptable to all types of systems.

---

## 🌐 Website

[https://UVAVIVA.github.io/CLIMAOROen/](https://UVAVIVA.github.io/CLIMAOROen/)

**🇮🇹 Versione italiana:** [https://UVAVIVA.github.io/CLIMAORO/](https://UVAVIVA.github.io/CLIMAORO/)

---

## 📖 What is CLIMAORO

CLIMAORO is a system that:

- **Optimizes the heat pump** by reducing short cycling
- **Manages multiple zones** centrally with weight-based logic and thresholds
- **Communicates without WiFi** thanks to ESP-NOW (fallback)
- **Works alongside the traditional system** without replacing it
- **Costs less than €15 per thermostat** (compared to €100-250 for commercial systems)

---

## 📷 Thermostats

<img src="images/termostati/1.jpg" alt="Thermostat 1" width="32%"> <img src="images/termostati/2.jpg" alt="Thermostat 2" width="32%"> <img src="images/termostati/3.jpg" alt="Thermostat 3" width="32%">

---

## 🔧 Project Status

| Feature | Status |
|---------|--------|
| Summer cooling | ✅ In production |
| Dehumidifiers | ✅ Integrated |
| Photovoltaics | ✅ Integrated |
| Winter logic | 🔄 Ready, waiting for testing |
| Documentation | 📝 Under construction |

---

## 🔌 Mobile thermostat

<img src="images/termostato-mobile/1.jpg" alt="Mobile thermostat 1" width="32%"> <img src="images/termostato-mobile/2.jpg" alt="Mobile thermostat 2" width="32%"> <img src="images/termostato-mobile/3.jpg" alt="Mobile thermostat 3" width="32%">

**Part list:**

- [ESP32-C6 board](https://it.aliexpress.com/item/1005007676682081.html)
- [Temperature and humidity sensor (SHT4x)](https://it.aliexpress.com/item/1005009954170157.html)
- [Charger / power supply](https://it.aliexpress.com/item/1005008268805480.html)

**3D printed mobile thermostat case:**

- [termostato-ovale-19-c6.3mf](docs/files/termostato-ovale-19-c6.3mf)
- Recommended material: **PETG**
- Note: the file can only be opened with **OrcaSlicer** or **Flash Studio**

**Configuration for compilation:**

- [Main config file (English example)](https://github.com/UVAVIVA/CLIMAOROen/blob/main/termostato_example.yaml)

---

## 🧩 Main Components

| Component | Description |
|-----------|-------------|
| **Thermostats** | ESP32 (S3/C6/C3) devices with sensors, LEDs, and various installation modes (plug-in, 503 box) |
| **Manifold** | Central unit with relays for valves and circulator, with opto-isolated feedback |
| **Centralized logic** | Intelligent control that decides when to turn on the pump based on aggregated demand |

---

## 🎛️ Thermostat with encoder in a 503 box

<img src="images/termostato-encoder-503/1.jpg" alt="Thermostat with encoder 503 1" width="49%"> <img src="images/termostato-encoder-503/2.jpg" alt="Thermostat with encoder 503 2" width="49%">

**Part list:**

- [ESP32-S3 board](https://it.aliexpress.com/item/1005007171129437.html)
- [Rotary encoder](https://it.aliexpress.com/item/1005012374134834.html)
- [Display](https://it.aliexpress.com/item/1005009260256313.html)

---

## 🤝 LOOKING FOR COLLABORATIONS

This project is open to contributions. I am looking for people with specific skills to help develop and improve the system.

### Areas of interest

| Area | Skills needed |
|------|---------------|
| **Hardware** | PCB design, component optimization, reliability improvement, cost reduction |
| **Programming** | ESPHome firmware, control logic, Home Assistant integration, interface development |
| **Documentation** | Installation guides, technical manuals, translations |
| **Testing** | Testing on other systems, in different contexts, with different configurations |
| **App development** | Application to generate configurations without touching code |

### Who I'm looking for

People who already know how to work in these areas. The project has reached a level of complexity that requires solid experience: contributors must be able to read and modify code, understand electrical schematics, or document clearly and precisely.

It is not necessary to have experience in all areas, but it is important to have **solid skills in at least one of them**.

### How to contribute

1. Explore the project on [GitHub](https://github.com/UVAVIVA/CLIMAOROen)
2. Open an **issue** to discuss changes
3. **Fork** the repository
4. Submit a **pull request**

📌 **Learn more:** [https://UVAVIVA.github.io/CLIMAOROen/](https://UVAVIVA.github.io/CLIMAOROen/)

---

## 🛠️ Manifold

<img src="images/collettore/1.jpg" alt="Manifold 1" width="32%"> <img src="images/collettore/2.jpg" alt="Manifold 2" width="32%"> <img src="images/collettore/3.jpg" alt="Manifold 3" width="32%">

**Part list:**

- [ESP32-C6 board](https://it.aliexpress.com/item/1005006678253557.html)
- [Relay module (4+ channels)](https://it.aliexpress.com/item/1005007538301230.html)
- [Optocouplers](https://it.aliexpress.com/item/1005009598584430.html)

---

## 📜 License

MIT License – Copyright (c) 2026 UVAVIVA

---

**Built with passion, from scratch.**