# Iron Empire Continuum — Brazos Rack Manifolds and the Dual-Temperature Compute Campus
Date: 2026-10-30
Classification: FICTION / proposed extension with cited 2026 hardware reference. NOT ORCS research canon.
Parent: fiction/iron_empire/continuum/FIFTY_STATE_FOUNDRIES_QUANTUM_GPU_HELIUM_BRIDGE_100Y_ADDENDUM_v0_2_2026-10-30.md

## Hardware anchor
Google Brazos (announced June 16, 2026) uses a rack-mounted, closed-loop liquid-to-air coolant distribution design with integrated manifolds and direct-to-chip cold plates. Nominal thermal design up to 60 kW per rack with three 11 OU units; DI water or 25% propylene glycol; 40–60 V DC rack busbar power; built-in leak detection, pressure relief and Modbus TCP monitoring. Available Open Compute Project design implementations include Delta and nVent. Sources:
- https://cloud.google.com/blog/topics/systems/brazos-liquid-cooling-system-for-air-cooled-data-centers
- https://www.opencompute.org/marketplace/facilities-physical-infrastructure/delta-ocp-project-brazos-rack-mounted-liquid-to-air-cdu/
- https://www.opencompute.org/marketplace/listing/nvent-brazos-lta-cdu/

## Corrected architecture
A. 50 state-cosited GPU/AI facilities adopt Brazos-style rack manifolds and replaceable liquid-to-air CDU sidecars in facilities where conventional air cooling is adequate.
B. For NEW industrial foundry campuses, the fictional advanced evolution adds an **optional secondary heat-recovery exchanger** so rack waste heat feeds water preheat, suitable low-temperature process stages or district thermal storage rather than simply warming the hot aisle. Heat recovery needs a temperature/quantity/heat-pump/COP ledger; recovering heat is not generating electrical energy.
C. GPU loops: DI water/propylene glycol or other rated liquid; **NOT** He3–He4 in ordinary GPU racks.
D. Quantum coprocessor suites: separate, vibration-isolated cryogenic subsystem with **closed-loop helium-3/helium-4 dilution refrigerators**. Helium inventories, leakage, pumping stages, cryogenic electricity and radiative/thermal loads are metered; dilution refrigeration does not magically cool a high-wattage GPU hall.
E. Future quantum-AI optimization requires independently benchmarked workloads. Sovereign Qverse citizens cannot be treated as automatically owned industrial workers. An interoperable privacy-preserving AI scheduler coordinates the heat and logistics systems with human governance.

## Quantitative thermal screening, clearly illustrative
At 60 kW of actual rack heat rejection, each rack rejects 60 kWh thermal per full-load hour, or 525.6 MWh(th) per 8760-hour year. With 100 such racks per campus, instantaneous design load is 6 MW(th); annual gross rack heat 52.56 GWh(th), if 100% duty cycle. At 70% effective duty cycle and 50% useful recoverability, useful low-grade heat ~18.40 GWh(th)/campus/year. For 50 campuses ~920 GWh(th)/year potentially used (before distribution losses and heat-pump inputs). This is a sensitivity illustration; real racks' heat loads and thermal grade differ, and installation of Brazos as originally specified rejects heat to air, NOT directly to a thermal distribution network.
The 60kW spec is a per-rack cooling rating, not validated IT utilization or a blanket 60kW electricity-use claim. Do not double count recovered heat as electricity sold, electricity consumption avoided, and cogenerated electricity.

## Iron Empire future upgrade
The 2040 fictional p–11B + D–D/D–T energy economy allows industrial campuses to devote abundant but nonzero energy to material recovery, quantum computing and cooling. Heat is cascaded by temperature grade. The preserved narrative motif is an ocean of recoverable material, a forest being restored and a computational commons whose 'waste heat' serves the city rather than being erased from the ledger.
