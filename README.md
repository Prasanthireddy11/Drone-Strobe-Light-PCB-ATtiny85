# Drone-Strobe-Light-PCB-ATtiny85
# 🚨 Drone Strobe Light – ATtiny85 Based PCB Project

## 🔧 Project Overview

This project is a compact, low-cost **drone strobe light system** designed using the **ATtiny85 microcontroller**. The circuit drives high-intensity red and green LEDs in programmable flashing patterns. It is ideal for visual line-of-sight (VLOS) compliance and improved visibility during night or low-light drone flights.

---

## ✨ Features

- 🔴🟢 **Two-channel LED control**: One pin for red LEDs, one for green
- 💡 **High-luminance output** using 5mm or SMD 3528 LEDs
- 📟 **Pattern customization** via Arduino IDE (strobe/fade/blink)
- 🔌 **USB Debugging** support (via Type-C connector)
- 🔋 Operates on **5V or 9V** (regulated via AMS1117-5.0)
- 📏 **Compact PCB design** using EasyEDA for drones

---

## 🧰 Hardware Used

- ATtiny85 (DIP or SMD)
- AMS1117-5.0 Voltage Regulator
- USB Type-C Connector (KH-TYPE-C-16P)
- High-Intensity Red & Green LEDs (5mm or SMD)
- NPN Transistors (S8050 / 2N2222)
- JST/XT30 Power Input Connector
- SPST Slide Switch & Push Button
- Capacitors, resistors, ISP header

---

## 🧠 My Contribution

- Designed circuit in Proteus for simulation
- Created and routed the PCB in EasyEDA
- Programmed light patterns in Arduino IDE
- Debugged using USB interface and ISP programmer
- Designed for manufacturability and compact drone use

---

## 💻 Programming Notes

- Use Arduino IDE with ATtiny85 board support (via `ATTinyCore`)
- Flash code via USBASP or similar ISP programmer
- Code is compatible with low power sleep modes if required

---

## 🔄 Added Future Improvements

- RGB LED support for more visual modes
- DIP switch or rotary switch for mode selection
- Consider low-power mode for longer battery life

