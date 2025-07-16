# ⏰ Digital Clock Project

This is a **Digital Clock** developed as a semester project for the **Digital Logic Design (DLD)** course. The clock displays real-time in **HH:MM:SS** format using digital ICs, designed and simulated in **Proteus 8**.

---

## 📌 Features

- Displays Hours, Minutes, and Seconds (24-hour format)
- Simulated in Proteus
- Fully IC-based — no microcontrollers used

---

## 🔧 Tools & Technologies

- 🧪 **Proteus Design Suite** – for simulation and testing
- ⚙️ **Logic ICs and Logic Gates**
- 🧰 **Breadboard** and jumper wires
- 🔋 **5V DC Power Supply**

---

## 🔌 If you want to Develop Hardware Then These Components Would be Used

| Component           | Quantity | Description                              |
|--------------------|----------|------------------------------------------|
| 7490 Decade Counter| 6        | For time counting (HH, MM, SS)           |
| 7447 BCD to 7-segment decoder | 6 | To drive 7-segment displays              |
| 7-Segment Display  | 6        | For showing digits (HH:MM:SS)            |
| 555 Timer IC       | 1        | To generate 1Hz pulse                    |
| Breadboard         | 1        | For prototyping the circuit              |
| Resistors & Capacitors | Various | For timing and protection               |

---

## ⚙️ Working Principle

1. **Time Pulse**:
   - A 555 Timer is used in astable mode to produce a stable 1Hz pulse.

2. **Counting Mechanism**:
   - Each segment (HH, MM, SS) is made using 7490 counters.
   - Reset logic is added to reset seconds at 60, minutes at 60, and hours at 24.

3. **Display Output**:
   - The binary count is passed to 7447 BCD decoders to drive the 7-segment displays.

---

## 🖼️ Screenshots

> Include simulation screenshots from Proteus and photos of the working hardware if available.

---

## 🧪 How to Simulate in Proteus

1. Open the `Digital_Clock.pdsprj` file in Proteus.
2. Click on the “Play” button to run the simulation.
3. Observe the time progression on 7-segment displays.
4. Use the reset button (if implemented) to reinitialize.


