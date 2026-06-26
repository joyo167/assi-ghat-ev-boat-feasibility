# assi-ghat-ev-boat-feasibility

# Assi Ghat Electric Boat Propulsion Feasibility Study

A techno-economic and cell-level engineering feasibility study for converting 
Varanasi's Assi Ghat boat fleet (800+ boats, currently diesel/CNG) to electric 
propulsion — covering power sizing, battery bank/module design, cost modeling, 
and cell-level reliability risk.

## Overview
- Diesel/CNG fleet baseline and motivation for electrification
- Three boat classes analyzed: 10 HP, 20 HP, 180 HP
- Scope: technical feasibility + financial payback + cell-level engineering

## Methodology
1. Power requirement derivation (hydrodynamic drag scaling, upstream/downstream asymmetry)
2. Battery bank sizing (kWh) per boat class
3. Cost modeling: initial investment vs. CNG operating cost, payback period
4. Cell-level breakdown: cell selection, module/bank architecture, BMS requirements

## Key Results
- Battery sizing: 30 kWh / 60 kWh / 400 kWh across boat classes
- Payback period: ~6.3 years for standard (10 HP) boats
- Cell choice: LiFePO₄ 26800 cylindrical (3.6V, 6Ah, 167 Wh/kg) for thermal safety
- Primary scale-up risks: BMS design complexity, cell matching/balancing

## Electrochemistry Background
Brief section/folder covering the underlying theory used to justify chemistry 
and design choices: intercalation, SEI formation, Gibbs free energy and cell 
voltage, C-rate tradeoffs across LFP/NMC/LCO.
