# Smart Air Conditioner

This project involves designing a Smart Air Conditioner (A/C) system using digital logic concepts. The main goal is to create a circuit that automates the A/C functionality based on motion detection, temperature sensing, and user control.

---

## Project Overview

### Features:
1. **Automatic Operation:** The system automatically turns the A/C on or off based on movement and temperature conditions.
2. **Energy Efficiency:** Helps maintain a normal room temperature while reducing electricity consumption.
3. **User Control:** The system can also be controlled manually via a remote control.

### Main Components:
- **Flip-Flops:** Used for data storage and sequential circuit design.
- **Sensors:** Motion and temperature sensors are integrated for environment detection.
- **Logic Gates:** Digital logic gates implement the core functionality of the circuit.

---

## Circuit Design Steps

### Input and Output:
- **Inputs:**
  - Motion Sensor (M)
  - Timer (Ti)
  - Remote Control (C)
  - Temperature Sensor (T)

- **Outputs:**
  - Power Button (D)
  - A/C On (Q)
  - A/C Off (Q')

### Functional Logic:
1. When the remote control is on, and either the motion sensor or timer is activated, the power button turns on.
2. If the power button is on:
   - The A/C turns on when the temperature is high.
   - The A/C turns off when the temperature is low.
3. If the power button is off, the A/C remains off regardless of the temperature.

### Boolean Functions:
- **D:** `D = Ti*C + M*C`
- **Q:** `Q = Ti*C*T + M*C*T`
- **Q':** `Q' = M'*Ti' + C' + T'`

### Circuit Layout:
The circuit consists of digital components such as flip-flops and logic gates, simulated using the Cedar Logic Simulator.

---

## Report Details

- **Document Name:** Final Project Report - Smart Air Conditioner
- **File Type:** PDF
- **Content:**
  - Introduction to digital circuits.
  - Comparison of analog and digital circuits.
  - Explanation of combinational and sequential circuits.
  - Detailed description of the smart air conditioner design and cases.
  - Circuit diagrams and Boolean functions.

---

## Figures and Tables:
- Figures include circuit layouts for different cases of the smart A/C.
- Truth tables, state diagrams, and K-maps are provided to explain the logic design.

---

## Resources
- The detailed report is available in PDF format for in-depth understanding.

**[Download Full Report](Final_Project_Report_Smart_AC.pdf)**

---

## Bibliography
1. Converting State Diagrams to Logic Circuits. Retrieved from [ETSU.edu](https://faculty.etsu.edu/tarnoff/ntes2150/statemac/statemac.htm)
2. D Type Flip-Flop: Circuit, Truth Table, and Working. Retrieved from [Circuit Digest](https://circuitdigest.com/electronic-circuits/d-flip-flops)
3. Differences between Analog Circuits and Digital Circuits. Retrieved from [Electronics Hub](https://www.electronicshub.org/analog-circuits-and-digital-circuits/)
4. Digital Circuit: Design, Types, Advantages, Disadvantages & Applications. Retrieved from [WatElectronics.com](https://www.watelectronics.com/what-is-a-digital-circuit-design-types-its-applications/)
5. D-type Flip Flop Counter or Delay Flip-flop. Retrieved from [Basic Electronics Tutorials](https://www.electronics-tutorials.ws/sequential/seq_4.html)

