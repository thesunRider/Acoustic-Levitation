# Ultrasonic Levitator - Pure Analog Implementation

## 🚀 Project Overview
This project demonstrates an **ultrasonic levitator** built using two 40kHz ultrasonic transducers. Unlike conventional microcontroller-based implementations, this design leverages **pure analog circuitry** to achieve precise phase control for dynamic levitation.

By carefully positioning the transducers, a **standing wave** is formed between them, creating alternating high-pressure (antinodes) and low-pressure (nodes) regions. Small objects can be levitated at these low-pressure nodes. The key innovation here is a **controllable phase shift** that allows dynamic adjustment of levitation points without relying on a microcontroller.

## 🛠️ How It Works
- A **555 timer** generates a stable 40kHz ultrasonic wave.
- A **CD4066 PLL (Phase-Locked Loop)** generates a second wave locked to the input frequency but with an adjustable **phase shift**.
- By applying a **DC offset to the VCO input of the PLL**, the phase shift can be precisely controlled.
- This allows real-time manipulation of levitation points by shifting the standing wave pattern dynamically.

## 🔧 Hardware Components
- **Ultrasonic Transducers (40kHz, 2x)**
- **555 Timer IC** (Wave Generation)
- **CD4066 PLL** (Phase Control)
- **Resistors, Capacitors, and Potentiometers** (For fine-tuning)
- **Power Supply (5V - 12V)**

## 🔬 Circuit Design
The circuit consists of:
1. A **555 timer-based oscillator** that generates a steady 40kHz signal.
2. A **PLL circuit** (CD4066) that locks onto this signal and provides a phase-adjustable output.
3. A **DC-controlled phase shift mechanism**, where a variable voltage controls the phase shift dynamically.

## 📷 Demonstration
![Ultrasonic Levitation](link-to-video-or-gif)

## 📜 Schematic Diagram
![Circuit Schematic](link-to-schematic-image)

## 🎯 Features & Advantages
✅ **Fully Analog Design** – No microcontrollers required!  
✅ **Precise Phase Control** – Adjust standing wave positions dynamically.  
✅ **Low-Cost Components** – Uses readily available ICs and parts.  
✅ **Expandable & Scalable** – Can be adapted for more advanced levitation experiments.  

## 📌 Future Improvements
- Implementing **closed-loop control** using sensors to stabilize the levitated object.
- Exploring **higher frequencies** for finer control over smaller particles.
- Experimenting with **multi-axis levitation** for more dynamic object manipulation.

## 📂 Repository Structure
```
📁 Ultrasonic-Levitator
│-- 📜 README.md  (This File)
│-- 📁 Schematics  (Circuit Diagrams & PCB Layout)
│-- 📁 Simulation  (SPICE Simulations & Results)
│-- 📁 Code (If any firmware is needed in the future)
│-- 📁 Media  (Videos, Images, and Demos)
```

## 🤝 Contributing
Feel free to fork this repository, suggest improvements, or experiment with new phase control methods. Pull requests are welcome!

## 📜 License
This project is open-source and licensed under the **MIT License**.

---
🚀 **Built with passion for analog electronics!** If you find this interesting, consider giving a ⭐ to the repository!  
For any discussions, feel free to reach out. Happy experimenting! 🛠️

#Ultrasonics #AnalogElectronics #Levitation #DIY #Makers #Engineering
