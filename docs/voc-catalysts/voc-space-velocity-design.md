---
title: "VOC Catalyst Space Velocity Design"
description: "Space velocity in VOC catalytic oxidation: how GHSV sets catalyst volume, conversion and system cost."
---

# Space Velocity and Contact Time in VOC Oxidation Design

> **Part of the [VOC Catalytic Oxidation: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.
>


**Direct answer:** Space velocity (GHSV) is the gas flow rate per catalyst volume per
hour — the inverse of contact time. It is the primary sizing parameter for VOC
oxidation reactors: typical designs run 10,000–30,000 h⁻¹, with the exact value set
by inlet concentration, temperature, required conversion and catalyst activity.

## Definitions

- **GHSV (h⁻¹)** = volumetric gas flow (Nm³/h) ÷ catalyst volume (m³).
- **Contact time (s)** = 3600 ÷ GHSV — the nominal residence time of gas in the
  catalyst bed.

Higher GHSV means a smaller catalyst for the same flow — cheaper capital but lower
conversion and higher pressure drop per unit flow. Lower GHSV buys conversion margin.

## How concentration changes the answer

The reaction heat is proportional to inlet VOC concentration:

- **Low concentration (< ~1 g/Nm³):** little exotherm; the catalyst operates near gas
  temperature and activity — not heat — limits the design. Space velocity is set by
  the required conversion.
- **Medium concentration (~1–4 g/Nm³):** noticeable adiabatic temperature rise
  (roughly 15–30°C per g/Nm³, subject to species and verification); sizing must check
  that the adiabatic rise stays within the catalyst's temperature window.
- **High concentration (> ~4 g/Nm³):** the bed can overheat; designs move to staged
  beds, dilution air, or heat recovery upstream. Above ~25% LEL, safety systems are
  mandatory.

## Sizing logic

1. Determine required conversion at the actual inlet concentration.
2. Select candidate GHSV from the catalyst's activity data at the operating
   temperature.
3. Check adiabatic temperature rise for the chosen concentration — verify it stays
   within the safe window.
4. Check pressure drop across the bed against fan economics.
5. Add deactivation margin: size for end-of-life activity, not fresh activity —
   typically 15–30% extra volume depending on duty class.

## Common design mistakes

- Sizing from fresh-catalyst data with no aging margin.
- Ignoring the adiabatic rise on medium-concentration streams, leading to local
  hot spots and sintering.
- Using total hydrocarbon concentration when species-level data would show a hard
  fraction that needs far more residence time.
- Running a fixed GHSV when flow varies seasonally — check performance at both
  minimum and maximum flow.

## Manufacturer perspective

We size with the species list and the flow range, then verify with simulation
testing on the customer's actual gas when the stream is non-standard. A design that
is correct at one flow rate but fails at another is not a correct design.

## Related articles

- [VOC Catalyst Selection](voc-catalyst-selection.md)
- [Regeneration & Lifecycle](voc-catalyst-lifecycle.md)

[← Back to the VOC Catalytic Oxidation: The Complete Guide](index.md)

## Related products

- [Platinum VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/platinum-catalyst/)
- [Platinum-Palladium VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/platinum-palladium-catalyst/)
- [Non-Precious-Metal VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/non-precious-metal-catalyst/)
