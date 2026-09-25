---
title: Breakthrough Curves, Mass Transfer Zone and Working Capacity: Reading an Adsorption Bed
description: How to read a breakthrough curve — breakthrough time, mass transfer zone, working capacity vs total capacity — and what shortens breakthrough time in real fixed-bed adsorption systems, with Chinese standard definitions and literature data.
---

# Breakthrough Curves, Mass Transfer Zone and Working Capacity

**Direct answer:** A breakthrough curve is the outlet-concentration history of a fixed adsorption bed. It tells you three things at once: how long the bed works (breakthrough time), how efficiently it uses its carbon (steepness of the curve / width of the mass transfer zone), and how much pollutant the bed actually holds in service (working capacity — always less than the static maximum). The most common specification error is sizing a bed on total capacity and discovering, at breakthrough, that the bed was only half used.

---

## 1. What the curve is

Plot outlet concentration against time (or cumulative gas volume) for a fixed bed receiving a constant inlet concentration. The result is an S-shaped curve:

- **Flat early phase**: the adsorption front is still inside the bed; outlet ≈ 0.
- **Knee and rise**: the front reaches the outlet; concentration climbs.
- **Plateau**: outlet ≈ inlet; the bed is effectively saturated.

**Breakthrough time (BT)** is the time at which outlet concentration crosses the threshold — an emission limit, or a defined fraction of inlet concentration (5% is common). **Exhaustion** is when outlet ≈ inlet.

Two capacities hide in the geometry:

- **Maximum (static) capacity** = the area *above* the curve, integrated to exhaustion — everything the bed could hold.
- **Working capacity** = the amount adsorbed *up to breakthrough* — what the bed delivers before the outlet violates the limit.

Working capacity is always smaller than maximum capacity. How much smaller is precisely what the curve shape shows.

China's HJ 2026-2013 defines the engineering twin of working capacity: **dynamic adsorption capacity** (动态吸附量) — the average mass adsorbed per unit adsorbent mass when the outlet reaches the set value under constant temperature, pressure and flow (mg/g). The same standard requires adsorbent replacement when dynamic capacity falls to 80% of design.

## 2. The mass transfer zone (MTZ)

The bed is never uniformly saturated. A concentration transition band — the **mass transfer zone** — travels from inlet to outlet. Behind it the carbon is saturated; ahead of it the carbon is fresh; inside it, adsorption is happening *right now*.

- **Narrow MTZ** → steep S-curve → most of the bed is either saturated or fresh → high utilization, late and sudden breakthrough.
- **Wide MTZ** → shallow curve → a large fraction of the bed is "partly used" → early breakthrough, low utilization.

The MTZ widens — utilization falls — with:

| Factor | Effect on MTZ / breakthrough |
|---|---|
| Larger particle size | Widens (slower intraparticle diffusion) |
| Higher gas velocity | Widens (less contact time per unit bed) |
| Lower inlet concentration | Widens (smaller driving force) |
| Higher humidity | Widens (water competition slows uptake) |
| Shorter bed | Raises MTZ *fraction* of bed → lower utilization |
| Higher temperature | Narrower kinetically, but lower equilibrium capacity (§4 of the mechanism guide) |

This is the mechanistic reason behind the velocity caps in HJ 2026-2013 (granular beds <0.60 m/s, fiber <0.15 m/s, honeycomb <1.20 m/s): velocity and particle size directly control how much of the bed you actually use.

## 3. What shortens breakthrough time in practice

Breakthrough time for a given bed falls when any of these worsens:

1. **Humidity rise** — a documented effect direction; in low-concentration duty the single most common cause of premature breakthrough. Quantified examples: benzene capacity −55.9% from RH 0→90% on a hydrophilic carbon (2020 study); see the full numbers in [Adsorption Mechanism](activated-carbon-adsorption-mechanism.md).
2. **Inlet concentration rise** — higher loading consumes the bed faster even though working capacity per unit mass *rises*.
3. **Temperature rise** — lower equilibrium capacity; the bed holds less before breakthrough, even though kinetics improve.
4. **Bed aging** — capacity decays with cycles and time; HJ 2026-2013's 80% replacement rule operationalizes this.
5. **Channeling / maldistribution** — part of the bed sees most of the flow; measured breakthrough arrives earlier than the design curve. Causes include broken granules, dust accumulation, and poor inlet distribution.

## 4. Using the curve in design and procurement

- **Demand the breakthrough curve measured at your conditions** — concentration, humidity, temperature, velocity, bed depth. A curve from different conditions is a different curve. This is the single most valuable engineering document a supplier can provide, and it is rarely delivered unless asked for.
- **Compare carbons on working capacity, not iodine number.** Two carbons with identical iodine numbers can show meaningfully different working capacities in humid low-concentration duty (see the hydrophobized-carbon data in the mechanism article).
- **Size beds on working capacity with a utilization factor**, not on maximum capacity.
- **Treat the 80% dynamic-capacity threshold (HJ 2026-2013) as the replacement trigger** in audited Chinese installations, and document the reference test conditions.
- **Pilot-test when the duty is humid, low-concentration, or multi-component** — these are exactly the regimes where generic design margins fail. Multicomponent breakthrough (light VOC breaking through while heavy VOC is still adsorbed, or water displacement effects) cannot be predicted from single-component data alone.

## 5. Where the standard numbers stop

Two things this article deliberately does *not* state: typical MTZ lengths in meters and "capacity drop per degree" coefficients. We searched Chinese and international sources for both. The MTZ length depends on the full condition set and no citable design-handbook value was located in this research round (**NOT FOUND** — obtain from design handbooks such as adsorption-separation textbooks or vendor pilot data); per-degree coefficients do not exist as a universal rule (**NOT FOUND** — the literature contains only case-specific isotherm data).

**Bottom line:** the breakthrough curve is the honest biography of an adsorption bed. Sizing on total capacity overstates real performance by exactly the area between the working curve and the exhaustion point. Ask for the curve at your conditions, size on working capacity, and let the 80% rule time your replacements.

---

*Data classification: definitions and curve geometry are General technical knowledge; HJ 2026-2013 clauses (dynamic capacity definition, 80% rule, velocity caps) are Regulatory/standard values (High); humidity/kinetic effect directions are Literature values (High). MTZ length typical values and per-degree coefficients: NOT FOUND, flagged. Related: [Adsorption Mechanism](activated-carbon-adsorption-mechanism.md), [Adsorption Bed Design](../voc-engineering/voc-adsorption-bed-design.md), [Capacity Calculation](activated-carbon-capacity-calculation.md).*
