# 🚦 Traffic Light Using Logic ICs

A **digital logic–based traffic light controller** implemented using **combinational and sequential logic ICs** — without using any microcontroller or programmable device.

This project demonstrates how real-world traffic systems can be built purely with hardware logic design concepts such as counters, timers, and logic gates.

---

## 📌 Project Overview

The system simulates a real traffic signal with timed light transitions using logic ICs. The design focuses on understanding:

- Sequential logic behavior
- Timing generation using hardware
- State transitions
- Digital system design principles

---

## ⏱ Traffic Light Timing Cycle

| Light | Duration |
|------|----------|
| 🟢 Green | 30 seconds |
| 🟡 Yellow | 2 seconds |
| 🔴 Red | 30 seconds |

The cycle repeats automatically in a continuous loop.

---

## 🧩 Hardware Components

Typical components used in the design include:

- Logic Gates (AND / OR / NOT)
- Counters (e.g., 4017 or similar)
- Timer IC (555 Timer or equivalent clock source)
- LEDs (Red, Yellow, Green)
- Resistors
- Breadboard & Power Supply

> Exact IC numbers may vary depending on implementation.

---

## ⚙️ Working Principle

1. A clock signal is generated using a timer circuit.
2. The clock feeds a counter IC that changes states sequentially.
3. Each counter state activates a specific LED through logic gating.
4. Logic combinations control when each light turns ON or OFF.
5. After completing all states, the system resets and repeats.

This mimics the finite state machine (FSM) behavior used in real traffic controllers.

---

## 🧠 Design Concepts Used

- Sequential Logic
- Clock Signals
- State Machines (FSM Concept)
- Digital Timing Control
- Hardware-Based Automation

---

## 📷 Circuit Diagram

*(Add circuit image or schematic here)*

```
/images/circuit-diagram.png
```

---

## 🎯 Learning Outcomes

After completing this project, you should understand:

- How timing can be implemented without programming
- Practical use of logic ICs
- Hardware implementation of sequential systems
- Real-world digital electronics applications

---

## 🚀 Possible Improvements

- Add pedestrian crossing button
- Adjustable timing using potentiometer
- Dual-road intersection control
- PCB implementation instead of breadboard
- Simulation using Proteus or Multisim

---

## 👨‍💻 Author

**Youssef Elzainy**  
Communications Engineering Student – MSA University

---

⭐ If you found this project useful, consider starring the repository!
