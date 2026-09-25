---
title: "3A and 4A Molecular Sieves: Pore Size, Drying Duty and Regeneration"
description: "3A vs 4A molecular sieves compared: 0.3 vs 0.4 nm pore openings, deep drying and separation duties, dew-point capability, water capacity and regeneration temperatures."
---

# 3A and 4A Molecular Sieves: Choosing the Right Pore Size

> **Part of the [Zeolite Molecular Sieves: The Complete Guide](../molecular-sieves/index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** 3A sieve (0.3 nm pores, potassium-exchanged A zeolite) admits water molecules but excludes CO₂, methane and ethanol — the choice for deep drying and solvent dehydration where nothing but water may be adsorbed. 4A sieve (0.4 nm pores, sodium A zeolite) co-adsorbs water with small molecules like CO₂, giving higher total capacity but less selectivity — the choice for general gas drying and small-stream CO₂ removal. Regeneration for both is thermal, typically 200–350 °C.

---

## 1. The pore-size logic

The type number states the effective pore opening in ångströms. Selection is decided by comparing the kinetic diameters of the molecules involved:

| Molecule | Kinetic diameter | Enters 3A (0.3 nm)? | Enters 4A (0.4 nm)? |
| --- | --- | --- | --- |
| Water | ~2.8 Å | Yes | Yes |
| CO₂ | ~3.3 Å | No | Yes |
| Methane | ~3.8 Å | No | Yes |
| Ethanol | ~4.4 Å | No | No |

- **3A** = potassium-exchanged type A zeolite. Water in, everything else out.
- **4A** = sodium type A zeolite. Water plus CO₂, H₂S, methanol, ethanol vapor, NH₃.

Molecular diameters are textbook values (general technical knowledge); pore assignments are vendor-standard (sorbsieve.com).

## 2. Typical duties

| Duty | Choice | Reason |
| --- | --- | --- |
| Ethanol / fuel-ethanol dehydration to ≥99.5% (v/v) | 3A | Adsorbs water without holding ethanol |
| Solvent drying (dries the solvent, not the solvent out of itself) | 3A | Size exclusion protects the product |
| Natural-gas deep drying / LNG pre-liquefaction | 3A | Dew points to −100 °C, water below 0.1 ppmv |
| Olefin cracker-gas drying (<1 ppm water, dew point < −70 °C), refrigerants, LPG | 3A | Deep dry without co-adsorbing product |
| Insulated-glass units | 3A | Adsorbs moisture only — 4A would co-adsorb O₂/N₂, creating pressure differences that deform the panes |
| Compressed-air drying, pipeline-gas dew-point control (−10 to −20 °C), CO₂ removal | 4A | Higher total capacity, small-molecule co-adsorption acceptable |
| Detergent builders (phosphate replacement), water softening | 4A | Ion-exchange duty, not gas drying |
| Air separation pre-purification | 4A | CO₂ + water removal ahead of cryogenic or PSA separation |

3A deep-drying capability: water below 1 ppm / dew point below −70 °C in cracker-gas service (Chinese catalyst vendors), down to −100 °C claimed for natural-gas deep drying (vendor literature — confirm against Zeochem/UOP datasheets before design). 4A in pipeline service delivers −10 to −20 °C dew points.

## 3. Water capacity and kinetics

- **Static water capacity**: 3A ≥ 20 wt%; 4A ~20–22 wt% (vendor specifications; GB/T 6287-2021 defines the static water adsorption test method). Roughly 0.2 g water per gram of 4A at 25 °C / 60% RH.
- **Bulk density** (4A reference): ~770 g/L → on the order of 150–170 g water per litre of bed (inference from the two vendor numbers — verify per batch).
- **Kinetics**: in pure water-removal service, 3A is the faster adsorber of water; 4A's higher total capacity comes with co-adsorption of other species.

## 4. Regeneration

- **Temperature window**: 200–350 °C for 3A/4A/5A; below ~200 °C water does not desorb fully, above ~350 °C the crystal structure can be damaged. Heat-up 25–50 °C/h, hold 2–8 hours; laboratory regeneration commonly 200–350 °C oven, 2–4 hours.
- **Cooling discipline**: after regeneration, cool under dry sweep gas — exposing a hot regenerated bed to ambient air instantly re-humidifies it.
- **Maximum continuous operating temperature** (4A): 400 °C.
- **Service life**: 2–3 years typical (vendor sources conflict at 3–5 years; take the conservative figure and verify per application).

## 5. Specification points for buyers

- **Chinese standards**: GB/T 10504-2017 for 3A sieves; HG/T 2524-2010 for 4A (sphere, extrudate, powder, activated powder grades); static water adsorption per GB/T 6287-2021.
- **Always state**: equilibrium water capacity at which conditions, crushing strength, and the dew point the bed must hold — not just "3A" or "4A".
- **13X caution**: regeneration temperatures cited for 13X conflict across sources (250–350 °C vs 350–500 °C); use the lower recommended range unless a datasheet says otherwise.

Related: [Molecular Sieve Dehydration](molecular-sieve-dehydration.md), [Type Selection](molecular-sieve-type-selection.md), [Regeneration](molecular-sieve-regeneration.md).
