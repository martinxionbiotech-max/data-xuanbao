---
title: "CO Oxidation Application Scenarios: Sintering, Incineration and Safety"
description: "The four CO oxidation application scenarios: sintering machines, waste incineration, furnace exhaust and CO safety duty."
---

# CO Oxidation Application Scenarios: Sintering, Incineration and Beyond

> **Part of the [CO Oxidation: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.
>


**Direct answer:** CO oxidation catalysts appear wherever CO must be removed from
oxygen-containing gas below the temperature where thermal oxidation is economical.
The four largest scenarios are sintering machine exhaust, waste incineration,
industrial furnace and kiln off-gas, and catalytic combustion tail gas — each with
distinct gas compositions and therefore distinct catalyst requirements.

## Sintering and pelletizing exhaust

Sintering lines emit large flows at moderate temperature (typically 120–200°C in the
duct after the ESP, subject to site conditions) with CO in the thousands of ppm range,
plus SO₂, moisture and residual dust.

- CO concentrations are high enough that reaction exotherm matters for reactor design.
- SO₂ and moisture are the main activity threats.
- Flow rates are enormous — pressure drop per metre of catalyst bed is a first-order
  economic parameter.
- Many plants combine CO oxidation with SCR or desulfurization in series, so the CO
  unit must tolerate upstream variability.

## Waste and medical waste incineration

Incineration flue gas carries CO spikes that reflect incomplete combustion events —
the CO level itself is a combustion-quality signal.

- Duty is highly dynamic: CO swings with batch charging.
- HCl, SO₂, heavy metals and moisture are all present; the catalyst sits behind
  appropriate gas cleaning.
- Temperature is usually sufficient for light-off once the boiler design provides
  it; reheating may be needed at low load.

### Medical waste incineration — deeper look

Medical waste units combine the worst of thermal cycling with an aggressive gas
chemistry.

- **Temperature:** after gas cleaning the stream is often 150–220°C — near the
  light-off margin, so pre-heating or a low-light-off formulation is usually needed.
- **CO fluctuation:** batch charging produces surges from the hundreds to the
  thousands of mg/Nm³; size for the peak and verify the exotherm stays safe.
- **Poisons:** residual HCl after the scrubber and heavy-metal fume attack the
  catalyst; chloride tolerance and upstream cleaning define the catalyst life.
- **Sizing note:** the documented medical-waste result in the Evidence Registry
  (XB-EV-002) shows high single-pass conversion, but the test record does not publish
  flow, temperature or O₂ — so the duty must be re-sized on the customer's own
  measured gas, not copied from the result.

## Industrial furnaces, kilns and dryers

Furnaces, rotary kilns and drying lines vent CO from incomplete fuel burnout.

- Streams are smaller and often intermittent.
- Temperature varies with batch operation — light-off margin and pre-heating matter.
- Where fuel is switched seasonally, gas composition shifts; sizing should cover the
  worst-case fuel.

### Gas-fired boilers and kilns — deeper look

Gas-fired units run cleaner than coal or incineration but have their own CO pattern.

- **Temperature:** gas burners hold flue-gas temperature relatively stable, but
  low-load and start-up conditions can fall below light-off.
- **CO fluctuation:** CO tracks air-fuel ratio upsets — a briefly rich burner can
  spike CO sharply; a polishing catalyst must ride these transients.
- **Poisons:** low SO₂ and dust on natural gas means longer catalyst life, but
  moisture from combustion is always present; condensation protection still matters.
- **Sizing note:** the sizing input is the peak CO during burner upsets, not the
  steady-state average, because compliance can be tested during a transient.

## Coking flue gas

Coke-oven and coking by-product gas streams add complexity beyond a simple furnace
vent.

- **Temperature:** coking flue gas temperature varies with the battery operating
  cycle and heat-recovery design; confirm the minimum continuous temperature at the
  catalyst face.
- **CO fluctuation:** CO level shifts with oven charging and pushing; treat as a
  dynamic duty, not a steady stream.
- **Poisons:** coking gas can carry sulfur species (H₂S, SO₂), tars and condensables
  that foul or poison the catalyst — upstream tar removal and sulfur control are
  prerequisites.
- **Sizing note:** a coking stream is sized like a sintering stream in miniature —
  poisons and duty pattern dominate, and the catalyst must sit behind effective
  particulate and tar removal.

## Catalytic combustion tail gas

Catalytic combustion units can emit small residual CO at low temperature. A
polishing CO catalyst downstream guarantees compliance across operating conditions.

## Enclosed-space and emergency duty

In enclosed environments (garages, tunnels, industrial halls) CO removal is a safety
function rather than an emissions function. Heating-tube catalyst systems with
electric pre-heating provide continuous low-temperature CO abatement.

## Sizing by scenario

| Scenario | Temperature | Key challenges |
| --- | --- | --- |
| Sintering exhaust | Moderate | SO₂, moisture, huge flow |
| Medical waste incineration | Variable, near light-off | HCl, metals, dynamic load |
| Gas boiler / kiln | Stable | Cold starts, burner-transient CO |
| Coking flue gas | Variable | Sulfur, tars, duty swings |
| Furnace / kiln off-gas | Intermittent | Cold starts, fuel changes |
| Catalytic combustion tail | Low | Low-temperature light-off |
| Enclosed space | Ambient | Continuous safety duty |

## Documented field results

Two scenarios have documented field-test evidence, registered in the
[Evidence Registry](../methodology/evidence-registry.md):

- **Sintering machine CO (XB-EV-001):** CO 1,499 ppm → 18 ppm (2022-08-23) — see
  [Sintering Machine CO Control](co-sintering-machine.md).
- **Medical waste incinerator CO (XB-EV-002):** CO 11,224.2 mg/Nm³ → 16.2 mg/Nm³
  (2023-03-20) — see [Waste Incineration CO Control](co-waste-incineration.md).

Both are **Field Test Results** and **Partially recorded** — the operating conditions
behind the numbers are not published, so neither result generalizes to other plants.
The coking and gas-boiler scenarios have no published field evidence and are described
above from engineering principles only.

## Manufacturer perspective

Scenario dictates the guardrails, not the catalyst chemistry alone. We size from the
actual stream data per unit — temperature profile, CO range, moisture, SO₂ and duty
pattern — because the same CO removal target leads to different designs in each
scenario.

## Related articles

- [CO Catalyst Selection](co-catalyst-selection.md)
- [Light-Off Temperature](co-light-off-temperature.md)

[← Back to the CO Oxidation: The Complete Guide](index.md)

## Related products

- [CO Removal Catalyst](https://xuanbaoenvironment.com/products/co-removal-catalyst/)
- [Heating Tubes](https://xuanbaoenvironment.com/products/heating-tubes/)
