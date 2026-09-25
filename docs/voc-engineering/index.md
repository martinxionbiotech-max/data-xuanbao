---
title: "VOC Treatment Engineering: The Complete System Design Guide"
description: "VOC treatment system design: flow, concentration, species and duty pattern - adsorption, catalytic oxidation, RCO, RTO and combined systems."
---

# VOC Treatment Engineering: The Complete Guide

**Direct answer:** VOC treatment system design is decided by four numbers — flow
rate, concentration, species list and duty pattern. Adsorption wins at low
concentration, catalytic oxidation at medium, thermal oxidation at high
concentration and tough streams, and concentration wheels upgrade huge dilute
streams into small rich ones. This guide is the engineering hub for the whole
topic; detailed articles are linked throughout.

---

## 1. The technology map

| Technology | Sweet spot | Strengths | Watch out for |
| --- | --- | --- | --- |
| Carbon adsorption | Low concentration, recovery value | Cheap capex, recovery | Fire limits, bed replacement |
| Zeolite adsorption | Low concentration, humid streams | Non-flammable, regenerable | Lower capacity for some VOC |
| Catalytic oxidation (RCO) | Medium concentration, clean streams | Low fuel, low temperature | Catalyst poisons |
| Thermal oxidation (RTO) | High concentration / tough streams | Robust, no catalyst | Fuel cost, capex |
| Wheel + oxidizer | High flow, very low concentration | Shrinks the oxidizer | Rotor fouling, light-VOC limits |

The full selection matrix with cost structures is in
[Technology Comparison](voc-technology-comparison.md).

## 2. The four deciding numbers

**Flow rate.** Above ~20,000–30,000 Nm³/h at low concentration, heating the whole
stream becomes fuel-expensive — concentration enters the conversation.

**Concentration.** Below ~1 g/Nm³ adsorption economics dominate; ~1–4 g/Nm³ is
the catalytic sweet spot (the exotherm covers heat demand); above ~4 g/Nm³,
oxidation with heat recovery or RTO; LEL safety systems become mandatory above
~25% LEL.

**Species.** Halogens need special oxidizers with scrubbing; ketones limit carbon
safety; silicones and heavy metals rule out catalytic routes; light species
frustrate carbon and wheels.

**Duty pattern.** Intermittent lines favour quick-light-off catalytic units;
continuous lines favour RTOs and wheels.

## 3. Adsorption bed design

A bed is defined by face velocity, bed depth, contact time and breakthrough
criterion. The classic failure is sizing on total adsorbent mass while the bed
is too shallow — the mass transfer zone reaches the outlet early and breakthrough
arrives despite adequate capacity. The design sequence, velocity rules and MTZ
concept are in [Adsorption Bed Design](voc-adsorption-bed-design.md).

| Parameter | Granular carbon beds | Honeycomb beds |
| --- | --- | --- |
| Face velocity | 0.2–0.5 m/s | 1–3 m/s |
| Bed depth | 0.3–1.0 m | 0.3–0.6 m (stacked) |
| Contact time | 1–3 s | <1 s |
| Pressure drop | Higher | Low |

## 4. RCO vs RTO

Catalytic oxidation (RCO) destroys VOC at 250–400°C; thermal oxidation (RTO) at
750–850°C. RCO wins on fuel cost; RTO wins on robustness. The decision hinges on
the poison pre-check — a few ppm of silicone kills RCO economics while an RTO
ignores it. The full trade-off is in [RCO vs RTO](rco-vs-rto.md)
- [Emission Limits & Monitoring](voc-emission-limits-monitoring.md) — permit expressions, CEMS, parametric data.
- [LEL Control & Process Safety](voc-lel-process-safety.md) — flammable range, arrestors, interlocks.
- [Energy Management](voc-energy-management.md)
- [Combined Systems](voc-combined-systems.md) — chaining technologies, interface design.
- [Wet Scrubbers](voc-wet-scrubbers.md) — what they can and cannot capture. — heat recovery, self-sustaining operation..

## 5. Adsorbent selection: zeolite vs carbon

For adsorption duties the recurring choice: carbon (more capacity, flammable,
humidity-sensitive) versus zeolite (thermal regeneration, hydrophobic grades,
non-flammable). The structured comparison — capacity, regeneration, safety,
humidity behaviour — is in
[Zeolite vs Activated Carbon](zeolite-vs-activated-carbon.md).

## 6. The selection workflow

1. Measure: flow, species-level VOC analysis, concentration range, temperature,
   humidity, dust.
2. Screen poisons (silicones, halogens, metals) — they delete catalytic options.
3. Plot flow vs concentration — identify the technology zone.
4. Check duty pattern and available energy (steam, fuel, electricity).
5. Shortlist two technologies; compare 10-year TCO (capex + energy + consumables).
6. Pilot or simulate on the real stream before committing.

## 7. Quick reference: decision table

| Situation | Default route | Go to |
| --- | --- | --- |
| High flow, <500 mg/Nm³ | Wheel + small oxidizer | [Technology Comparison](voc-technology-comparison.md) |
| Medium flow, 1–3 g/Nm³, clean | RCO | [RCO vs RTO](rco-vs-rto.md) |
| Poison-laden or dusty stream | RTO with pre-treatment | [RCO vs RTO](rco-vs-rto.md) |
| Recovery of valuable solvent | Carbon/zeolite adsorption + regeneration | [Zeolite vs Carbon](zeolite-vs-activated-carbon.md) |
| Humid stream, low concentration | Hydrophobic zeolite bed | [Bed Design](voc-adsorption-bed-design.md) |

## 8. The complete VOC engineering series

- [Technology Comparison](voc-technology-comparison.md) — the full matrix and cost structures.
- [Zeolite vs Activated Carbon](zeolite-vs-activated-carbon.md) — the adsorbent decision.
- [Adsorption Bed Design](voc-adsorption-bed-design.md) — velocity, bed depth, MTZ, breakthrough.
- [RCO vs RTO](rco-vs-rto.md) — catalytic vs thermal oxidation.

## 9. Manufacturer perspective

Most selection errors come from choosing the technology before measuring the
stream. We start from the species list and the flow-concentration pair, screen
for poisons, then shortlist — and we say so plainly when a stream belongs to a
technology we do not supply rather than forcing a fit.

## Related products

- [Platinum VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/platinum-catalyst/)
- [Honeycomb Activated Carbon](https://xuanbaoenvironment.com/products/activated-carbon/honeycomb-activated-carbon/)
- [ZSM-5 Zeolite](https://xuanbaoenvironment.com/products/zeolite-molecular-sieve/zsm-5/)
- [Modified 13X Molecular Sieve](https://xuanbaoenvironment.com/products/zeolite-molecular-sieve/modified-13x/)
