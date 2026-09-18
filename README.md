Gas Sweetening Process Using MDEA Solvent

Aspen HYSYS | Natural Gas Processing | Gas Sweetening | MDEA | Process Simulation

Overview:

This project demonstrates the steady-state simulation of a natural gas sweetening process using MDEA (Methyldiethanolamine) solvent in Aspen HYSYS.
The process is designed to remove acidic gases, primarily Hydrogen Sulfide (H₂S) and Carbon Dioxide (CO₂), from sour natural gas using an amine absorption and regeneration process.

Objectives:

Develop a gas sweetening flowsheet using Aspen HYSYS.
Model H₂S and CO₂ removal using MDEA solvent.
Simulate rich amine regeneration and lean amine recycle.
Analyse material and energy balances.
Evaluate key process streams and operating conditions.

Process Description:

The process consists of two main sections:
1. Gas Absorption
Sour natural gas enters the MDEA absorber, where it contacts lean MDEA solvent.
The acidic components, primarily H₂S and CO₂, are absorbed into the liquid MDEA phase.

Outputs:
Sweet gas
Rich MDEA

2. MDEA Regeneration
The rich MDEA stream is routed to the regeneration section. Heat supplied through the reboiler releases the absorbed acid gases from the solvent.
The regenerated lean MDEA is cooled and recycled back to the absorber.

Overall Process:
Sour Gas
    │
    ▼
┌──────────────┐
│ MDEA Absorber│
└──────┬───────┘
       │
       ├──────────────► Sweet Gas
       │
       ▼
   Rich MDEA
       │
       ▼
┌─────────────────┐
│ Heat Exchanger  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ MDEA Regenerator│
└───────┬─────────┘
        │
        ├────────────► Acid Gas
        │
        ▼
    Lean MDEA
        │
        ▼
   Cooler / HX
        │
        └────────────► Recycle to Absorber

        
Simulation Details:

Parameter	       Details
Simulator	       Aspen HYSYS
Simulation Type	 Steady-State
Process	         Natural Gas Sweetening
Solvent	         MDEA
Main Acid Gases	 H₂S, CO₂
Process Type	   Gas-Liquid Absorption & Regeneration
Application	     Oil & Gas / Natural Gas Processing

Major Process Equipment:

The simulation includes modelling of key process units such as:
MDEA Absorber
MDEA Regenerator
Reboiler
Condenser
Lean/Rich Amine Heat Exchanger
Lean Amine Cooler
Process Streams
Recycle Loop

Engineering Activities:

Developed the gas sweetening process flowsheet in Aspen HYSYS.
Configured sour gas and MDEA solvent streams.
Modelled acid-gas absorption in the absorber.
Modelled MDEA regeneration in the regenerator.
Analysed lean and rich MDEA stream conditions.
Performed material and energy balance analysis.
Reviewed H₂S and CO₂ concentrations before and after treatment.
Analysed temperature, pressure and flow conditions of key process streams.
Established the lean-MDEA recycle loop.

Simulation Results

The Aspen HYSYS model provides results for:
Sour gas and sweet gas composition
H₂S and CO₂ removal
Lean and rich MDEA conditions
Gas and solvent flow rates
Stream temperature and pressure
Reboiler duty
Condenser duty
Heat exchanger performance

Detailed process results are available within the attached Aspen HYSYS simulation model.

Tools & Skills:

Software:
Aspen HYSYS

Process Engineering:

Natural Gas Processing
Gas Sweetening
MDEA Amine Treating
Absorption & Regeneration
Material & Energy Balances
Process Simulation
Process Flowsheet Development
Process Stream Analysis
Process Troubleshooting

Aspen HYSYS Flowsheet:

<img width="1416" height="683" alt="image" src="https://github.com/user-attachments/assets/17683312-5766-4384-bf99-8960145c0701" />


Key Learning Outcomes:

This project provided practical exposure to:
Aspen HYSYS steady-state process simulation
MDEA-based gas sweetening
Acid-gas absorption and amine regeneration
Natural gas process flowsheet development
Material and energy balance analysis
Process stream evaluation
Process equipment modelling
Oil & Gas process engineering

Author

Himani Kinkar
Chemical Engineer | Process Engineer | Aspen HYSYS Process Simulation

Disclaimer
This project is intended for educational and portfolio purposes. 
The simulation model and results should not be used for actual plant design or operation without appropriate engineering validation and project-specific requirements.




