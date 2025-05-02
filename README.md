# -Earthquake-Detector-Using-Arduino-Uno
# 🌍 Earthquake Detector Using Arduino Uno

This project is a basic Earthquake Detector built using an **Arduino Uno** and an **MPU6050** gyroscope and accelerometer module. It monitors rotational motion using gyroscope data and triggers a buzzer and LED alert when abnormal movement is detected. This is useful for simple early warning systems or educational demonstrations of earthquake detection principles.

---

## 📦 Components Required

| Component           | Quantity |
|--------------------|----------|
| Arduino Uno        | 1        |
| MPU6050 Module     | 1        |
| Buzzer             | 1        |
| LED                | 1        |
| Resistor (220Ω)    | 1        |
| Breadboard         | 1        |
| Jumper Wires       | As needed |
| USB Cable          | 1        |

---

## 🔧 Circuit Connections

**MPU6050 to Arduino Uno:**

| MPU6050 Pin | Arduino Pin |
|-------------|-------------|
| VCC         | 5V          |
| GND         | GND         |
| SDA         | A4          |
| SCL         | A5          |

**Other Components:**

- **Buzzer:** Positive → Pin 10, Negative → GND  
- **LED:** Anode → Pin 11 (with 220Ω resistor), Cathode → GND
