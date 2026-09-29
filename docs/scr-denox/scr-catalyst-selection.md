---
title: "How to Select an SCR Catalyst: Decision Guide"
description: "A step-by-step SCR catalyst selection guide: gas conditions, temperature window, geometry choice, volume sizing, poison audit and verification testing."
---

# How to Select an SCR Catalyst

> **Part of the [SCR DeNOx: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** SCR catalyst selection runs through six decisions in order:
(1) characterize the gas — temperature, NOx, SO₂, dust, moisture; (2) fix the
temperature window and required NOx removal; (3) choose geometry (plate vs
honeycomb) from dust and erosion; (4) size the catalyst volume with a
deactivation margin; (5) run a poison audit from the fuel and upstream process;
(6) verify by simulation testing on the actual gas. Skipping any step converts a
catalyst choice into a field problem.

## Step 1: Characterize the gas

| Parameter | Why it matters |
| --- | --- |
| NOx inlet and NO/NO₂ split | Sets required removal and NH₃ demand |
| Gas temperature at catalyst | Selects the catalyst formulation window |
| SO₂ / SO₃ | Drives bisulfate risk and SO₂→SO₃ oxidation limit |
| Dust concentration & particle size | Decides geometry and pitch |
| Moisture | Affects acid dew point downstream |
| O₂ | SCR needs oxygen present |

Typical conventional SCR operating window is 200–420 °C; below ~200 °C choose a
low-temperature formulation, and understand the bisulfate trade-off (see
[Low-Temperature SCR](scr-low-temperature-catalyst.md)).

## Step 2: Set the removal target

Design NOx removal of 80–95% is typical for permit-driven duties. Higher removal
needs more volume, tighter NH₃ control and cleaner gas. The NH₃/NOx molar ratio
operating range is about 0.8–1.05 — beyond 1.0 ammonia slip rises steeply.

## Step 3: Choose geometry

- **Plate** — wider pitch, better for high-dust and sticky ash; see [Plate vs Honeycomb](plate-vs-honeycomb-scr.md).
- **Honeycomb** — higher surface per volume, lower volume for the same activity; fine for low-dust gas.

Face velocity, channel pitch and erosion margin follow from the dust analysis
(see [Ash & Erosion](scr-ash-erosion.md)).

## Step 4: Size the volume

Volume follows from space velocity and required conversion, then a deactivation
margin is applied for the expected life (see
[Volume Calculation](scr-catalyst-volume-calculation.md)). Typical space velocity
range is 2,000–8,000 h⁻¹ depending on gas and target — a design value, not a
product guarantee.

## Step 5: Run the poison audit

The fuel and upstream process decide catalyst life:

- Alkali/alkaline-earth metals (biomass, waste) — see [Catalyst Poisoning](scr-catalyst-poisoning.md)
- SO₂ and ammonium bisulfate — see [Ammonia Slip Control](scr-ammonia-slip-control.md)
- Arsenic, phosphorus — fossil and some industrial fuels
- Silica fines — erosion

The same NOx target can need 20–40% more volume on a high-poisoning fuel.

## Step 6: Verify before commitment

Simulation testing on the actual flue gas (see [SCR Activity Testing](scr-activity-testing.md))
confirms conversion, SO₂ oxidation and pressure drop at the design conditions.
This is standard practice before large orders.

## When SCR is not the right choice

- Flue gas temperature far below the window with no reheating budget — evaluate SNCR or staging.
- Very high SO₃ with no upstream control — catalyst poisoning dominates economics.
- Variable fuel with unknown poison profile — resolve fuel security first.
- Space or pressure-drop constraints that no catalyst geometry satisfies.

## Related pages

- [SCR vs SNCR](scr-sncr-comparison.md) — technology-level choice
- [Reactor Positioning](scr-reactor-positioning.md) — where the catalyst sits in the duct
- [Reducing Agent Systems](scr-reducing-agent-systems.md) — NH₃/urea supply

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [Honeycomb SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/honeycomb-scr-catalyst/)
