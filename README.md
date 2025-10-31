# ⚡ Footstep Power Generation using Piezoelectric Tiles

This project involves the **design and analysis of a piezoelectric-based energy harvesting floor tile** that converts mechanical energy from human footsteps into electrical power.  
The system integrates **12 piezoelectric discs** on a 33×33 cm platform with a **rectification and storage circuit**, providing measurable, storable electrical energy suitable for low-power applications.

> _Guided by Prof. Arpan Gupta (IIT Delhi) — Aug 2025–Ongoing_

---

## 🎯 Objectives
- Develop a **piezoelectric floor prototype** for kinetic-to-electric energy conversion.
- Design a **rectification and energy storage circuit**.
- Interface with **Arduino Uno** for real-time voltage and step-count monitoring.
- Analyze the feasibility for **self-sustaining smart floor applications**.

---

## 🧰 Components & Tools
| Component | Specification | Function |
|------------|---------------|-----------|
| Piezo Discs | 12 × 27 mm, PZT type | Energy transducers |
| Bridge Rectifier | 1N4007 diodes | AC–DC conversion |
| Capacitor | 4700 µF, 25V | Energy storage |
| Load | 1 W LED | Output demonstration |
| Arduino Uno | ATmega328P | Data acquisition |
| LCD / Serial Monitor | — | Real-time display |

---

## ⚙️ Working Principle

1. **Mechanical Pressure** → Step on tile compresses piezo discs.  
2. **Electric Output** → Generates alternating voltage (≈18–22 V open circuit).  
3. **Rectification & Storage** → Bridge rectifier + capacitor stores ~0.25 J/step.  
4. **Output Usage** → Powers a 1 W LED for ~2–3 seconds after 10 steps.  
5. **Data Logging** → Arduino measures voltage, current, and step count.

---

## 📊 Performance Metrics

| Parameter | Measured Value | Condition |
|------------|----------------|------------|
| Voltage (Voc) | 18–22 V | Single step |
| Current (Isc) | ≈18 mA | Step impact |
| Energy/step | 0.25 J | At 10 kg load impulse |
| LED Operation | 2–3 s | After 10 steps |

---

## 🧩 Circuit Diagram
![Circuit Diagram](Results/piezo_circuit.png)

## 💡 Experimental Setup
![Setup Image](Results/piezo_tile_setup.png)

---

## 🧠 Learning Outcomes
- Understood **piezoelectric transduction** and **charge accumulation**.
- Designed **rectification and storage circuits** for kinetic energy harvesting.
- Integrated **Arduino data logging** for real-time system monitoring.
- Evaluated **feasibility of renewable micro-energy generation** in smart infrastructure.

---

## 🧭 Future Work
- Integrate **supercapacitor or Li-ion storage** for longer operation.
- Implement **parallel-series hybrid disc arrangements** for higher yield.
- Explore **IoT-based monitoring** for large-scale campus deployment.

---


## 📄 Project Report

You can access the complete project documentation here:  
[📘 **Footstep Power Generation using Piezoelectric – Report**](Footstep_Power_Generation_Using_Piezoelectric.docx)

---

## 👨‍💻 Author
**Shubham Kurre**  
Mechanical Engineering | Energy Harvesting | Embedded Systems | Arduino  
[LinkedIn](https://linkedin.com/in/) • [GitHub](https://github.com/shubhamkurre)

---

## 📂 Repository Structure
