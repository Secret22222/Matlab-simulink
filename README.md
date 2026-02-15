# ⚡ Half-Wave Rectifier Simulation using MATLAB Simulink

## 📌 Project Overview
This repository contains MATLAB Simulink models of half-wave rectifiers with different load configurations.  
The project focuses on analyzing the performance of controlled and uncontrolled rectifiers under R and RL load conditions.

The simulations help in understanding:
- Output voltage and current waveforms
- Effect of firing angle (α) in controlled rectifiers
- Behavior of inductive loads
- Role of freewheeling diode in RL circuits

---

## 🛠 Tools & Software Used
- MATLAB
- Simulink
- Simscape Electrical (if used)
- Power Electronics concepts

---

## 📂 Models Included

### 🔹 Uncontrolled Rectifiers
- Half-wave rectifier with R load
- Half-wave rectifier with RL load

### 🔹 Controlled Rectifiers (SCR Based)
- Half-wave controlled rectifier with R load
- Half-wave controlled rectifier with RL load
- Half-wave controlled rectifier with RL load + Freewheeling diode

---

## ⚙️ Key Concepts Implemented
- Phase angle control using SCR
- Firing angle variation (α control)
- Continuous and discontinuous conduction
- Inductive load current behavior
- Freewheeling diode operation
- Average output voltage analysis

---

## 📊 Observations
- For R load: Current follows voltage waveform.
- For RL load: Current continues even after voltage crosses zero.
- Freewheeling diode improves current continuity and reduces voltage spikes.
- Increasing firing angle reduces average output voltage.

---

## 🎯 Applications
- AC to DC converters
- Controlled power supplies
- Motor speed control basics
- Industrial rectifier systems

---

## 🚀 Learning Outcome
This project strengthened my understanding of:
- Power electronics converter design
- SCR-based phase control
- Simulation-based analysis
- Practical waveform interpretation

---
## 📘 Theoretical Background

Average Output Voltage (Uncontrolled Half-Wave Rectifier):

Vavg = Vm / π

Average Output Voltage (Controlled Half-Wave Rectifier):

Vavg = (Vm / 2π) * (1 + cos α)

Where:
Vm = Peak Input Voltage  
α = Firing Angle  

## 👨‍💻 Author
[Beauti Satyam]  
Electrical / Electronics Engineering Student  
