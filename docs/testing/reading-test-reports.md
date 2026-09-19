# Reading Test Reports: The Conditions Section Is the Report

> **Part of the [Testing & Analysis: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** A test report's headline number — conversion, K value, capacity — means nothing without
its conditions: gas composition, temperature, space velocity, sample history and test standard. The
professional habit is to read the conditions section first and treat every number as a pair: value plus
context. Reports without stated conditions are marketing material.

## The mandatory context list

Any performance number needs, at minimum:

- **Gas composition** — species and concentrations, including H₂O and O₂; for SCR: NOx, NH₃, SO₂, and
  the NO₂/NOx ratio.
- **Temperature** — measured where, and held how steadily.
- **Flow / space velocity** — gas flow per catalyst volume or surface.
- **Sample description** — fresh, aged, regenerated; core, coupon or full module; from which layer and
  position.
- **Test standard** — which method was followed (ISO, GB, ASTM, in-house with stated procedure).

## Numbers that mislead without context

- **"99% conversion"** — at what inlet concentration? Against what species mix? High conversion at high
  inlet says more than the same number at trace inlet.
- **"T90 = 170°C"** — in dry clean gas or humid sulfur-bearing gas? The difference can be 50°C.
- **"Iodine number 1,000"** — a quality indicator, not a performance prediction for your specific VOC.
- **"K = 42 m/h"** — the industry reference point; the number alone cannot be compared across suppliers
  unless conditions match.

## How to compare two reports

1. Align the conditions first — if temperatures or compositions differ, normalize or discard the
   comparison.
2. Check sample age and history — an aged sample's K is not comparable to a fresh sample's.
3. Verify the calculation — conversion, AV and K must be internally consistent (K = −AV × ln(1−η)).
4. Ask for raw data — a single summary number hides scatter; raw curves show stability.

## Red flags in reports

- No gas composition stated.
- Test temperature outside your application range.
- "Typical values" without test date, batch or traceability.
- Sample described only as "catalyst" — which product, which batch, which history?
- Conversion quoted without inlet concentration.

## Manufacturer perspective

We publish conditions alongside every performance claim and provide raw data on request. When customers
bring competitor reports, we compare them on the conditions first — that is where claims usually
collapse.

## Related articles

- [Catalyst Activity Evaluation](catalyst-activity-evaluation.md)
- [Laboratory Characterization](lab-characterization-methods.md)
- [Flue Gas Sampling](flue-gas-sampling.md)

[← Back to the Testing & Analysis: The Complete Guide](index.md)

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [CO Removal Catalyst](https://xuanbaoenvironment.com/products/co-removal-catalyst/)
- [Platinum VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/platinum-catalyst/)
