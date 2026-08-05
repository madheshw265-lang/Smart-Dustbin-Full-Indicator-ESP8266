<p align="center">
  <img src="banner.png" alt="Smart Dustbin Banner" width="100%">
</p>
# 🗑️ Smart Dustbin Full Indicator using ESP8266

An IoT-based Smart Dustbin Full Indicator using an **ESP8266 NodeMCU** and **HC-SR04 Ultrasonic Sensor**. The system detects the garbage level inside a dustbin and blinks an LED when the bin becomes full.

---

# 📖 Project Overview

This project is designed to monitor the garbage level inside a dustbin. The ultrasonic sensor continuously measures the distance between the sensor and the garbage. When the distance becomes less than the predefined threshold, the ESP8266 detects that the dustbin is full and blinks an LED to alert the user.

---

# 🎯 Objectives

- Detect the garbage level automatically.
- Indicate when the dustbin is full.
- Build a simple and low-cost IoT project.
- Demonstrate ESP8266 and ultrasonic sensor interfacing.

---

# ✨ Features

- Automatic garbage level detection
- LED indication when the bin is full
- Low-cost implementation
- Easy to build
- IoT-ready (can be upgraded with Wi-Fi notifications)

---

# 🧰 Components Used

| Component | Quantity |
|-----------|---------:|
| ESP8266 NodeMCU | 1 |
| HC-SR04 Ultrasonic Sensor | 1 |
| LED | 1 |
| 220Ω Resistor | 1 |
| Breadboard | 1 |
| Jumper Wires | As required |

---

# 🔌 Pin Connections

| ESP8266 | HC-SR04 |
|---------|----------|
| D1 | TRIG |
| D2 | ECHO *(through voltage divider)* |
| VIN | VCC |
| GND | GND |

### LED

| ESP8266 | LED |
|---------|-----|
| D5 | Positive |
| GND | Negative |

---

# ⚙️ Working Principle

1. The ultrasonic sensor measures the distance to the garbage.
2. The ESP8266 continuously reads the sensor value.
3. If the measured distance is less than **10 cm**, the dustbin is considered full.
4. The LED starts blinking.
5. If the distance is greater than 10 cm, the LED remains OFF.

---

# 📊 Block Diagram

![Block Diagram]

**block_diagram.jpeg**

---

# 🔧 Circuit Diagram

![Circuit Diagram]

**circuit_diagram.png**

---

# 🔄 Flowchart

![Flowchart]

**flow_chart.jpeg**

---

# 💻 Source Code

The complete Arduino source code is available in:

**SmartDustbin.ino**

---

# 📄 Project Report

The detailed project report is available in:

**Smart_Dustbin_Report.pdf**

---

# ✅ Advantages

- Low cost
- Easy to implement
- Low power consumption
- Reliable indication system
- Can be upgraded to a complete smart waste management system

---

# 🌍 Applications

- Homes
- Schools
- Colleges
- Offices
- Hospitals
- Shopping malls
- Public places

---

# 🚀 Future Scope

- Mobile notifications using Wi-Fi
- Blynk application integration
- Cloud data monitoring
- Multiple smart dustbins
- Automatic waste collection system

---

# 🛠️ Technologies Used

- ESP8266 NodeMCU
- Arduino IDE
- Embedded C++
- IoT
- HC-SR04 Ultrasonic Sensor

---

# 👨‍💻 Author

**Madhesh G**

Department of Computer Science and Engineering

---

## ⭐ If you like this project, consider giving it a Star!
