# 🔬 Two-Stage Amplifier Design (BJT & MOSFET) – LTspice

## 📌 Project Overview

This project presents the design and analysis of **two-stage amplifier circuits** using both **BJT and MOSFET transistors**.

The circuits are analyzed:

* Theoretically (hand calculations)
* Through LTspice simulations

The goal is to compare amplifier performance in terms of:

* Voltage Gain
* Input Resistance
* Output Resistance
* Frequency Response

---

## ⚙️ Circuit Designs

### 🔹 BJT Two-Stage Amplifier

* Transistors: BC847B
* Supply Voltage: 15V
* Gain: **~2981**
* Input Resistance: **2.19 kΩ**
* Output Resistance: **6 kΩ**

### 🔹 MOSFET Two-Stage Amplifier

* Transistors: NMOS
* Supply Voltage: 12V
* Gain: **~28.1**
* Input Resistance: **6 kΩ**
* Output Resistance: **3 kΩ**

---

## 📊 Simulation Results

### 📈 Voltage Gain (BJT)

![Gain](images/gain_bjt.png)

### 📈 Input Resistance

![Input](images/input_impedance.png)

### 📈 Output Resistance

![Output](images/output_impedance.png)

---

## ⚡ Key Observations

### 🔥 BJT Amplifier

* Very high voltage gain
* Lower input impedance
* Suitable for high-gain applications

### ⚡ MOSFET Amplifier

* Lower gain
* High input impedance
* Better for signal integrity

---

## 🔍 Comparison Summary

| Feature           | BJT     | MOSFET  |
| ----------------- | ------- | ------- |
| Gain              | ~2981   | ~28.1   |
| Input Resistance  | 2.19 kΩ | 6 kΩ    |
| Output Resistance | 6 kΩ    | 3 kΩ    |
| Control Type      | Current | Voltage |

---

## 🧪 DC Operating Points

Simulation confirms theoretical results:

* BJT collector voltage ≈ 10.33V
* MOSFET drain currents ≈ 0.44mA – 0.55mA

---

## 🛠️ Tools Used

* LTspice
* Analog Circuit Analysis

---

## 📎 Report

Full report available in:

📄 `report/ED-1_Odev2.pdf`

---

## 👨‍💻 Author

**Murat Emre Demirci**
