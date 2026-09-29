---
title: "SCR Activity Testing: Laboratory Powder vs Field Catalyst Performance"
description: "Why laboratory SCR activity test results differ from field performance: powder vs whole catalyst, GHSV differences, field decay curves and sampling representativeness."
---

# Laboratory vs Field SCR Activity: Reading the Gap Between Test and Service

> **Part of the [Testing & Analysis: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** A laboratory SCR activity number does not transfer directly to a
full-size reactor. The lab usually tests crushed powder at high surface exposure and
low flow per unit mass, under a fixed synthetic gas — while the field operates a
full honeycomb or plate module at much higher gas velocity, on real flue gas that
contains poisons and dust. The gap between the two is systematic, not random, and a
competent sizing process treats the lab value as a reference point, not a guarantee.

## Why the two measurements differ

Four differences dominate, and each acts in the same direction — laboratory results
are generally more favourable than field performance.

- **Powder vs whole catalyst.** Crushing a catalyst into powder exposes internal
  pore surface that is partly inaccessible in the formed monolith. Powder activity
  therefore overstates what a full block delivers.
- **Space velocity.** Laboratory rigs commonly run lower space velocities (longer
  contact time) than a production reactor, where gas velocity is set by pressure-drop
  and footprint economics.
- **Gas composition.** The lab runs a clean synthetic gas; the field gas carries
  SO₂, moisture, dust and trace poisons that progressively suppress activity.
- **Transient vs steady.** A lab test is a snapshot at one set of conditions; the
  field sees load swings, temperature drift and deactivation over months.

## What laboratory activity is good for

Despite the gap, the lab is indispensable for what it can control:

- **Comparative ranking** — screening formulations under identical conditions.
- **Fresh-sample reference** — establishing the baseline activity K₀ for a product.
- **Kinetic characterisation** — isolating the effect of a single variable (SO₂
  concentration, temperature) on conversion.
- **Quality control** — confirming a delivered batch matches the type specification.

## What laboratory activity cannot do

- It cannot predict end-of-life performance — deactivation rates come from operating
  history on similar fuels, not from a fresh-powder test.
- It cannot capture poison accumulation, erosion or ABS fouling, all of which are
  field phenomena.
- It cannot substitute for simulation testing on the customer's actual gas.

## Field decay curves vs laboratory snapshots

The field picture is a **decay curve** — activity K (or K/K₀) plotted against
operating time — not a single point. The laboratory provides the curve's starting
point; the field provides its slope. Two catalysts can start at the same K₀ and
diverge sharply after a year depending on fuel sulphur, alkali content and dust load.

> *Data type:* the activity-decline guidance below is Typical Value engineering
> reference; K/K₀ trigger levels are Design Values and are set per plant. See
> [Data Classification](../methodology/data-classification.md).

## Sampling representativeness

A field activity measurement is only as good as the sample behind it:

- **Location.** Sample across the reactor cross-section at multiple traverse points;
  a single centre-point sample misses the maldistribution that is often the real
  problem.
- **Timing.** Sample at stable load, not during a transient.
- **Representative gas.** The activity test gas must match the measured field gas,
  or the comparison is meaningless.
- **Records.** Log temperature, flow, O₂, NH₃/NOx ratio and dust at the sampling
  moment — an activity number without these cannot be trended.

## How activity numbers feed sizing margin

A defensible sizing uses the lab value only after applying a series of conservative
steps:

1. **Confirm the gas** — measured field composition, not an assumption.
2. **Run simulation** — reproduce the real gas on a bench reactor to get a
   condition-corrected activity.
3. **Apply deactivation margin** — size for the expected end-of-life activity
   (K/K₀ at replacement trigger), not the fresh value.
4. **Add distribution margin** — allow for non-ideal flow, erosion and fouling over
   the campaign.

> **Key Engineering Point:** The lab number is the *start* of the sizing, not the
> answer. The end-of-life activity — after deactivation and maldistribution — is what
> determines whether a reactor still meets the emission limit at the end of its
> campaign.

## Manufacturer perspective

We report laboratory activity together with its test conditions, and we treat the
lab result as a screening reference. For any non-standard stream we recommend
simulation testing with the customer's real gas before committing catalyst volume.
A number without its conditions — powder or full-block, space velocity, gas
composition — cannot support a sizing decision.

## Related articles

- [SCR Catalyst Activity Testing](../scr-denox/scr-activity-testing.md) — the three-tier testing model and the K metric.
- [Flue Gas Sampling](flue-gas-sampling.md) — traverse sampling and sample handling.
- [Reading Test Reports](reading-test-reports.md) — conditions and normalization.
- [SCR Catalyst Volume Calculation](../scr-denox/scr-catalyst-volume-calculation.md)

[← Back to the Testing & Analysis: The Complete Guide](index.md)

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [Honeycomb SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/honeycomb-scr-catalyst/)
