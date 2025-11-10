# Perabots
Perabots Competition – Autonomous Robotics Challenge Designed and programmed a two-wheeled autonomous robot capable of mapping a track and optimizing its path for speed and accuracy. 

## ⚙️ Main Components Used
**Hardware:**
- Raspberry pi

  

**Software & Tools:**
- Webots Simulator  
- STM32CubeIDE  
- KiCad / Proteus (for circuit design)  
- Python / C Programming  
- GitHub for version control

---

## 🔌 Circuit Diagram
Upload your circuit image (e.g., `circuit.png`) to your repository and link it here:

![Circuit Diagram](circuit.png)

_Add a short caption explaining what each section of the circuit does — e.g., voltage sensing, amplification, or display control._

---

## 🧩 Simulation (Webots)
Include screenshots, GIFs, or videos of your simulation here.  
You can embed them as images or link to YouTube/GitHub assets.

**Example:**
![Webots Simulation](simulation.gif)

_The Webots simulation was used to model the robot’s movement, sensor feedback, and control algorithm before implementing it in hardware._

---

## ⚙️ Operation
Describe how your system or robot operates step by step.

**Example:**
1. Power is supplied through the LM2596S regulator.  
2. The STM32F411 reads sensor data via the I2C module.  
3. Measured values are amplified and filtered by LM358P.  
4. The processed voltage and current are displayed on the LCD.  
5. The microcontroller logs data or adjusts behavior based on readings.

---

## 🧪 Discussion
Reflect on your results and findings.

**What went well:**
- The system successfully measured voltage and current with good precision.  
- The Webots simulation accurately modeled the sensor behavior.  

**What went wrong:**
- Noise affected the sensor readings at higher currents.  
- Timing issues occurred between I2C updates and LCD refresh.  

**Possible Improvements:**
- Add a Kalman filter or averaging function for cleaner data.  
- Improve hardware layout for better noise immunity.  
- Implement real-time plotting via serial communication.

---

## 🚀 Future Work
- Add wireless data logging (Bluetooth / Wi-Fi)  
- Integrate with a mobile or PC dashboard  
- Expand simulation to 3D path optimization  

---

## 🧰 Tools and Technologies
| Category | Tools |
|-----------|--------|
| Microcontroller | STM32F411 |
| Simulation | Webots |
| Circuit Design | KiCad / Proteus |
| Programming | C, Python |
| IDE | STM32CubeIDE |
| Version Control | GitHub |

---

## 👩‍💻 Contributors
| Name | Role |
|------|------|
| [Your Name](https://github.com/yourusername) | Firmware & Simulation |
| [Teammate Name] | Hardware & Circuit Design |

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Acknowledgements
Special thanks to:
- University of Sri Jayewardenepura – Faculty of Engineering  
- Perabots Competition organizers  


---
