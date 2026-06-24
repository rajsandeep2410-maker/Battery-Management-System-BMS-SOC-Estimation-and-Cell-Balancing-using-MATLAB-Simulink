# Battery Management System (BMS) – SOC Estimation and Cell Balancing using MATLAB/Simulink

## Overview

This project presents a Battery Management System (BMS) model developed in MATLAB/Simulink for a multi-cell Lithium-Ion battery pack. The model demonstrates State of Charge (SOC) estimation and cell balancing techniques to improve battery pack performance, safety, and lifespan.

The objective is to monitor individual cell voltages, identify imbalance conditions, and perform balancing to equalize the SOC of all cells in the battery pack.

---

## Features

* Multi-cell Lithium-Ion battery pack simulation
* State of Charge (SOC) estimation
* Cell voltage monitoring
* Passive cell balancing implementation
* Charge and discharge cycle simulation
* Cell imbalance detection
* Performance visualization through plots
* Battery pack behavior analysis

---

## System Architecture

```text
Battery Pack
      │
      ▼
Voltage & Current Measurement
      │
      ▼
SOC Estimation Block
      │
      ▼
Balancing Controller
      │
      ▼
Passive Balancing Circuit
      │
      ▼
Balanced Battery Pack
```

---

## Working Principle

1. Each battery cell is monitored individually.
2. The SOC of each cell is estimated using battery parameters.
3. The controller continuously compares cell voltages and SOC values.
4. Cells with higher voltage/SOC are identified.
5. Passive balancing resistors are activated to discharge higher-energy cells.
6. The balancing process continues until all cells reach similar SOC levels.

---

## Simulation Parameters

| Parameter           | Value             |
| ------------------- | ----------------- |
| Battery Type        | Lithium-Ion       |
| Number of Cells     | 10                |
| Nominal Voltage     | 3.7 V             |
| Maximum Voltage     | 4.2 V             |
| Balancing Method    | Passive Balancing |
| Simulation Platform | MATLAB/Simulink   |

---

## Results

The following results are obtained from simulation:

### SOC Convergence

* Initial SOC imbalance among cells
* Gradual equalization of SOC values
* Stable balanced condition

### Cell Voltage Analysis

* Voltage difference reduction during balancing
* Uniform voltage distribution after balancing

### Balancing Performance

* Controlled discharge of higher-voltage cells
* Improved battery pack uniformity

---

## Key Concepts Implemented

* Battery Management System (BMS)
* State of Charge (SOC) Estimation
* Cell Balancing
* Lithium-Ion Battery Modeling
* Voltage Monitoring
* Battery Safety Concepts
* Energy Management

---

## Tools Used

* MATLAB
* Simulink
* Simscape Electrical

---

## Future Improvements

* Active Cell Balancing
* State of Health (SOH) Estimation
* Extended Kalman Filter (EKF) SOC Estimation
* Temperature Monitoring
* CAN Communication Integration
* Fault Detection and Diagnostics
* Real-Time Hardware Implementation

---

## Applications

* Electric Vehicles (EVs)
* Energy Storage Systems (ESS)
* Battery Research and Development
* Electric Construction Equipment
* Industrial Battery Packs

---

## Repository Structure

```text
├── Simulink_Model
│   └── BMS_Cell_Balancing.slx

├── Results
│   ├── SOC_vs_Time.png
│   ├── Cell_Voltage.png
│   └── Balancing_Performance.png

├── Documentation
│   ├── Architecture.png
│   ├── Flowchart.png
│   └── Report.pdf

└── README.md
```

---

## Author

**Sandeep Raj**
B.Tech Electronics & Communication Engineering
R&D Electrical Intern – Escorts Kubota Limited

---

### Note

This project is developed for educational and research purposes to understand Battery Management Systems, SOC estimation techniques, and cell balancing strategies used in modern electric vehicle battery packs.
