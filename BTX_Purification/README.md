# BTX Purification Unit -- Aspen HYSYS Simulation

## Project Overview

This project presents the simulation and design of a **BTX
(Benzene--Toluene--Xylene) purification unit** using **Aspen HYSYS**.

The process uses a **two-column distillation sequence** to separate
benzene and toluene from a BTX feed and achieve high-purity products.

------------------------------------------------------------------------

## Problem Statement

Design a **BTX purification unit** to separate a mixed feed containing:

  Component     Feed Composition
  ----------- ------------------
  Benzene                 40 wt%
  Toluene                 35 wt%
  o-Xylene                25 wt%

### Feed Conditions

-   **Flow Rate:** 1000 lbmol/h
-   **Temperature:** 211 °F
-   **Pressure:** 1 atm

### Design Objective

Achieve **benzene and toluene product purities greater than 99.50 mol%**
by determining suitable:

-   Number of theoretical stages
-   Feed stage location
-   Reflux ratio
-   Column operating conditions

------------------------------------------------------------------------

## Process Configuration

The purification system consists of **two distillation columns**.

### Column 1 -- Benzene Purification (DC1)

The first column separates benzene as the primary overhead product while
concentrating the heavier components in the bottom stream.

-   **Number of theoretical trays:** 28
-   **Reflux ratio:** 7.75
-   **Operating pressure:** \~100 psia

### Column 2 -- Toluene Purification (DC2)

The intermediate stream from DC1 is processed in the second column to
obtain high-purity toluene as the overhead product, with o-xylene
concentrated in the bottoms.

-   **Number of theoretical trays:** 22
-   **Reflux ratio:** 9.35
-   **Operating pressure:** \~103 psia

------------------------------------------------------------------------

## Simulation Results

### Benzene Product -- T1

  Component     Mole Fraction
  ----------- ---------------
  Benzene          **0.9990**
  Toluene              0.0010

**Benzene purity: 99.90 mol%**

### Toluene Product -- T2

  Component     Mole Fraction
  ----------- ---------------
  Toluene          **0.9973**
  o-Xylene             0.0010

**Toluene purity: 99.73 mol%**

Both target products meet the required **\>99.50 mol% purity**
specification.

------------------------------------------------------------------------

## Simplified Process Flow

``` text
                    BTX Feed
              1000 lbmol/h | 211°F
                       |
                       v
              +------------------+
              |       DC1        |
              | Benzene Column   |
              | 28 Trays         |
              | RR = 7.75        |
              +--------+---------+
                       |
              Intermediate Stream
                       |
                       v
              +------------------+
              |       DC2        |
              | Toluene Column   |
              | 22 Trays         |
              | RR = 9.35        |
              +--------+---------+
                       |
              +--------+---------+
              |                  |
              v                  v
       Toluene Product     o-Xylene Rich
        99.73 mol%           Bottoms

       Benzene Product
        99.90 mol%
        from DC1 overhead
```

------------------------------------------------------------------------

## Aspen HYSYS Flowsheet
<img width="952" height="532" alt="image" src="https://github.com/user-attachments/assets/366081b8-3936-4ef8-913e-72bf8ea3e746" />


------------------------------------------------------------------------

## Software & Tools

-   Aspen HYSYS
-   Multicomponent Distillation
-   Distillation Column Simulation
-   Material & Energy Balance
-   Theoretical Stage Analysis
-   Reflux Ratio Analysis
-   Process Flow Diagram Development

------------------------------------------------------------------------

## Key Engineering Concepts

-   BTX separation
-   Multicomponent distillation
-   Benzene--Toluene--Xylene separation
-   Theoretical stages
-   Reflux ratio
-   Product purity specification
-   Material balance
-   Distillation column operation
-   Process simulation

------------------------------------------------------------------------

## Key Outcomes

-   Developed a **two-column BTX purification process** in Aspen HYSYS.
-   Achieved **99.90 mol% benzene purity**.
-   Achieved **99.73 mol% toluene purity**.
-   Evaluated theoretical stages and reflux ratios for both columns.
-   Demonstrated multicomponent distillation for BTX purification.

------------------------------------------------------------------------

## Author

**Himani Kinkar**

Chemical Engineer \| Process Simulation\
Aspen HYSYS \| Process Design \| Distillation
