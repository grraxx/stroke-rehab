# Stroke Rehabilitation Glove

An open-source wearable device designed for post-stroke hand therapy, offering gamified rehabilitation through real-time motion tracking.

---

## 🚀 Project Overview

This project presents a novel approach to hand rehabilitation for stroke survivors by combining sensor technology and gamified experiences. Our glove tracks hand movements using flex sensors and an IMU, processes the data through an ESP32 microcontroller, and provides engaging, game-based exercises that aim to improve motor recovery and patient adherence.

### 👨‍💻 Team Members

- Goraksh Bendale  
- Manas Gharpure  
- Siddhesh Umarjee  
- Arnav Gogate  
- Apoorv Rane  
- Dhruv Jalan

#### Developed as part of:
- **ES117: World of Engineering**
Semester I, AY 2023–24
- **ES115: Design Innovation and Prototyping**  
Semester II, AY 2023–24

---

## 🎯 Problem Statement

Stroke is a leading cause of long-term motor disability, especially impairing fine motor control in hands. Existing therapy methods are:

- Repetitive and monotonous
- Low in engagement, leading to poor compliance
- Limited in duration/frequency due to resource constraints
- Lacking precise quantitative metrics for progress tracking

---

## 💡 Our Solution

We engineered a glove-based rehabilitation device with the following key features:

### 🔧 Sensor Fusion Architecture
- **5 Flex Sensors (FS-L-055-253-MP)**: Measure individual finger bends

### 🛠 Custom Hardware
- 3D printed modular brackets for comfort and adaptability
- Designed for minimal weight and high wearability

### 🧠 Microcontroller Integration
- **ESP32** processes sensor data and wirelessly transmits it to an external computer for real-time visualization and feedback

### 🎮 Gamification
- Developed basic gesture-based games (e.g., Flappy Bird clone)
- Utilized movement thresholds to interact with game mechanics, improving therapy engagement

### 🧪 Data Processing
- **Low-pass filter (moving average)** to remove high-frequency noise
- **Peak detection** to identify significant gestures like finger taps or full flexes

---

## 🛠 System Components

| Component              | Details                                  |
|------------------------|------------------------------------------|
| Microcontroller        | ESP32                                    |
| Sensors                | 5 Flex Sensors + MPU6050 (6-DOF IMU)     |
| Power Supply           | 9V battery (regulated)                   |
| Physical Structure     | 3D Printed Finger Rings/IMU Housing      |
| Data Transmission      | WiFi (ESP32 to PC)                       |
| Software               | Arduino for MCU, Unity for games         |

---

## 🔍 Limitations

Despite substantial progress, the following challenges remain:

- ❌ No clinical testing on actual stroke patients due to scope limitations
- ❌ DIY PCB and form-factor miniaturization not completed
- ❌ Inadequate comparative analysis with traditional methods

---

## 📖 Case Study: Galanto Innovation

Inspired by Dr. Chandan Kumar Jha's guest lecture, we studied a real-world stroke rehab glove developed at IIT Gandhinagar. Their model uses **optical flex sensors** with **0.1° accuracy**, offering inspiration for future refinement.

---

## 📚 References

1. [CCPhysiotherapy - Robotic Gloves for Stroke Rehab](https://www.ccphysiotherapy.com/stroke/dont-miss-out-on-hand-therapy-robotic-gloves-revolutionary-tool-for-stroke-rehab/)
2. [Frontiers in Neurorobotics, 2023](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10295999/)
3. [Frontiers in Neurology, 2022](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9381330/)
4. [Neofect Blog - Games for Healthcare](https://www.neofect.com/us/blog/ways-to-use-games-for-healthcare)
5. [Arduino Forum - Peak Detection](https://forum.arduino.cc/t/how-to-detect-a-peak-and-low-in-noisy-data/690968)

---

## 🧰 Future Work

- ✅ Calibration protocols for stroke patients
- ✅ Full sensor fusion with real-time feedback
- ✅ Compact PCB integration
- ✅ Comparative studies with clinical methods
- ✅ Enhanced Unity visualizations and interaction models

---

*This project represents a promising step towards low-cost, accessible, and effective stroke rehabilitation technology.*
