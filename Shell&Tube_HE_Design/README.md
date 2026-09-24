# Shell & Tube Heat Exchanger Design – Aspen EDR

## Project Overview

This project demonstrates the **thermal and hydraulic design of a Shell & Tube Heat Exchanger using Aspen Exchanger Design & Rating (EDR)**.

The exchanger is designed to cool **benzene using cooling water**, considering the specified operating conditions, fouling resistance, and allowable pressure drop.

---

## Design Objective

Design a Shell & Tube Heat Exchanger to cool **40,000 kg/h of benzene** from **100°C to 65°C** using cooling water entering at **30°C** and leaving at **35°C**.

The design considers:

* Heat-transfer duty
* Cooling-water requirement
* Heat-transfer area
* Fouling resistance
* Pressure-drop limitations
* Thermal and hydraulic performance

---

## Design Basis

| Parameter               |    Benzene Side | Cooling Water Side |
| ----------------------- | --------------: | -----------------: |
| Fluid                   |         Benzene |      Cooling Water |
| Flow Rate               | **40,000 kg/h** |     **Calculated** |
| Inlet Temperature       |           100°C |               30°C |
| Outlet Temperature      |            65°C |               35°C |
| Inlet Pressure          |         5.5 bar |              5 bar |
| Allowable Pressure Drop |           1 bar |              1 bar |
| Fouling Factor          |   0.0002 m²·K/W |      0.0001 m²·K/W |

---

## Design Approach

The heat exchanger was designed and rated using **Aspen EDR**.

The design workflow included:

1. Defining process streams and operating conditions.
2. Specifying benzene and cooling-water properties.
3. Determining the heat-transfer duty.
4. Calculating the required cooling-water flow rate.
5. Performing thermal design of the exchanger.
6. Accounting for fouling resistance on both sides.
7. Evaluating pressure drop on the shell and tube sides.
8. Determining the required heat-transfer area.
9. Reviewing the final EDR design and rating results.

---

## Process Service

### Hot Side — Benzene

* **Flow Rate:** 40,000 kg/h
* **Inlet Temperature:** 100°C
* **Outlet Temperature:** 65°C
* **Inlet Pressure:** 5.5 bar

### Cold Side — Cooling Water

* **Flow Rate:** Calculated
* **Inlet Temperature:** 30°C
* **Outlet Temperature:** 35°C
* **Inlet Pressure:** 5 bar

---

## Fouling Consideration

Fouling resistance was included on both sides of the exchanger:

| Side         | Fouling Factor |
| ------------ | -------------: |
| Benzene Side |  0.0002 m²·K/W |
| Water Side   |  0.0001 m²·K/W |

These values were considered during the EDR design to account for the reduction in heat-transfer performance due to fouling.

---

## Design Results

The following results were obtained from the design:

| Parameter                   |   Calculated Value |
| --------------------------- | -----------------: |
| Heat-Transfer Duty          | **596,740 kcal/h** |
| Cooling-Water Flow Rate     |   **120,117 kg/h** |
| Required Heat-Transfer Area |        **12.1 m²** |

---

## Equipment Summary

| Specification             |                       Value |
| ------------------------- | --------------------------: |
| Equipment Type            | Shell & Tube Heat Exchanger |
| Design Software           |               **Aspen EDR** |
| Service                   |             Benzene Cooling |
| Cooling Medium            |               Cooling Water |
| Benzene Flow Rate         |                 40,000 kg/h |
| Cooling-Water Flow Rate   |            **120,117 kg/h** |
| Benzene Temperature       |                100°C → 65°C |
| Cooling-Water Temperature |                 30°C → 35°C |
| Benzene Inlet Pressure    |                     5.5 bar |
| Water Inlet Pressure      |                       5 bar |
| Allowable Pressure Drop   |                       1 bar |
| Heat-Transfer Duty        |          **596,740 kcal/h** |
| Heat-Transfer Area        |                 **12.1 m²** |

---

## Key Engineering Skills

* Aspen EDR
* Shell & Tube Heat Exchanger Design
* Heat Exchanger Rating
* Thermal Design
* Hydraulic / Pressure-Drop Evaluation
* Heat Duty Calculation
* Fouling Analysis
* Cooling-Water Requirement
* Process Equipment Design

---

## Conclusion

A **Shell & Tube Heat Exchanger** was designed using **Aspen EDR** for cooling **40,000 kg/h of benzene from 100°C to 65°C** using cooling water from **30°C to 35°C**.

### Final Design Results

* **Heat-Transfer Duty:** 596,740 kcal/h
* **Cooling-Water Flow Rate:** 120,117 kg/h
* **Required Heat-Transfer Area:** **12.1 m²**

---

## Author

**Himani Kinkar**
Chemical Engineer | Process Simulation & Process Design

---

## Disclaimer

This project is intended for **educational and portfolio purposes only**. The Aspen EDR simulation and reported results are based on the specified problem statement, input data, and design assumptions.

The simulation should not be used directly for actual plant design, equipment procurement, or operational decisions without appropriate engineering review, validation, and verification.

---

**Process Engineering | Aspen EDR | Heat Exchanger Design | Thermal Design | Process Equipment Design**

