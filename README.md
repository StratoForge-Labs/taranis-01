# 🛰️ Taranis-01

**High-Altitude Balloon (HAB) platform for telemetry, embedded systems validation and atmospheric data acquisition**

Taranis-01 is an experimental high-altitude balloon project designed to explore the upper atmosphere, collect environmental data, and validate robust embedded systems under extreme conditions.

Inspired by Taranis, the Celtic god of thunder and sky, this mission focuses on resilience, reliability, and real-world engineering.

---

## 🌍 Overview

The system is designed to:

- Reach the stratosphere (25–30 km altitude)
- Transmit real-time telemetry via LoRa (868 MHz)
- Perform onboard data logging
- Track and recover the payload
- Validate embedded systems in low-temperature and low-pressure environments

---

## 🧠 System Architecture

The project is divided into two main segments:

### ✈️ Air Segment (Payload)
- Microcontroller (MCU)
- LoRa transceiver
- GNSS receiver
- Environmental sensors:
  - Temperature
  - Pressure
  - Humidity
- Data logging (SD / Flash)
- Power system and battery management
- Thermal insulation enclosure

### 🖥 Ground Segment
- LoRa receiver
- Ground control software
- Telemetry decoding and visualization
- Local server (optional)
- Trajectory prediction tools

---

## 📡 Telemetry

Typical transmitted data includes:

- Latitude / Longitude
- Altitude
- Vertical speed
- Temperature
- Pressure
- Battery level
- Link quality (RSSI / SNR)

The telemetry protocol is designed to be:

- Low bandwidth
- Robust against packet loss
- Extensible for future features

---

## 🛠 Repository Structure

```bash
/firmware        # Embedded code (payload)
/hardware        # Schematics, PCB designs
/ground-station  # Ground control software
/shared          # Common definitions (protocols, data structures)
/tests           # Validation and experimental tests
```

## 🧪 Development Approach

The project follows an iterative engineering workflow:

1. System definition and requirements  
2. Rapid prototyping (COTS)  
3. Firmware and hardware co-design  
4. Testing (range, thermal, reliability)  
5. Integration and validation  
6. Flight execution  
7. Data analysis and improvements  

---

## 📐 Technical Targets

- Payload mass < 4 kg  
- Operating temperature down to –60°C  
- Flight duration: 2–3 hours  
- Communication range: > 50 km (line of sight)  
- Full payload recovery  

---

## ⚖️ Compliance & Safety

The system is designed to comply with:

- European unmanned free balloon regulations  
- ISM band usage (868 MHz)  
- Airspace coordination requirements  

---

## 🚀 Status

> 🧩 Early development phase  
> System definition and initial prototyping in progress.

---

## 🧑‍🚀 Authors

- Ángel Soto Boullosa
- Alejandro Fernández Rodríguez  