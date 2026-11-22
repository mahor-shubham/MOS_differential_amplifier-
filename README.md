
# Analysis and Design of MOS Differential Amplifier
---

## 1. Project Overview

This project focuses on the design and performance analysis of a MOS Differential Amplifier using three different MOSFET channel lengths:

- 1 µm
- 800 nm (0.8 µm)
- 180 nm

The same basic circuit topology is investigated across different channel lengths to study the effects of transistor dimensions and operating conditions on amplifier performance.

The analysis focuses on voltage gain, -3 dB frequency, Input Common Mode Range (ICMR), and Slew Rate.

## 2. Project Objectives

- Design a MOS Differential Amplifier.
- Analyze circuit performance at 1 µm, 800 nm, and 180 nm channel lengths.
- Study voltage gain and frequency response.
- Determine the -3 dB frequency.
- Analyze Input Common Mode Range (ICMR).
- Measure Slew Rate.
- Compare amplifier performance across different channel lengths.

## 3. Design Specifications

The following design specifications are considered:

| Parameter | Target |
|---|---:|
| Voltage Gain (Av) | 40 dB |
| -3 dB Frequency | 200 kHz |
| Minimum ICMR | 1.5 V |
| Maximum ICMR | 4 V |
| Power Dissipation | 2 mW |
| Load Capacitance (CL) | 5 pF |
| Slew Rate (SR) | 10 V/µs |

Reference: https://www.researchgate.net/publication/308904430_Analysis_and_Design_of_MOS_Differential_Amplifier

## 4. Circuit Design and Simulation

The MOS Differential Amplifier is designed and simulated for three different channel lengths using LTspice.

# Circuit Diagram

<img width="350" height="450" alt="image" src="https://github.com/user-attachments/assets/b5733b82-3aa0-415a-a145-a398888d00a1" />


**Analysis Performed:**

- DC Operating Point Analysis
- Frequency Response Analysis
- Voltage Gain Measurement
- Input Common Mode Range (ICMR) Analysis
- Slew Rate Measurement
- Transient Response Analysis
- Comparative Performance Evaluation

## 5. Comparative Simulation Results

The following results were obtained and documented during the circuit analysis:

| Parameter | 1 µm | 800 nm | 180 nm |
|---|---:|---:|---:|
| Voltage Gain (Av) | 40.59 dB | 34.32 dB | 25.92 dB |
| -3 dB Frequency | 220.68 kHz | 435.41 kHz | 557.48 kHz |
| ICMR | 0.8–4.11 V | 0.708–4.02 V | 0.391–1.94 V |
| Slew Rate | 10.58 V/µs | 9.38 V/µs | 2.28 V/µs |
| W/L (M1, M2) | 30 | 30 | 60 |
| W/L (M3, M4) | 3 | 3 | 40 |
| W/L (M5) | 8 | 8 | 5 |
| W/L (M6) | 13 | 13 | 15 |
| W/L (M7) | 1 | 1 | 5 |
| Supply Voltage | 5 V | 5 V | 2 V |

## 6. Observations

Based on the simulation results:

- Voltage gain decreases from 40.59 dB at 1 µm to 25.92 dB at 180 nm.
- The -3 dB frequency increases from 220.68 kHz to 557.48 kHz as channel length decreases.
- The Input Common Mode Range varies across the three implementations.
- Slew rate decreases from 10.58 V/µs to 2.28 V/µs.
- The results highlight the trade-offs between voltage gain, bandwidth, input common mode range, and slew rate.

## 7. LTspice Circuit Files

The project includes the following LTspice circuit schematics and documentation:

| File | Description |
|---|---|
| `Analysis and Design of MOS Differential Amplifier 1um.asc` | Differential Amplifier with 1 µm channel length |
| `Analysis and Design of MOS Differential Amplifier 800nm.asc` | Differential Amplifier with 800 nm channel length |
| `Analysis and Design of MOS Differential Amplifier 180nm.asc` | Differential Amplifier with 180 nm channel length |
| `Project Report.pdf` | Detailed project documentation and simulation analysis |

## 8. Tools and Technologies

- **LTspice** – Circuit design and simulation.
- **MOSFET Technology** – 1 µm, 800 nm, and 180 nm.
- **Analog Circuit Design** – MOS Differential Amplifier.
- **Performance Analysis** – Voltage gain, bandwidth, ICMR, and slew rate.

## 9. Key Learning Outcomes

- Understanding MOS Differential Amplifier architecture.
- MOSFET sizing and channel length variation.
- DC operating point analysis.
- AC frequency response and voltage gain measurement.
- Input Common Mode Range analysis.
- Slew Rate measurement.
- Understanding technology scaling and analog circuit performance.
- Performing circuit simulations and waveform analysis using LTspice.

## 10. Conclusion

This project demonstrates the impact of MOSFET channel length variation on the performance of a MOS Differential Amplifier.

The comparative results show an increase in -3 dB frequency with reduced channel length, accompanied by changes in voltage gain, ICMR, and slew rate.

These observations highlight the important design trade-offs involved in analog CMOS circuit implementation across different technology dimensions.

---

**Technologies:** MOSFET | LTspice | Analog IC Design | Differential Amplifier | Circuit Simulation
