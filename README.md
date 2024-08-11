# 🛠️ Arduino Radar Project 🚀

---

## 🧰 Components Used

- **🔌 Arduino Uno**: The brain of our radar system, controlling the servo motor and ultrasonic sensor.
- **🔄 Servo Motor**: Allows the ultrasonic sensor to rotate and scan the surroundings.
- **📡 Ultrasonic Sensor (HC-SR04)**: Measures the distance to objects by sending out sound waves and timing their return.
- **🔗 Jumper Wires**: Connect the components securely on the breadboard.
- **🔋 Breadboard**: A platform to build the circuit without soldering.

---

![arduino_radar_animation](https://github.com/user-attachments/assets/277dd99f-271f-4c0a-9169-92eb4ec97469)

## 🛠️ Circuit Assembly

1. **🛠️ Connect the Ultrasonic Sensor**: 
   - VCC to **5V** on Arduino
   - Trig to **Pin 9**
   - Echo to **Pin 10**
   - GND to **GND**

2. **🔧 Connect the Servo Motor**:
   - Signal to **Pin 11**
   - VCC to **5V**
   - GND to **GND**

3. **📍 Build the Circuit on Breadboard**: Assemble the components on the breadboard, ensuring proper connections using jumper wires.
--
-![Hardware Setup Image 1](https://github.com/user-attachments/assets/75e2a47d-8f2c-49c5-be0c-e465394167e2)
## ⚙️ How It Works

- **📈 Rotating Scan**: The servo motor rotates the ultrasonic sensor, allowing it to scan a wide area.
- **📏 Distance Measurement**: The sensor sends out sound waves; when these waves hit an object, they bounce back. The sensor then calculates the time taken for the sound to return and converts it into distance.
- **🖥️ Visual Display**: The data collected by the sensor is sent to a connected display (e.g., a computer) that shows a radar-like interface, visualizing the position of detected objects.

---
## 💻 Software Integration

- **💡 Arduino IDE**: Program your Arduino Uno to control the sensor and motor.
- **🌐 Processing App**: Visualize the radar data on your computer.

### 🔗 Download Processing App

- Visit [Processing.org](https://processing.org/download/) to download the app.
- Choose the appropriate version for your operating system.
- Follow the installation instructions to set up.

---

## 🎯 Project Outcome

This Arduino Radar project provides a practical demonstration of how ultrasonic sensors and servo motors can be used together to create a functional radar system. It’s a fantastic project for those interested in robotics, electronics, and programming.

---

## 🌟 Final Thoughts

This project not only enhances your understanding of Arduino and sensor technology but also gives you the satisfaction of building a working radar system. Enjoy the process and happy building!

---
![Thank You](https://img.shields.io/badge/Thank%20You!-blue?style=flat-square&logo=smile)

<!-- Graphical GIF Animation -->
<div class="gif-container" style="text-align: center; margin-bottom: 20px;">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzdob2I4cHdsdWhnbmtmYTBxbnk4cnl2YjZ1bGw5ZGZvMXBwdWc4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/00n6TSoGffGTLXSMPO/giphy.gif" alt="Working on it GIF" />
</div>
