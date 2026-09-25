---
title: Activated Carbon Under Humidity and Temperature: Capacity, Safety Limits and Design Mitigations
description: How relative humidity and temperature change activated carbon adsorption capacity in gas-phase duty, with quantified literature values, Chinese regulatory red lines (HJ 2026-2013) and design mitigations for humid low-concentration exhaust.
---

# Activated Carbon Under Humidity and Temperature

**Direct answer:** In gas-phase duty, humidity is usually the bigger enemy and temperature the stricter safety limit. Activated carbon keeps most of its VOC capacity up to roughly 50% relative humidity; beyond that, capacity falls — by roughly half or more at RH 90% on hydrophilic carbons. Temperature cuts both ways: it raises kinetics but lowers equilibrium capacity, and Chinese engineering regulations cap inlet gas at 40°C and bed temperature at 83°C. The practical consequence: humid, low-concentration exhaust (coating, printing, odor) should be designed around humidity first; hot exhaust must be cooled before the bed — both for capacity and for fire safety.

---

## 1. Humidity: quantified effects

The direction is undisputed; the magnitude depends on carbon hydrophobicity, RH range and pollutant concentration. Published values (all Literature class, High confidence unless noted):

| Finding | Condition | Source (year) |
|---|---|---|
| Toluene capacity essentially preserved up to RH 50%; erosion above that | AC vs high-silica FAU-Y zeolite, room temperature | Microporous Mesoporous Mater. (2020) |
| Benzene capacity **−55.9%** from RH 0→90% on hydrophilic walnut carbon; **−19.3%** on PDMS-hydrophobized same carbon | Dynamic column | Sep. Purif. Technol. (2020) |
| Toluene capacity **−46%** from RH 0→80% on starch-based carbon; **−22%** on PDVB-hydrophobized composite | High humidity | Chem. Eng. J. (2024) |
| Unmodified carbon equilibrium water uptake 21.9 wt% (pore-volume occupancy reference) | Toluene-family VOC | ACS Appl. Mater. Interfaces (2021) |
| ACF felt capacity >120 mg/g toluene; at high inlet concentration RH barely matters, at low concentration RH is decisive | 21–18,160 mg/m³, 0.37 m/s | Environ. Technol. (2005) |
| Water vapor "severely inhibits" low-concentration VOC adsorption; heat-pretreated coal carbon beats alkali-impregnated at 60% RH | Low-conc. toluene, coal-based | Energy & Fuels (2021) |
| Multi-component breakthrough model (extended Manes) error: 11.8% dry vs 17.2% at 55/95% RH — water competition is the main unmodeled term | 5 VOCs, 0–95% RH | Environ. Sci. Technol. (2019) |

Three rules fall out of this data:

1. **RH 50% is a defensible design boundary** — below it, activated carbon performs near-dry; above it, expect progressive loss.
2. **Concentration decides how much it hurts.** High-concentration duty (solvent recovery, hundreds of ppm) rides over humidity; low-concentration duty (single-digit ppm odor/VOC) can be dominated by it. The Chinese "RH above 50–60% efficiency drops markedly" folklore agrees in direction, but we found no citable Chinese quantitative source — the numbers above are from international literature.
3. **Carbon choice moves the curve.** Hydrophobic carbons (unoxidized coal, coconut shell) and hydrophobized carbons (silicone/PDMS/PDVB-modified) hold far more capacity in humid air. "Coconut shell" is *not* automatically a humidity solution — modification is the documented one.

## 2. Temperature: equilibrium vs kinetics vs safety

- **Capacity falls with rising temperature** (adsorption is exothermic; the Dubinin–Radushkevich equation makes the temperature dependence explicit). We found **no universal "per °C" coefficient** in any citable source — treat such rules as unsourced folklore and use measured isotherms.
- **Kinetics improve with rising temperature** — the bed saturates faster (shorter breakthrough time), which matters for short-cycle operations.
- **Adsorption heat is real**: a dry bed on high-concentration VOC warms measurably; a wet bed warms less (water desorption absorbs heat). This is a design input, not a curiosity — see [Fire Safety](activated-carbon-fire-safety.md).

**Regulatory red lines (China HJ 2026-2013, Regulatory class, High confidence):**

- Exhaust entering the adsorber: **below 40°C**.
- Bed temperature during adsorption: **below 83°C**, with automatic alarm and cooling above it (anti-self-ignition).
- Hot-air regeneration: **below 120°C** for activated carbon and fiber; below 200°C for zeolite; hot-air regeneration prohibited for ketone-containing and other easily ignitable exhausts.
- Steam regeneration: below 140°C.

## 3. Design mitigations for humid duty

Ranked roughly by cost/effectiveness for humid, low-concentration VOC exhaust:

1. **Cool-and-dehumidify upstream** — cooling below the dew point removes water and brings the gas into the <40°C compliance window at the same time.
2. **Choose the carbon for humidity** — hydrophobic or hydrophobized grades; verify with a breakthrough test at *your* RH, not at lab RH.
3. **Switch adsorbent where conditions justify it** — high-silica zeolites hold capacity at higher RH (to ~70% RH for FAU-Y) and regenerate hotter; see [Zeolite vs Activated Carbon](../voc-engineering/zeolite-vs-activated-carbon.md).
4. **Down-rate the design capacity** — apply an RH correction to working capacity from measured data, and schedule the 80% dynamic-capacity replacement trigger (HJ 2026-2013) accordingly.
5. **Avoid hot-air regeneration of wet, ketone-laden or low-flashpoint streams** — both capacity recovery and fire risk argue for steam or inert-gas regeneration, or off-site reactivation.

## 4. What to ask the supplier

- "Show me the breakthrough curve for this carbon at my concentration **and my humidity** — not dry-lab conditions."
- "Is this grade hydrophobized, or naturally hydrophobic? What is its equilibrium water uptake at 80% RH?"
- "What bed temperature do you design for, and what happens at my worst-case inlet temperature?"
- For humid low-concentration duty: "What RH correction factor did you apply to working capacity?"

**Bottom line:** humidity steals capacity, temperature steals margin and safety. Design humid low-concentration systems around the RH number, keep every gas stream below 40°C into the bed, and demand wet-condition breakthrough data — a dry-lab data sheet is the most common source of field disappointment in adsorption projects.

---

*Data classification: humidity/temperature effect values are Literature class with per-study High confidence; HJ 2026-2013 limits are Regulatory class (High); the "50–60% RH folklore" is flagged as unsourced Chinese engineering lore (direction consistent with literature, magnitude uncitable). The missing "per-°C capacity coefficient" was searched and NOT FOUND — deliberately not invented. Related: [Adsorption Mechanism](activated-carbon-adsorption-mechanism.md), [Breakthrough Curves](activated-carbon-breakthrough-curves.md), [Fire Safety](activated-carbon-fire-safety.md), [Capacity Calculation](activated-carbon-capacity-calculation.md).*
