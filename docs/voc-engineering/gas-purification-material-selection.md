---
title: "Gas Purification Material Selection: A Cross-Family Guide"
description: "Gas purification material selection across activated carbon, zeolite molecular sieves, catalysts and impregnated media: pollutant-to-material mapping and decision rules."
---

# Gas Purification Material Selection: A Cross-Family Guide

> **Part of the [VOC Treatment Engineering: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** The purification material follows the pollutant class. Activated
carbon handles a broad range of organics by physisorption; zeolite molecular sieves
handle selective adsorption, drying and high-humidity VOC duty; precious-metal and
non-precious catalysts destroy CO and VOCs by oxidation; SCR catalysts reduce NOx;
impregnated carbon chemisorbs acid gases and ammonia. Most real exhaust streams need
more than one material in sequence — the question is the order and the duty split.

## The pollutant-to-material map

| Pollutant class | First-line material | Mechanism | Notes |
| --- | --- | --- | --- |
| VOC (general, dry stream) | Activated carbon | physisorption | inlet <40°C, RH control, bed <83°C |
| VOC (humid, ketone-rich) | Zeolite (ZSM-5 type) | hydrophobic adsorption | regenerable at 200–350°C |
| CO | Precious-metal honeycomb | catalytic oxidation | 150–600°C window |
| NOx | SCR catalyst (V-Mo-Ti) | selective catalytic reduction | 150–420°C, ammonia injection |
| Acid gases (H₂S, SO₂) | Impregnated activated carbon | chemisorption | single-use or regenerable grades |
| Ammonia, amines | Impregnated activated carbon | chemisorption | acid-impregnated grades |
| Moisture | 3A / 4A molecular sieve | selective adsorption | regeneration required |
| Odor (mixed, low level) | Coconut-shell carbon | physisorption | high iodine grades |

## Decision rule 1: destroy or transfer

- **Destroy** when the pollutant has no recovery value and the temperature budget
  exists: catalysts for CO/VOC/NOx.
- **Transfer** (adsorb) when concentration is low, flow is intermittent, or the
  material has reuse value.
- The full route logic is in
  [Adsorption vs Catalytic Oxidation](adsorption-vs-catalytic-oxidation.md).

## Decision rule 2: humidity splits carbon and zeolite

Above roughly 50% relative humidity, water competes with VOCs for carbon pores;
hydrophobic zeolites keep working (see
[Zeolite vs Activated Carbon](zeolite-vs-activated-carbon.md)). High-humidity streams
either need preconditioning (cooling/dehumidification) or a zeolite bed.

## Decision rule 3: concentration and flow set the architecture

- Low concentration, high flow → concentration wheel + oxidizer.
- Medium concentration, continuous → direct catalytic oxidation.
- Low flow, recovery value → adsorption with regeneration or disposal.

## Decision rule 4: temperature windows are hard constraints

- Carbon adsorption: inlet below 40°C; bed below 83°C (HJ 2026-2013).
- VOC precious-metal oxidation: light-off 180–250°C.
- SCR: 150–420°C; below the window activity collapses, above it selectivity falls.
- CO oxidation: 150–600°C.
- Zeolite regeneration: 200–350°C.

Each material family has a window; the exhaust temperature at the chosen reactor
position must fall inside it, or the position must move.

## The selection workflow

1. List pollutants with concentrations and the emission limit.
2. Classify each pollutant (VOC class, CO, NOx, acid gas, odor).
3. Read the exhaust conditions: temperature, humidity, O₂, dust, flow pattern.
4. Map each pollutant to its first-line material (table above).
5. Sequence the materials: dedust → adsorb/destroy → polish, in that order.
6. Verify the temperature windows at each stage; adjust position or precondition.
7. Test on the actual stream where the duty is critical.

## Related articles

- [How to Select Activated Carbon](../activated-carbon/activated-carbon-selection.md)
- [Molecular Sieve Type Selection](../molecular-sieves/molecular-sieve-type-selection.md)
- [How to Select a VOC Catalyst](../voc-catalysts/voc-catalyst-selection.md)
- [CO Catalyst Selection](../co-oxidation/co-catalyst-selection.md)
- [SCR Plate vs Honeycomb](../scr-denox/plate-vs-honeycomb-scr.md)
