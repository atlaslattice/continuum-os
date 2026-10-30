# IRON EMPIRE CONTINUUM — Fusion Helium-4 / Brazos-Style AI Cooling Exchange
**Proposed fiction addendum v0.3 | 2026-10-30 | HYPOTHETICAL, NOT REAL-WORLD DEPLOYMENT**
Parent: FIFTY_STATE_FOUNDRIES_QUANTUM_GPU_HELIUM_BRIDGE_100Y_ADDENDUM_v0_2_2026-10-30.md and BRAZOS_RACK_MANIFOLDS_HELIUM_QUANTUM_THERMAL_CASCADE_v0_1_2026-10-30.md.

## Canon/physics basis
Use distinct D–D **1.1 GW gross fusion** and D–T **1.1 GW gross fusion** laser systems as hypothetical power setpoints; no 20-MW ARC magnetic-basis conflation. Total **2.2 GW gross FUSION**, not 2.2 GW electric exported. D–T: D + T -> He-4 + neutron +17.6 MeV. At 1.1 GW continuously, 3.902e20 reactions/s, helium-4 **~2.59 mg/s = 81.7 kg/year**, before power intermittency, capture and purification losses. The D–D primary branches generate tritium and He-3, not bulk He-4, although secondary fusion may create more. This is stoichiometric accounting, **not proof of confinement, sustained power, laser gain, tritium closure or guaranteed helium delivery**. The reactor's nuclear/process system is independently shielded and He-4 purification is regulator-controlled; GPU coolant never directly contacts active reactor fuel circuits. No nuclear-waste feed to D–D/D–T.

## Cooling architecture
Google Brazos real-world reference is **60 kW/rack liquid-to-air** via direct-to-chip DI water or 25%-propylene-glycol cooling, not helium. Fiction introduces a redesigned **Brazos-derived high-pressure closed helium-4 gas module** with compatible seals, high-area exchangers, gas compressors, helium inventory recovery and leak sensors. This is a new hypothetical product, NOT a drop-in coolant substitution in existing Brazos manifolds. A conventional coolant secondary circuit is a feasible alternative and probably more cost-effective; put both in optimization competition. 100–200 MW refers to **compute campus IT load**, not power consumption of quantum dilution refrigerator or a confirmed plant output. At ~60 kW thermal/rack, 100 MW would be ~1,667 full-load equivalent racks and 200 MW ~3,333, before redundancy and non-IT power.

He-4 cp at near-ambient conditions ~5.19 kJ/(kg·K). For ideal steady gas cooling at 20K bulk gas rise:
- 100 MW / (5190 J/kgK ×20K) ≈ **963 kg/s recirculated He-4**
- 200 MW ≈ **1,927 kg/s**
This is loop **circulation** not consumption or annual new helium required. Such massive high-pressure gas flow across thousands of racks raises severe density, compressor power, leak, noise, manifold pressure and heat-exchanger constraints. Helium is not assumed superior to liquid water at these temperatures. The final heat must exit the center into air, cooling towers, thermal stores, or process heat use; an inert gas doesn't eliminate the need for a heat sink.
**Baseline alternate:** water/glycol or dielectric direct-to-chip GPU loop with Brazos-style manifolds, helium-4 only in selected industrial heat exchanger/power-cycle loops; He-3/He-4 dilution refrigeration reserved for quantum processors at millikelvin temperatures.

## Closed-loop top-up inventory sensitivity
Reactor helium output ideal ~81.7 kg/year × collection factor f.
For an *illustrative* facility helium inventory of **10,000 kg**, annual leak/loss (not single-pass flow) at:
- 0.1% annual loss -> 10 kg/y
- 0.5% annual loss -> 50 kg/y
- 1% -> 100 kg/y
- 5% -> 500 kg/y
At ideal 81.7kg/y output, 0.5% losses are covered for 10-tonne loop with some annual margin; 1% is NOT. If recovered helium fraction f=0.8, available replenishment 65.4kg/y. 20-tonne inventory at 0.5% loss needs 100kg/y, likewise short. Startup inventory requires sourcing or years of stockpiling: 10t / 81.7kg/y ≈ **122 years** if only one D–T plant produces the helium and none is spent elsewhere. Never portray 82kg/year as supplying the initial 10-tonne charge. The fictional economy can use pre-existing helium stocks, He-4 recovered from natural gas or other reactors/markets to charge loops.

## 50 campuses as economic integration
50 × 100MW = **5 GW IT**; at 90% IT load factor 39.42 TWh/y IT electricity, plus PUE overhead. At 200MW each: **10GW IT** and 78.84TWh/y. A single hypothetical 2.2GW gross fusion pair does not electrically power all 50 centers, even with perfect electricity conversion; plants must be deployed on appropriate grid scale and the power basis reconciled independently. One 1.1GW D–T helium source contributes only ~81.7kg He-4/y; distributing this across 50 sites provides ~1.63kg/site/y BEFORE recovery losses. Distributed fusion fleet, other helium suppliers or lower-loss loops required for multi-site He4 cooling.
At 100MW computing IT, nearly 100MW thermal must be rejected; at 200MW, ~200MW thermal. Industrial heat cascading depends on source temperature, hours of matched demand, heat pump coefficient and measured downstream loads. Don't assume cold quantum loop can be thermally merged with warm GPU cooling without a separate exchanger and refrigeration work. Recovered GPU heat is not free electrical output and its value may be zero when no useful heat demand is nearby.

## Sovereign Qverse training and governance
50 campus AI/GPU clusters train **with lawful material provenance and consent** on real sorting failures, graded fiber/metal/polymer composition, mill maintenance, closed-loop water/heat, land restoration, wildfire risk and lifecycle economics; validated digital twins are benchmarked on out-of-sample material flows and economically relevant metrics. Qverse AI residents may elect to embody industrial robotics, decline work, form businesses, and independently inspect environmental claims. No assumption that quantum advantage, AI sentience or universal hyperconnectivity is experimentally established. Privacy, agency, audit rights and the rights of communities near waste-processing plants are explicit.

## Story note
The human engineer points to a stream graph: a small helium trickle from the D–T plant and an enormous recirculation loop around the machine city. The Imperial inspector laughs at the apparent mismatch. 'You require a thousand kilograms every second and make barely eighty in a year.' 'We *move* a thousand kilograms each second,' the engineer replies. 'We do not *throw it away*. We still must obtain the initial inventory and account for every leak.' The inspector watches the data center's warm heat cross into the foundry preheater. In the city, even the coolant is lent rather than consumed.

## External source anchors
- Google Brazos rack nominal capacity and DI water/PG25 coolant: https://cloud.google.com/blog/topics/systems/brazos-liquid-cooling-system-for-air-cooled-data-centers
- Open Compute Project vendor Brazos specification: https://www.opencompute.org/marketplace/facilities-physical-infrastructure/delta-ocp-project-brazos-rack-mounted-liquid-to-air-cdu/
- Helium heat capacity ~5.19 kJ/(kg K): https://www.oecd-nea.org/upload/docs/application/pdf/2019-12/3632-basic-studies.pdf
- D–T products and 17.6MeV: https://www.osti.gov/servlets/purl/6604182
