# CO Catalyst Reactor and Bed Design: Sizing for Conversion and Pressure Drop

> **Part of the [CO Oxidation: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** A CO catalyst reactor is sized by three constraints acting together: the space velocity
needed for the target conversion, the pressure drop the fan or induced draft can afford, and the temperature
rise the bed can tolerate. Getting any one wrong produces a unit that either misses conversion, overloads the
fan, or overheats the catalyst.

## The sizing triangle

| Constraint | Design parameter | Failure mode |
| --- | --- | --- |
| Conversion | Space velocity (h⁻¹) = gas flow ÷ catalyst volume | Too high → CO breakthrough |
| Pressure drop | Bed depth, channel size, face velocity | Too high → fan overload, energy cost |
| Temperature rise | CO load, bed configuration | Too high → thermal deactivation |

## Space velocity and bed depth

Typical CO oxidation duties run at space velocities of 3,000–15,000 h⁻¹ depending on catalyst family and
inlet concentration. Higher CO concentrations mean more heat and often allow higher space velocity once the
bed is lit off, because the exotherm drives activity. The bed is usually shallow (0.3–1.0 m), arranged as a
single layer or stacked modules.

## Pressure drop management

Honeycomb geometries keep pressure drop low — a few hundred Pa per layer is typical. Design rules:

- Keep face velocity in the catalyst vendor's recommended range (commonly 1–3 m/s).
- Account for dust loading on the face; add upstream filtration where needed.
- Model the full duct system, not just the bed — elbows and dampers often exceed bed losses.

## Temperature rise and bed protection

CO oxidation releases about 283 kJ per mole of CO. A stream at 1% CO carries enough heat for roughly
80–90°C of adiabatic rise. Design responses:

- **Single-stage** — suitable when total rise keeps the bed inside its rated window.
- **Multi-stage with intercooling** — for concentrated streams; each stage handles part of the CO.
- **Heat recovery** — the rise is an asset when a heat exchanger or waste heat boiler follows the reactor.

## Mechanical details that matter

- **Module sealing** — bypass at module joints silently destroys conversion; specify sealing strips.
- **Thermal expansion** — the reactor shell and modules expand differently; flexible seals prevent gas
  bypass and module crushing.
- **Access for sampling** — inlet/outlet sampling ports for verification of conversion and light-off.

## Manufacturer perspective

We size CO reactors from the peak CO concentration — not the average — because process upsets are when
compliance is judged and when thermal damage happens. The adiabatic rise calculation at peak CO decides the
number of stages.

## Related articles

- [CO Catalyst Selection](co-catalyst-selection.md)
- [Light-Off Temperature](co-light-off-temperature.md)
- [Application Scenarios](co-application-scenarios.md)

[← Back to the CO Oxidation: The Complete Guide](index.md)

## Related products

- [CO Removal Catalyst](https://xuanbaoenvironment.com/products/co-removal-catalyst/)
- [Heating Tubes](https://xuanbaoenvironment.com/products/heating-tubes/)
