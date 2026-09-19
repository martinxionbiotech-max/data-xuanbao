# Managing the CO Oxidation Exotherm: Adiabatic Rise and Heat Recovery

> **Part of the [CO Oxidation: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** Every mole of CO oxidized releases roughly 283 kJ of heat — enough to raise a 1% CO stream
by 80–90°C adiabatically. The exotherm is both the main operating risk (overheating, sintering) and the main
opportunity (free heat for preheating or export). Design starts by computing the adiabatic temperature rise
at the peak CO concentration.

## Computing the rise

For air-like streams, the adiabatic temperature rise is approximately:

```
ΔT ≈ 9 × C_CO (°C, with C_CO in % by volume)
```

So 1% CO ≈ +90°C, 2% ≈ +180°C, and a 5% stream carries +450°C — beyond what any commercial catalyst bed
survives. This single number decides staging, dilution and materials.

## When the rise is a risk

- **Concentrated streams** — above roughly 2–3% CO, the bed can exceed its rated temperature and sinter.
- **Flow interruptions** — if the fan trips while CO-rich gas remains, the static bed can overheat locally.
- **Cold-start cycles** — preheating a bed that then sees high CO can overshoot on ignition.

Mitigations: multi-stage beds with intercooling or dilution air, temperature interlocks on the fan and fuel
supply, and catalyst formulations rated for higher temperature excursions.

## When the rise is an asset

- **Preheating the inlet gas** — a feed/effluent heat exchanger lifts cold inlet gas to light-off using the
  outlet stream.
- **Steam or hot water export** — a waste heat boiler or economizer downstream converts the rise into
  process heat.
- **Self-sustaining operation** — above roughly 1 g/Nm³ equivalent concentration, the reaction pays for its
  own preheat at steady state.

## Bed thermal design rules

- Calculate the rise at **peak** CO, not average.
- Verify the **maximum bed exit temperature** against the catalyst's thermal rating.
- Add **high-temperature alarms** and, on large systems, a quench or bypass path.
- In staged designs, size intercooling so no stage exceeds its rating even if one stage underperforms.

## Manufacturer perspective

The exotherm calculation is the first step in any CO project — it sets the number of stages, the materials
and the heat recovery value. We always ask for the CO range over normal operation, including upset peaks,
because those peaks size the safety system.

## Related articles

- [CO Catalyst Selection](co-catalyst-selection.md)
- [Reactor Bed Design](co-reactor-bed-design.md)
- [Application Scenarios](co-application-scenarios.md)

[← Back to the CO Oxidation: The Complete Guide](index.md)

## Related products

- [CO Removal Catalyst](https://xuanbaoenvironment.com/products/co-removal-catalyst/)
- [Heating Tubes](https://xuanbaoenvironment.com/products/heating-tubes/)
