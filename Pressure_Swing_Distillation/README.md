# Pressure Swing Distillation – Ethanol–Water Separation

## Project Overview

This project demonstrates the **steady-state simulation of Pressure Swing Distillation (PSD)** for the separation of an **Ethanol–Water mixture** using **Aspen HYSYS**.

The process uses two distillation columns operating at different pressures:

- **Low-Pressure (LP) Column**
- **High-Pressure (HP) Column**

The columns are integrated with a **pump, pressure-reducing valve, and recycle stream** to achieve high-purity ethanol and water products.

This project focuses on applying practical **process simulation, distillation, material balance, recycle, and process-flow concepts** using Aspen HYSYS.

---

## Objectives

- Simulate an **Ethanol–Water Pressure Swing Distillation** process.
- Understand the effect of operating pressure on the separation process.
- Develop and analyze LP and HP distillation columns.
- Integrate pump, valve, and recycle operations.
- Evaluate product flow rates and compositions.
- Demonstrate practical application of **Aspen HYSYS steady-state simulation**.

---

## Process Description

The feed enters the **Low-Pressure (LP) Column**, where the initial separation of the Ethanol–Water mixture takes place.

The column produces a **water-rich bottom product** and a distillate stream that is sent through a **pump** to increase its pressure before entering the **High-Pressure (HP) Column**.

The HP Column further separates the mixture and produces a high-purity **ethanol product**. A portion of the HP-column overhead stream is pressure-reduced through a valve and returned to the LP section as a **recycle stream**.

### Simplified Process Flow

-
flowchart LR
    A[Feed<br/>Ethanol + Water<br/>65 °C | 221.3 kPa]
    B[LP Column<br/>Low Pressure<br/>111.3 kPa]
    C[Water Product<br/>99.31 mol% H₂O]
    D[Pump<br/>Pressure Increase]
    E[HP Column<br/>High Pressure<br/>2000 kPa]
    F[Ethanol Product<br/>99.00 mol% Ethanol]
    G[Pressure Reducing Valve]

    A --> B
    B --> C
    B --> D
    D --> E
    E --> F
    E --> G
    G --> B

--

##  Process Configuration

| Equipment / Stream | Description |
|---|---|
| Feed | Ethanol–Water feed to LP Column |
| LP Column | Low-pressure distillation section |
| Pump | Increases pressure between LP and HP sections |
| HP Column | High-pressure distillation section |
| VLV-100 | Pressure-reducing valve |
| RCY-1 | Recycle stream |
| Water Product | High-purity water-rich product |
| Ethanol Product | High-purity ethanol-rich product |

---

##  Simulation Conditions

| Parameter | Value |
|---|---:|
| **Simulation Software** | Aspen HYSYS |
| **Process** | Pressure Swing Distillation |
| **Feed Temperature** | ~65 °C |
| **Feed Pressure** | ~221.3 kPa |
| **LP Column Pressure** | ~111.3 kPa |
| **HP Column Pressure** | ~2000 kPa |
| **Water Product Temperature** | ~100.8 °C |
| **Ethanol Product Temperature** | ~179.7 °C |
| **Recycle Stream Pressure** | ~120 kPa |

> Values are taken from the Aspen HYSYS simulation flowsheet and may vary slightly depending on convergence settings, thermodynamic package, and simulation configuration.

---

## Simulation Results

###  Water Product

| Parameter | Result |
|---|---:|
| **Molar Flow** | 816.3 kmol/h |
| **Water Mole Fraction** | 0.9931 |
| **Water Purity** | ~99.31 mol% |

###  Ethanol Product

| Parameter | Result |
|---|---:|
| **Molar Flow** | 200.0 kmol/h |
| **Ethanol Mole Fraction** | 0.9900 |
| **Ethanol Purity** | ~99.00 mol% |

### Key Output

The steady-state simulation produced approximately:

- **99.31 mol% water** in the water-rich product.
- **99.00 mol% ethanol** in the ethanol-rich product.

These results demonstrate the separation performance of the simulated pressure-swing configuration.

---

##  Process Engineering Concepts Applied

This simulation demonstrates practical application of:

- Pressure Swing Distillation
- Distillation Column Simulation
- Vapor–Liquid Equilibrium (VLE)
- Material Balance
- Steady-State Process Simulation
- Column Pressure Selection
- Recycle Stream Integration
- Pump Operation
- Pressure Reduction
- Product Purity Analysis
- Process Flow Diagram Interpretation
- Process Stream Analysis

---

##  Aspen HYSYS Flowsheet

<img width="880" height="478" alt="image" src="https://github.com/user-attachments/assets/0f7b69a9-af10-44e7-82ad-c4735f57d9ae" />

---

---

##  Software & Tools

**Aspen HYSYS**

Used for:

- Steady-state process simulation
- Distillation column modelling
- Material balance analysis
- VLE-based separation
- Process stream analysis
- Recycle configuration
- Process flowsheet development

---

##  Key Learning Outcomes

Through this project, I developed practical understanding of:

1. **Pressure Swing Distillation** and its application to Ethanol–Water separation.
2. The influence of **column pressure** on distillation performance.
3. Integration of **LP and HP distillation columns**.
4. Recycle-loop configuration and steady-state convergence.
5. Material flow and product-composition analysis.
6. Practical process simulation using **Aspen HYSYS**.

---

##  Project Highlights

- ✔️ Two-column Pressure Swing Distillation configuration
- ✔️ LP and HP column integration
- ✔️ Pump and pressure-reduction operations
- ✔️ Recycle stream configuration
- ✔️ High-purity ethanol product
- ✔️ High-purity water product
- ✔️ Steady-state Aspen HYSYS simulation
- ✔️ Process engineering analysis

---

## 👩‍🔬 Author

**Himani Kinkar**

**Chemical Engineer | Process Simulation | Aspen HYSYS & Process Simulation**


