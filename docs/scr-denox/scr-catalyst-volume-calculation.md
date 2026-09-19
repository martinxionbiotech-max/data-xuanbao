# SCR Catalyst Volume Calculation: Activity, Area Velocity and Life Management

> **Part of the [SCR DeNOx: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** SCR catalyst volume is calculated from the required NOx conversion, the flue gas flow, the
operating temperature and the catalyst's activity constant K, using the standard area-velocity equation. The
result is multiplied by a deactivation margin that reflects poisoning, erosion and regeneration strategy, so
the reactor meets its emission target at end-of-life, not just at commissioning.

## The core equation

The industry standard relates conversion to catalyst volume through:

```
K / AV = −ln(1 − η)
```

Where:

- **K** — catalyst activity constant (m/h), measured under reference conditions.
- **AV** — area velocity (m/h) = flue gas flow ÷ catalyst geometric surface area.
- **η** — NOx conversion (fraction).

For a given conversion target, higher AV (less catalyst) requires proportionally higher K — so the activity
number and the volume number are the same decision seen from two directions.

## Inputs the calculation needs

- **Gas flow** — actual wet volume at reactor temperature, not standard dry volume.
- **Inlet and target NOx** — the design conversion, plus the ammonia/NOx stoichiometry limit.
- **Operating temperature** — K is temperature-dependent; a 20°C lower average temperature can cost
  10–20% more volume.
- **Reference K value** — quoted by the catalyst supplier at defined gas composition, velocity and
  temperature.
- **Deactivation factor** — the end-of-life activity as a fraction of fresh activity, typically 0.5–0.8
  depending on fuel, dust and regeneration plans.

## Managing layers and the spare position

A standard reactor is designed with an initial layer plus one empty spare layer position:

- Year 0 — initial catalyst, sized for the target at end-of-life of the initial fill.
- Year N — one spent layer replaced, moved into the spare position, extending life.
- The spare position allows replacement without a reactor shutdown of extended duration.

## Sizing traps to avoid

- **Sizing on the design case only** — verify the low-load, low-temperature case; it often demands more
  volume than full load.
- **Ignoring fuel changes** — a switch to high-arsenic or high-alkali coal erases the original margin.
- **Not reserving for AIG imperfection** — a velocity distribution of ±15% means parts of the layer work
  harder; add distribution margin.
- **Using fresh K for end-of-life duty** — the legal guarantee is at end-of-life; size for that.

## Manufacturer perspective

We size from the fuel and flue gas analysis, the measured velocity distribution and the outage window —
never from a catalogue value alone. A volume calculation is only as good as the K value behind it, and we
quote K with its test conditions in writing.

## Related articles

- [SCR Activity Testing](scr-activity-testing.md)
- [SCR Catalyst Replacement](scr-catalyst-replacement.md)
- [Plate vs Honeycomb SCR](plate-vs-honeycomb-scr.md)

[← Back to the SCR DeNOx: The Complete Guide](index.md)

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [Honeycomb SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/honeycomb-scr-catalyst/)
