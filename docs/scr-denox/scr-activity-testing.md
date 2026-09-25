---
title: "SCR Catalyst Activity Testing: K/K0 and Laboratory Evaluation"
description: "How SCR catalyst activity is tested: the K/K0 activity ratio, laboratory evaluation methods and field performance verification."
---

# SCR Catalyst Activity Testing: From Lab Sample to Field Verification

> **Part of the [SCR DeNOx: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.
>


**Direct answer:** SCR catalyst activity is quantified as the NOx conversion achieved
at defined temperature, space velocity and NH₃/NOx ratio — expressed as activity K
(area or volume based). Testing happens in three tiers: laboratory characterization,
bench-scale simulation of the actual gas, and in-situ field verification.

## What "activity" means

Activity is not a single number. It is a curve: conversion versus temperature at fixed
space velocity and molar ratio. The useful engineering value is the temperature at
which a required conversion is met under the customer's actual gas conditions — not a
catalogue claim at ideal conditions.

## The three tiers

**Laboratory characterization.** Fresh catalyst is tested under standard gas
(defined NOx, NH₃, O₂, H₂O, SO₂ levels) across the operating temperature range. This
establishes the reference activity curve for the product type.

**Simulation testing.** The customer's actual flue gas composition — including SO₂,
dust, moisture and temperature profile — is reproduced on a bench reactor with
representative gas velocity. This is the tier that separates a good selection from a
mismatch, especially on fuels with unusual poisons.

**Field verification.** After installation, conversion and slip are measured across
the reactor at stable load. Baseline values are recorded for trend comparison over
the catalyst's life.

## Activity K — the standard metric

Catalyst activity is commonly expressed as K (m/h), from the first-order rate
equation:

K = −AV × ln(1 − η)

where AV is the area velocity (gas flow per catalyst geometric surface area, m/h) and
η the fractional NOx conversion. K declines over the catalyst's life; the ratio of
current K to initial K (K/K₀) is the standard deactivation index. Replacement or
regeneration planning typically triggers at K/K₀ of roughly 0.6–0.7, subject to plant
requirements.

## Testing conditions that change the answer

- **Space velocity:** doubling the space velocity at constant temperature cuts
  conversion roughly in proportion to the residence time change.
- **NH₃/NOx ratio:** tests below the stoichiometric ratio understate achievable
  conversion; tests far above it inflate slip.
- **SO₂ and H₂O:** both compete for sites and shift the effective activity, which is
  why simulation with the real gas matters.
- **Sample aging:** fresh-sample data cannot predict end-of-life performance;
  deactivation rates must come from operating history on similar fuels.

## Manufacturer perspective

We provide activity curves and the test conditions behind them, and we strongly
recommend simulation testing with the customer's own gas before large orders. Data
with hidden test conditions is worse than no data — it leads to undersized reactors.

## Related articles

- [SCR Regeneration](scr-catalyst-regeneration.md)
- [SCR Replacement](scr-catalyst-replacement.md)
- [SCR Catalyst Poisoning](scr-catalyst-poisoning.md)

[← Back to the SCR DeNOx: The Complete Guide](index.md)

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [Honeycomb SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/honeycomb-scr-catalyst/)
