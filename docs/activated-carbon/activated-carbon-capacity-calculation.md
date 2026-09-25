---
title: "Activated Carbon Capacity Calculation: Isotherms, Breakthrough and Bed Sizing"
description: "How to size an activated carbon bed: adsorption isotherms, working capacity, breakthrough behaviour and the calculation steps with worked logic."
---

# Activated Carbon Adsorption Capacity: Calculating Bed Size and Breakthrough

> **Part of the [Activated Carbon: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** Activated carbon bed sizing converts a concentration and flow into carbon mass using the
adsorption isotherm and a design working capacity. The key outputs are the bed volume, the breakthrough
time and the replacement or regeneration schedule. Getting capacity right is the difference between a bed
that meets its limit for a year and one that breaks through in a month.

## The capacity concept

Every carbon has an equilibrium capacity for each adsorbate — how many grams of VOC (or other species) one
gram of carbon holds at a given concentration and temperature. Practical design uses a fraction of this:

- **Working capacity** — equilibrium capacity minus the safety margin and the heel left after regeneration.
- **Typical design loadings** — 5–15% by weight for solvent recovery, 10–25% for water treatment and
  dedicated high-capacity duties.

## Inputs for sizing

- **Flow rate** and its variation (batch vs continuous).
- **Inlet concentration**, including peaks — the peak, not the average, sets breakthrough.
- **Temperature and humidity** — capacity falls as temperature rises; humidity competes for sites.
- **Target outlet concentration** — the emission limit or recovery requirement.
- **Isotherm data** — measured (preferred) or estimated for the specific carbon–adsorbate pair.

## Breakthrough time

The bed breaks through when the outlet concentration exceeds the target. Breakthrough time scales with:

```
t_b ≈ (bed mass × working capacity) / (flow × inlet concentration)
```

The mass transfer zone (MTZ) — the depth where adsorption is actively occurring — must fit inside the bed;
short beds with a long MTZ waste carbon because the zone reaches the outlet early.

## Practical design rules

- **Contact time** — gas-phase beds are commonly designed for 0.5–2.0 s empty-bed contact time.
- **Bed depth** — usually 0.5–1.5 m for fixed beds; deeper beds improve carbon utilization.
- **Pressure drop** — granular carbon is pressure-drop hungry; watch the fan budget.
- **Safety margin** — 20–30% extra capacity over the calculated value is standard practice.

## When measurements beat estimates

Isotherm predictions can be wrong by 2× for complex mixtures — competition between species, humidity
effects and pore blockage are hard to model. For anything above pilot scale, a small column test on the
actual gas is the cheapest insurance.

## Manufacturer perspective

We size from the real gas composition and ask for peaks, not averages. A carbon bed that meets the limit
only on the average day is a compliance failure on the worst day — which is when the plant gets inspected.

## Related articles

- [Quality Indicators](activated-carbon-quality-indicators.md)
- [Replacement Cycles](activated-carbon-replacement-cycles.md)
- [Adsorption Bed Design](../voc-engineering/voc-adsorption-bed-design.md)

[← Back to the Activated Carbon: The Complete Guide](index.md)

## Related products

- [Honeycomb Activated Carbon](https://xuanbaoenvironment.com/products/activated-carbon/honeycomb-activated-carbon/)
- [Coal-Based Columnar Carbon](https://xuanbaoenvironment.com/products/activated-carbon/coal-based-columnar-carbon/)
- [Coconut Shell Carbon](https://xuanbaoenvironment.com/products/activated-carbon/coconut-shell-carbon/)
