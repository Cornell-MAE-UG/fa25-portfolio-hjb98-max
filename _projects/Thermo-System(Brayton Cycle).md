---
layout: project
title: Gas Powered Turbine (Brayton Cycle)
description: Gas Powered Turbine (Brayton Cycle)
technologies: [Excel]
image: /assets/images/Power-Plant.jpg"
images:
	
	- /assets/images/Braxton Cycle.jpg"
	- /assets/images/Braxton Cycle T-S.jpg"
---

Gas Powered Turbine (Brayton Cycle)
Thermodynamics Portfolio: Gas Turbine Power Plant (Brayton Cycle)
Introduction
The system that will be analyzed is an industrial gas turbine. The gas turbine is a common tool used in the generation of electricity in a grid-connected power station, industry, or as a turbine for airplane engines. The gas turbine works on the Brayton cycle. The cycle utilizes the chemical energy of the fuel in the production of mechanical or electrical energy. The process acts as a good illustration of the first and second laws of thermodynamics for an open, steadyflow system.
Quantitative Description of Operation
A simple gas turbine has four main processes. They include:

1. Air Inlet (State 1): The air enters the compressor at atmospheric pressure and temperature.
2. Compression (1 → 2): The compressor raises the pressure of the air. This process requires shaft work input and increases the air temperature.
3. Combustion (2 → 3): Fuel is injected and burned at constant pressure, resulting in a substantial rise in the temperature of the working fluid.
4 Expansion (3 → 4): Hot gas expands in the turbine to produce shaft work. The work is used to run the compressor as well as to generate electrical energy.
5. Exhaust (4 → 1): The exhaust gases are released into the atmosphere, thus completing one cycle.
System Diagram and Assumptions

The gas turbine is analyzed using a steady-state, steady-flow control volume model. The working fluids flow continuously in each component.
Assume
- Steady-state, steady-flow processes
- Small change in Kinetic Energy and Potential Energy
- Ideal gas behavior of the Working Fluid
- The compressor and turbine are adiabatic
- Actual combustion process modeled by adding heat at constant pressure

Mass Balance
For steady-state operation:

Σṁ_in = Σṁ_out

For each component:

ṁ_in = ṁ_out = ṁ
Energy Balance (First Law)
General steady-flow energy equation (neglecting kinetic and potential energy):

Q̇ − Ẇ = ṁ(h_out − h_in)

Compressor (adiabatic):
Ẇ_c = ṁ(h₂ − h₁)

Combustor:
Q̇_in = ṁ(h₃ − h₂)

Turbine (adiabatic):
Ẇ_t = ṁ(h₃ − h₄)

Net power output:
Ẇ_net = Ẇ_t − Ẇ_c
Entropy Balance (Second Law)
General entropy balance for steady-flow control volume:

Σṁs_in + Σ(Q̇/T) = Σṁs_out + Ṡ_gen

Compressor:
Ṡ_gen,c = ṁ(s₂ − s₁) ≥ 0

Turbine:
Ṡ_gen,t = ṁ(s₄ − s₃) ≥ 0

Combustor:
The combustor experiences the largest entropy generation due to combustion and heat transfer across finite temperature differences.
Performance Metrics
Thermal efficiency:

η_th = Ẇ_net / Q̇_in

Back work ratio:

BWR = Ẇ_c / Ẇ_t
Design Change Analysis: Increased Turbine Inlet Temperature
Increasing the turbine inlet temperature T₃ increases the enthalpy entering the turbine, which increases turbine work output:

Ẇ_t = ṁ(h₃ − h₄)

Since compressor work is largely determined by pressure ratio, net work output increases. Although heat input also increases:

Q̇_in = ṁ(h₃ − h₂)

The increase in net work often leads to higher thermal efficiency.

Engineering tradeoffs include:
- Higher material stresses and creep in turbine blades
- Increased cooling requirements
- Higher emissions
- Increased system cost and maintenance
Conclusion
This portfolio demonstrates the application of mass, energy, and entropy balances to a real gas turbine power plant. By analyzing the Brayton cycle and evaluating the effect of increased turbine inlet temperature, this work shows how thermodynamic principles guide real engineering design decisions in energy systems.
