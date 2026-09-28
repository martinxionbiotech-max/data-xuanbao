---
title: "CO Removal on Sintering Machines"
description: "CO oxidation catalyst application on sintering machines: operating conditions, catalyst arrangement and documented field test results."
---

# CO Control on Sintering Machines: The Hardest CO Duty

> **Part of the [CO Oxidation: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** Sintering machine flue gas is the most demanding CO oxidation application in industry:
large flows, moderate temperature, and CO concentrations that swing from hundreds to thousands of ppm within
hours as the sinter bed progresses. Successful control requires a catalyst sized for the peak CO, placed
where temperature and dust are manageable, and tolerant of SO₂ and moisture.

## Why sintering CO is difficult

- **Concentration swings** — CO tracks the combustion state of the sinter bed; charge cycles and upset
  operation produce order-of-magnitude swings.
- **Large flow** — a single sintering line can move millions of Nm³/h; even a small unit dwarfs most
  process-gas duties.
- **Moderate temperature** — flue gas after dedusting often sits near or below light-off, forcing
  preheating or heat recovery decisions.
- **Co-pollutants** — SO₂, moisture and residual dust arrive with the CO.

## System architecture

The typical layout is dedusting → temperature management → CO oxidation → stack (or further treatment):

1. **Dedusting** — ESP or bag filter protects the catalyst face from blinding.
2. **Temperature management** — if the gas is below light-off, heating-tube catalysts or heat exchange
   with hot wind boxes lift the temperature.
3. **CO oxidation** — honeycomb catalyst bed sized for the peak CO with exotherm control.
4. **Optional SCR** — where NOx also requires control, SCR follows the CO stage.

## Sizing rules for sintering duty

- Size for the **peak** CO, not the average — the compliance test can come at any hour.
- Compute the **adiabatic rise at peak CO**; single-stage is acceptable only if the bed stays inside its
  thermal rating.
- Add **dust margin** — even after dedusting, residual ash accumulates; choose pitch and face velocity
  accordingly.
- Plan **bypass or preheat** for cold starts and low-load operation.

## Documented field test result

| Item | Detail |
| --- | --- |
| Result | CO: 1,499 ppm → 18 ppm |
| Data type | Field Test Result |
| Test date | 2022-08-23, as recorded in the original field test report |
| Derived value | Removal efficiency ≈ 98.8% |
| Source | [Sintering Machine CO Removal — Field Test](https://xuanbaoenvironment.com/case-studies/sintering-machine-co-removal/) on the main site |
| Completeness | The published record does not include gas flow, operating temperature, O₂, catalyst volume or space velocity |

**Engineering interpretation:** the test shows a four-digit ppm inlet brought below 20 ppm on a real
sintering stream — but sustained performance depends on temperature stability and peak management, and the
record lacks the supporting conditions needed to generalize the number. Plants should measure the full CO
range over normal operation before sizing.

## Manufacturer perspective

Sintering duty is where our field experience concentrates: we size from measured CO profiles across charge
cycles, not from a single design point, and we prefer pilot testing with the plant's real gas before full
installation.

## Related articles

- [Exotherm Management](co-exotherm-management.md)
- [Reactor Bed Design](co-reactor-bed-design.md)
- [Light-Off Temperature](co-light-off-temperature.md)

[← Back to the CO Oxidation: The Complete Guide](index.md)

## Related products

- [CO Removal Catalyst](https://xuanbaoenvironment.com/products/co-removal-catalyst/)
- [Heating Tubes](https://xuanbaoenvironment.com/products/heating-tubes/)
