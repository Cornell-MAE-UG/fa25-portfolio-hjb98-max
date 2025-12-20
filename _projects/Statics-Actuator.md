---
layout: project
title: Actuator Lever Arm
description: Static Equilibrium
technologies: [AutoCAD, Excel]
image: /assets/images/radio-machine-cad.png
images:
	- /assets/images/radio-machine-cad.png
	- /assets/images/radio-machine.jpg
	- /assets/images/old-radio.jpg
---

Gas Powered Turbine (Brayton Cycle)

This portfolio analyzes an industrial gas turbine power plant, a widely used device for electricity generation in grid-scale power plants, industrial applications, and aviation propulsion. Gas turbines operate on the Brayton cycle and convert the chemical energy of fuel into mechanical work and, ultimately, electrical power. This system provides a strong real-world example for applying the first and second laws of thermodynamics to an open, steady-flow system.
Qualitative Description of Operation
A simple gas turbine consists of four primary processes:

1. Air Inlet (State 1): Ambient air enters the compressor at approximately atmospheric pressure and temperature.
2. Compression (1 → 2): The compressor raises the pressure of the air. This process requires shaft work input and increases the air temperature.
3. Combustion (2 → 3): Fuel is injected and combusted at approximately constant pressure, significantly increasing the temperature of the working fluid.
4. Expansion (3 → 4): High-temperature gas expands through the turbine, producing shaft work. Part of this work drives the compressor, and the remainder is converted into electrical power.
5. Exhaust (4 → 1): The exhaust gases are released to the environment, completing the cycle.
System Diagram and Assumptions
The gas turbine is modeled as a steady-state, steady-flow control volume. The working fluid flows continuously through each component.

Assumptions:
- Steady-state, steady-flow operation
- Negligible changes in kinetic and potential energy
- Ideal gas behavior for the working fluid
- Compressor and turbine are approximately adiabatic
- Combustor modeled as heat addition at constant pressure
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
This portfolio demonstrates application of mass, energy, and entropy balances to a real gas turbine power plant. By analyzing the Brayton cycle and evaluating the effect of increased turbine inlet temperature, this work shows how thermodynamic principles guide real engineering design decisions in energy systems.
