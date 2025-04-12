# 📡 Wireless Environmental Monitoring Circuit Using LoRa and XIAO ESP32 S3

This project involves a wireless environmental monitoring system using a custom 2-layer PCB designed in EasyEDA. It measures **temperature**, **humidity**, and **light intensity**, and transmits the data via **LoRa** for remote tracking.

---

## 📦 Components Used

- **LoRa Module** – Wireless long-range communication
- **HJ-SMB049 Antenna** – Compact LoRa antenna for signal transmission
- **XIAO ESP32 S3** – Microcontroller with Wi-Fi/BLE support
- **DHT11 Sensor** – Measures temperature and humidity
- **LDR (Light Dependent Resistor)** – Measures ambient light
- **1kΩ Resistor** – Used with LDR in voltage divider
- **Slider Switch (SK-22D02-G5)** – Power control switch
- **Headers and Resistors** – Modular interfacing & signal conditioning

---

## 🧠 Project Functionality

- ESP32 S3 reads:
  - Temperature & humidity from **DHT11**
  - Light level using **LDR + 1kΩ resistor** in voltage divider
- **Slider switch** toggles power
- Data sent via **LoRa module + HJ-SMB049 antenna** to remote receiver
- Monitored Parameters:
  - 🌡️ Temperature
  - 💧 Humidity
  - 💡 Light Intensity

---

## 🧩 PCB Design Details

- **Tool**: EasyEDA
- **Size**: 30x55 mm
- **ESP32 Header Spacing**: 15.24 mm
- **Layers**: 2

### 🟦 Top Layer
- ESP32 S3
- DHT11
- LDR + Voltage Divider
- LoRa Module
- HJ-SMB049 Antenna Connector
- SK-22D02-G5 Slider Switch

### 🟥 Bottom Layer
- Full copper ground plane
  - Reduces electrical noise
  - Improves power distribution
  - Enhances thermal dissipation
  - Stabilizes sensor readings

---

## 📸 Screenshots of the Design

### 🔌 Circuit Diagram
![Circuit Diagram](./Circuit.png)

### 🔷 PCB Layout - Front View
![PCB Front](./PCB_Front.png)

### 🔶 PCB Layout - Back View
![PCB Back](./PCB_Back.png)

### 🔭 2D View
![2D PCB](./2D_PCB.png)

### ⚙️ 3D View
![3D PCB](./PCB_3D.png)

---

## 🚀 Applications

- 🌾 Smart Agriculture
- 🌧️ Weather Stations
- 🏕️ Remote Data Logging
- 🏠 Home Automation
- 📡 LoRa IoT Networks

---

## 🌱 Possible Future Improvements

- Solar charging + battery management
- Replace DHT11 with DHT22
- Add RTC (Real-Time Clock)
- Integrate OLED display
- Add PIR/motion sensor
- Build LoRa dashboard (Python / Node-RED)

---

## ✅ Conclusion

- Compact and efficient PCB for LoRa-based IoT
- Accurate sensing of environmental data
- Reliable transmission using HJ-SMB049 antenna
- Stable performance with copper ground layer

---

> 🛠️ Designed and documented by **[Pawan Gupta]**  
> 📅 Date: 12 April 2025  
> 🖥️ Tool Used: EasyEDA
