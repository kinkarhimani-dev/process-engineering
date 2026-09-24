# Shell & Tube Heat Exchanger Design – Aspen EDR

## Project Overview

This project demonstrates the **thermal and hydraulic design of a Shell & Tube Heat Exchanger using Aspen Exchanger Design & Rating (EDR)**.

The exchanger is designed to cool **benzene using cooling water**. The design considers the specified process conditions, fouling resistance, allowable pressure drop, thermal performance, and required heat-transfer area.

The detailed **Aspen EDR simulation/design file** is included in this repository for reference.

---

## Design Objective

Design a Shell & Tube Heat Exchanger to cool:

**40,000 kg/h of benzene from 100°C to 65°C**

using cooling water:

**30°C → 35°C**

The design objective is to determine the required heat-transfer area while considering thermal performance, fouling resistance, and allowable pressure drop.

---

## Design Basis

| Parameter | Benzene Side | Cooling Water Side |
|---|---:|---:|
| Fluid | Benzene | Cooling Water |
| Flow Rate | 40,000 kg/h | Calculated |
| Inlet Temperature | 100°C | 30°C |
| Outlet Temperature | 65°C | 35°C |
| Inlet Pressure | 5.5 bar | 5 bar |
| Allowable Pressure Drop | 1 bar | 1 bar |
| Fouling Factor | 0.0002 m²·K/W | 0.0001 m²·K/W |

---

## Design Methodology

The exchanger was designed and rated using **Aspen EDR**.

The design involved:

1. Defining the benzene and cooling-water streams.
2. Specifying the operating temperatures, pressures, and flow conditions.
3. Determining the required heat-transfer duty.
4. Calculating the required cooling-water flow rate.
5. Performing thermal design of the Shell & Tube Exchanger.
6. Incorporating fouling resistance on both sides.
7. Evaluating shell-side and tube-side pressure drops.
8. Determining the required heat-transfer area.
9. Reviewing the final thermal and hydraulic design results.

---

## Process Description

### Hot Side — Benzene

Benzene is the process fluid being cooled.

- **Flow Rate:** 40,000 kg/h
- **Inlet Temperature:** 100°C
- **Outlet Temperature:** 65°C
- **Inlet Pressure:** 5.5 bar

### Cold Side — Cooling Water

Cooling water is used as the cooling medium.

- **Flow Rate:** Calculated
- **Inlet Temperature:** 30°C
- **Outlet Temperature:** 35°C
- **Inlet Pressure:** 5 bar

The heat released by the benzene is transferred to the cooling-water stream through the heat-transfer surface.

---

## Fouling Consideration

Fouling resistance was included on both sides of the exchanger:

| Side | Fouling Factor |
|---|---:|
| Benzene Side | 0.0002 m²·K/W |
| Cooling Water Side | 0.0001 m²·K/W |

The fouling factors were incorporated into the design to account for the expected reduction in heat-transfer performance during operation.

---

## Calculated Results

The following values were obtained from the design:

| Parameter | Calculated Value |
|---|---:|
| Heat-Transfer Duty | **596,740 kcal/h** |
| Cooling-Water Flow Rate | **120,117 kg/h** |
| Required Heat-Transfer Area | **12.1 m²** |

### Heat-Transfer Duty

**596,740 kcal/h**

This represents the heat that must be removed from the benzene stream to achieve the specified outlet temperature.

### Cooling-Water Flow Rate

**120,117 kg/h**

This is the calculated cooling-water requirement for the specified temperature rise from **30°C to 35°C**.

### Required Heat-Transfer Area

**12.1 m²**

This is the calculated heat-transfer surface required for the specified exchanger duty.

---

## Equipment Summary

| Specification | Value |
|---|---:|
| Equipment | Shell & Tube Heat Exchanger |
| Design Software | **Aspen EDR** |
| Service | Benzene Cooling |
| Cooling Medium | Cooling Water |
| Benzene Flow Rate | 40,000 kg/h |
| Cooling-Water Flow Rate | **120,117 kg/h** |
| Benzene Temperature | 100°C → 65°C |
| Cooling-Water Temperature | 30°C → 35°C |
| Benzene Inlet Pressure | 5.5 bar |
| Water Inlet Pressure | 5 bar |
| Allowable Pressure Drop | 1 bar |
| Heat-Transfer Duty | **596,740 kcal/h** |
| Required Heat-Transfer Area | **12.1 m²** |

---

## 🔍 Design Highlights

- Shell & Tube heat exchanger thermal design
- Aspen EDR-based exchanger rating
- Benzene cooling service
- Cooling-water flow calculation
- Heat-transfer area determination
- Fouling resistance consideration
- Shell-side and tube-side pressure-drop evaluation
- Thermal and hydraulic performance assessment

---

## Software & Tools

**Primary Software**

- Aspen Exchanger Design & Rating (EDR)

**Engineering Applications**

- Heat Exchanger Thermal Design
- Process Equipment Design
- Heat Duty Calculation
- Hydraulic / Pressure-Drop Evaluation

> **Note:** Aspen EDR is required to open and interact with the detailed simulation/design file. The key design basis and calculated results are provided in this README for reference.

---

**Himani Kinkar**

Chemical Engineer | Process Simulation & Process Design

---

## Disclaimer

This project is intended for **educational and portfolio purposes only**. The Aspen EDR simulation and reported results are based on the specified problem statement, input data, and design assumptions.

The simulation should not be used directly for actual plant design, equipment procurement, or operational decisions without appropriate engineering review, validation, and verification.

---

**Process Engineering | Aspen EDR | Heat Exchanger Design | Thermal Design | Process Equipment Design**

