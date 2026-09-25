---
title: How Activated Carbon Adsorbs: Mechanism, Pore Diffusion, Competition and Breakthrough
description: A step-by-step engineering explanation of activated carbon adsorption — physisorption, pore diffusion, competitive adsorption, breakthrough and regeneration — with quantified data from Chinese and international sources and their confidence ratings.
---

# How Activated Carbon Adsorbs: From Physisorption to Breakthrough

**Direct answer:** Activated carbon adsorbs pollutants in five linked steps — (1) physical adsorption onto pore surfaces by van der Waals forces, (2) diffusion of molecules through the pore network, (3) competition with water vapor and co-pollutants for the same sites, (4) progressive saturation of the bed expressed as a breakthrough curve, and (5) regeneration by supplying the energy adsorption released. The two numbers that govern engineering design — dynamic adsorption capacity and breakthrough time — are determined by the *slowest* of these steps under your specific conditions, not by the carbon's static surface area alone.

---

## 1. Step 1: Physical adsorption — the surface does the work

Activated carbon removes gas or liquid molecules primarily by **physisorption**: van der Waals/London dispersion forces bind molecules to the pore surface without changing their electronic structure. Binding energies are small (5–10 kJ/mol for gases on carbon), so the process is reversible — raising temperature or lowering pressure releases the adsorbate. This reversibility is both a strength (regeneration is possible) and a limit (capacity falls as temperature rises).

Three properties of the *adsorbate* dominate:

- **Boiling point / volatility** — high-boiling, heavy molecules are adsorbed far more strongly than light, volatile ones; this is why activated carbon polishes VOCs easily but cannot hold methane or hydrogen at ambient temperature.
- **Molecular size** — a molecule must fit the pore; iodine (≈0.27 nm) indicates micropore capacity, carbon tetrachloride (≈0.55 nm) probes slightly larger pores, methylene blue probes mesopores.
- **Polarity** — polar molecules (alcohols, ketones) interact with oxygen-containing surface groups; the degree of surface oxidation changes capacity for polar species.

**Chemisorption** — a chemical reaction between adsorbate and surface (impregnated carbons removing H₂S, NH₃, mercury, or radioiodine) — is a different regime: stronger binding, more selective, and harder to regenerate. Standard VOC/water purification duty is dominated by physisorption; impregnated carbons are a special class ([Impregnated Carbon](activated-carbon-impregnated.md)).

## 2. Step 2: Pore diffusion — the transport network

Molecules travel in three stages: film diffusion across the external boundary layer → transport through macropores and mesopores (the "highways") → adsorption in micropores (<2 nm, the "storage"). IUPAC classification: micropore <2 nm, mesopore 2–50 nm, macropore >50 nm.

The engineering consequences:

- **Particle size sets kinetics.** Powdered carbon (PAC, mostly <100 μm) has diffusion paths thousands of times shorter than granular carbon (0.5–4 mm), so PAC adsorbs far faster per unit mass — at the cost of being a one-shot material in water treatment.
- **Mesopores are the delivery network.** A carbon with enormous micropore volume but few mesopores can show poor dynamic performance — molecules cannot reach the storage fast enough. This is why the mesopore volume matters for fast-cycling gas duty.
- **Temperature accelerates diffusion.** Higher temperature shortens the time to saturation because diffusion coefficients rise — but simultaneously lowers equilibrium capacity (§4). Kinetics improves; thermodynamics worsens.

## 3. Step 3: Competitive adsorption — humidity is a competitor, not an atmosphere

Water vapor competes with pollutants for the same micropores. The severity depends on three factors, and **oversimplified rules of thumb mislead**:

- **Relative humidity (RH)**: activated carbon holds its toluene capacity roughly up to RH 50%, then capacity erodes as RH rises (2020 comparative study — High confidence). Quantified examples: a hydrophilic walnut-shell carbon lost **55.9%** of its benzene capacity from RH 0%→90%, while a PDMS-hydrophobized version of the same carbon lost only 19.3% (2020, Sep. Purif. Technol.); a starch-based hierarchical carbon lost 46% of toluene capacity from RH 0%→80%, a hydrophobized composite 22% (Chem. Eng. J. 2024). An unmodified carbon was measured to take up 21.9 wt% water at equilibrium — a sense of how much pore volume water can occupy.
- **Concentration**: at high VOC concentration (hundreds of ppm and above) humidity barely matters — the VOC competes successfully. At low concentration (single-digit ppm), humidity becomes the decisive factor. This is why coating/printing exhaust (low concentration, high flow) must address humidity explicitly, while solvent-recovery duty (high concentration) tolerates it.
- **Carbon hydrophobicity**: coconut-shell and unoxidized coal carbons are relatively hydrophobic; oxygen-rich surfaces (chemical activation residues, oxidation treatments) are hydrophilic. Surface modification (silicone, PDMS, PDVB) is the documented anti-humidity solution — not "any coconut carbon".

A useful engineering takeaway: for humid, low-concentration VOC duty, prefer hydrophobic carbons or molecular-sieve adsorbents, or dehumidify upstream — see [Zeolite vs Activated Carbon](../voc-engineering/zeolite-vs-activated-carbon.md).

## 4. Temperature: equilibrium falls, kinetics rise

Two opposing effects, both real:

1. **Capacity falls as temperature rises.** Adsorption is exothermic; the adsorption enthalpy exceeds liquefaction enthalpy (ΔH_ads = ΔH_liq − RT·ln c). The Dubinin–Radushkevich equation, which predicts capacity for aromatic and chlorinated VOCs on activated carbon, contains temperature explicitly — capacity declines monotonically with T. There is **no single universal "X% per °C" coefficient** in the literature; the slope depends on the adsorbate-carbon pair and must come from measured isotherms. Treat any "per degree" rule of thumb you see as unsourced.
2. **Kinetics improve as temperature rises.** Pore diffusion accelerates, so the bed reaches saturation sooner.

**Engineering red lines (China HJ 2026-2013, High confidence):**

- Exhaust temperature entering the adsorber should be **below 40°C**.
- Bed temperature during the adsorption cycle must stay **below 83°C**; automatic alarm and cooling above that threshold — this is an anti-self-ignition limit.
- Hot-air regeneration: **below 120°C** for activated carbon (fiber); below 200°C for molecular sieves; hot-air regeneration is prohibited for exhausts containing ketones and other easily ignitable species. Steam regeneration: below 140°C.
- Heat release is real: a dry bed adsorbing high-concentration VOCs can warm measurably (adsorption heat); a wet bed warms less because water desorption absorbs heat. Design for the temperature excursion, not for isothermal operation.

## 5. Step 4: Breakthrough — how a bed actually exhausts

A fixed bed does not saturate uniformly. An adsorption front — the **mass transfer zone (MTZ)** — moves from inlet to outlet. The outlet concentration stays near zero until the front arrives; the moment outlet concentration reaches the threshold (an emission limit or a fraction of inlet concentration, e.g. 5%) is the **breakthrough point**, and the time to reach it is the breakthrough time.

- The area above the breakthrough curve integrates to the maximum capacity; the quantity adsorbed *up to breakthrough* is the **working capacity** — what the bed delivers in service.
- China's HJ 2026-2013 defines the engineering twin, **dynamic adsorption capacity** (动态吸附量): the average adsorbed mass per unit adsorbent when outlet concentration reaches the set value at constant temperature, pressure and flow (mg/g).
- A steep S-curve means a narrow MTZ and high bed utilization; a shallow curve means a wide MTZ and wasted bed. MTZ widens with: larger particle size, higher velocity, lower inlet concentration, higher humidity. This is exactly why HJ 2026-2013 caps superficial velocities: granular beds below **0.60 m/s**, activated-carbon fiber beds below 0.15 m/s, honeycomb below 1.20 m/s.
- Pressure drop limits from the same standard: below 2.5 kPa for non-fiber beds, below 4 kPa for fiber beds.

For the full treatment including design parameters, see [Adsorption Bed Design](../voc-engineering/voc-adsorption-bed-design.md) and [Breakthrough Curves & Bed Sizing](activated-carbon-breakthrough-curves.md).

## 6. Step 5: Regeneration — paying back the energy

Desorption requires the energy adsorption released. Three routes:

- **Thermal swing (TSA)**: hot gas or steam reverses the equilibrium. Chinese regulatory ceilings: steam <140°C; hot air <120°C (carbon) / <200°C (zeolite).
- **Pressure swing (PSA/VSA)**: pressure reduction releases adsorbate.
- **Thermal reactivation** (off-site or dedicated furnace): drying at ~105°C, desorption/decomposition at 500–900°C under inert atmosphere, then steam/CO₂ gasification of residues at ~800°C. Each cycle burns off 5–15 wt% of the bed.

Operationally, HJ 2026-2013 says replace the adsorbent when dynamic capacity falls to **80%** of design value. See [Regeneration](activated-carbon-regeneration.md) for the full lifecycle economics.

## 7. What this means for specifiers

1. **Ask for dynamic data, not just static surface area.** BET and iodine describe the carbon; dynamic adsorption capacity (mg/g at *your* concentration, velocity, bed height) describes *your* system. The two can diverge by a large margin in humid, low-concentration duty.
2. **State humidity and concentration together** — they jointly determine whether you have a capacity problem. One without the other is unanswerable.
3. **Design within the red lines**: inlet <40°C, bed <83°C, and the velocity/pressure-drop caps of HJ 2026-2013 if the unit will be audited in China.
4. **Anticipate the temperature excursion** in high-concentration duty — including self-heating margins.
5. **Prefer measured isotherms over "per-degree" folklore** when extrapolating capacity to summer conditions.

**Bottom line:** capacity is a system property, not a material property. The carbon supplies the surface; your conditions — concentration, humidity, temperature, velocity, bed height — decide how much of that surface is actually used. The mechanism chain above is the checklist for finding where the loss is.

---

*Data classification: mechanism statements are General technical knowledge; quantified humidity/temperature effects are Literature values with the cited studies (High confidence); HJ 2026-2013 figures are Regulatory/standard values (High). "X% per °C" folklore was searched for and NOT FOUND in any citable source — flagged deliberately. See [Data Classification(../methodology/data-classification.md) and [Sources & Evidence(../methodology/sources.md).*
