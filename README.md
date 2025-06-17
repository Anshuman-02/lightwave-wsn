# 💡 Wireless Sensor Network with Light

This project explores the implementation of **Wireless Sensor Networks (WSNs) using light-based communication** such as **Visible Light Communication (VLC)** and **Optical Wireless Communication (OWC)**. It demonstrates how sensor nodes can use LEDs and photodiodes to transmit and receive data, offering an energy-efficient and secure alternative to traditional RF-based WSNs.

---

## 🧠 Problem Statement

Traditional wireless sensor networks (WSNs) rely on RF communication, which faces challenges like:
- Limited bandwidth and congestion
- High power consumption
- Electromagnetic interference (EMI)
- Security vulnerabilities

This project addresses these issues by using **light as a communication medium**, making WSNs more efficient, secure, and EMI-free.

---

## 🚀 Objectives

- Demonstrate data transmission via **modulated LED light**
- Analyze real-time sensing and communication using light
- Compare performance with RF-based systems
- Explore use cases in EMI-sensitive environments

---

## 🔧 Tools & Software Used

| Software | Purpose |
|----------|---------|
| **Arduino IDE** | Microcontroller programming and real-time sensor debugging |
| **Proteus** | Circuit simulation (optional) |
| **MATLAB** | Signal analysis and modulation simulations (optional) |
| **Fritzing / Tinkercad** | Circuit diagram design |
| **Postman / Serial Monitor** | Debugging and real-time output monitoring |

---

## 🧩 Working Principle

1. Sensor node collects analog data and converts it via ADC
2. Microcontroller modulates the data onto LED light (e.g., OOK, PWM)
3. Photodiode receives and demodulates the signal
4. Central node aggregates and forwards data to a controller or cloud
5. Secure, line-of-sight communication ensures low interference

---

## 📁 Repository Structure

```
lightwave-wsn/
├── report/
│   └── Light_Wave_PBL_Report.pdf
├── README.md
```

---

## 🌍 Applications

- **Hospitals & Healthcare**: EMI-free patient monitoring
- **Smart Homes/Buildings**: LED lighting + data exchange
- **Industrial Automation**: Real-time monitoring in RF-hostile zones
- **Underwater Comms**: IR/green-blue light for marine sensors
- **Military Use**: Secure, localized tactical communication
- **Smart Cities**: LED-based streetlight sensors and control
- **Retail & Navigation**: VLC for indoor positioning and tracking

---

## 📊 Key Features

- High-speed and low-latency communication
- Energy-efficient (dual-use LED)
- Secure due to directional, non-penetrative light signals
- Unregulated bandwidth (optical spectrum)
- Suitable for EMI-sensitive and confined environments

---

## 📚 References

- Ghassemlooy, Z., Popoola, W. O., & Rajbhandari, S. - Optical Wireless Communications
- IEEE 802.15.7 - Standard for Short-Range Optical Communication
- Chowdhury & Razzak - VLC for IoT (Sensors Journal)
- [IEEE Xplore](https://ieeexplore.ieee.org/)
- [ScienceDirect](https://www.sciencedirect.com/)
- [ResearchGate](https://www.researchgate.net/)
