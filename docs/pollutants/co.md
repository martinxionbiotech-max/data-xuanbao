---
title: "CO Pollutant Profile: Properties, Sources and Treatment"
description: "Carbon monoxide (CO) as an industrial pollutant entity: sources, physical properties, hazard characteristics, treatment challenges and the catalysts and systems that oxidize it."
---

# CO (Carbon Monoxide): Pollutant Profile

**Direct answer:** Carbon monoxide is a toxic, flammable combustion intermediate
formed wherever carbon burns with insufficient oxygen or mixing. It is removed by
catalytic oxidation to CO₂ — a strongly exothermic reaction whose practical design
is dominated by light-off temperature, oxygen availability and exotherm control.

## Definition

CO is a colorless, odorless gas; molar mass 28.01 g/mol; boiling point −191.5 °C
(Literature Value). It binds hemoglobin far more strongly than oxygen, which is why
emission and workplace limits treat it as a primary toxic hazard. In flue gas it
indicates incomplete combustion — either oxygen starvation, poor mixing or quenched
combustion.

## Industrial sources

- Sintering machines and pellet plants (iron & steel)
- Waste incineration and medical waste incineration
- Coke ovens and gas flares
- Catalyst regeneration vents and FCC units
- Incomplete combustion in boilers under load swings
- Charcoal/activated carbon kilns and pyrolysis off-gas

## Treatment challenges

1. **Light-off temperature** — catalysts only work above their light-off point (T50/T90); cold starts and low-load operation may fall below it.
2. **Exotherm** — CO oxidation releases heat; concentrated CO streams can raise bed temperature hundreds of degrees and must be managed by staging, dilution or heat recovery.
3. **Poisoning** — sulfur, halogens, moisture and metal fumes degrade oxidation catalysts; upstream gas cleaning defines catalyst life.
4. **Peak vs average** — compliance tests can occur at peak CO; sizing to average fails.

## Suitable materials

- **Precious-metal catalysts (Pt, Pd)** — lowest light-off, highest activity; see [CO Catalyst Selection](../co-oxidation/co-catalyst-selection.md).
- **Base-metal catalysts (hopcalite-type, transition metal oxides)** — lower cost, higher light-off, poison-sensitive.
- Activated carbon does not oxidize CO at industrial scale; it is not a CO treatment material.

## Suitable technologies

- **Catalytic oxidation** — the default route for ppm-to-low-percent CO; see the [CO Oxidation Complete Guide](../co-oxidation/index.md).
- **Thermal oxidation** — for concentrated streams where the heat is usable.
- **Process integration** — sintering machine flue gas recirculation combined with catalytic oxidation.

## Operating conditions that matter

- Inlet CO concentration and its peak/transient behavior
- Gas temperature vs catalyst light-off (T50/T90)
- Oxygen content — stoichiometric requirement is 0.5 mol O₂ per mol CO, with excess for kinetics
- Space velocity and bed residence time
- Dust, SO₂, HCl, moisture load

*Data type:* ranges quoted in the linked pages are Typical Value engineering references unless
a specific field test is cited. See [Data Classification](../methodology/data-classification.md).

## Testing

- Catalyst screening by light-off curve measurement — [Light-Off Temperature: T50 and T90](../co-oxidation/co-light-off-temperature.md)
- Activity verification on actual gas — [Catalyst Activity Evaluation](../testing/catalyst-activity-evaluation.md)
- Field evidence examples: [Sintering Machine CO Removal](../co-oxidation/co-sintering-machine.md) and [Waste Incineration CO](../co-oxidation/co-waste-incineration.md) (both Field Test Results with documented dates)

## Limitations

- Below light-off temperature the catalyst does nothing; supplemental heating or bypass strategy required.
- High-dust gas fouls the bed; dedusting is normally mandatory.
- Very concentrated CO requires staged oxidation or thermal route; a single catalyst bed cannot absorb unlimited exotherm.
- Halogen-containing streams need halogen-tolerant formulations or pre-scrubbing.

## Related materials

- [CO Oxidation Catalysts](../co-oxidation/index.md)

## Related processes

- [CO Reactor Bed Design](../co-oxidation/co-reactor-bed-design.md)
- [CO Exotherm Management](../co-oxidation/co-exotherm-management.md)
- [CO Catalyst Deactivation](../co-oxidation/co-catalyst-deactivation.md)
