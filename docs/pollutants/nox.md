---
title: "NOx Pollutant Profile: Properties, Sources and Treatment"
description: "Nitrogen oxides (NOx) as an industrial pollutant entity: what NO and NO2 are, their sources, physical properties, treatment challenges and the materials and technologies that remove them."
---

# NOx (Nitrogen Oxides): Pollutant Profile

**Direct answer:** NOx is the collective term for nitric oxide (NO) and nitrogen
dioxide (NO₂) — acid-forming, oxidizing combustion gases. NO dominates at the
flame, NO₂ forms downstream by oxidation. NOx is removed either by reduction to
N₂ (SCR / SNCR, the standard industrial routes) or by absorption routes, and its
treatment is dominated by temperature window, sulfur content and dust load.

## Definition

- **NO** — nitric oxide, colorless, poorly water-soluble, the main species at combustion temperature.
- **NO₂** — nitrogen dioxide, reddish-brown, water-reactive (forms nitric acid), toxic; the species most emission limits are expressed in terms of.
- Emission regulations generally state limits as NOx, calculated as NO₂ equivalents.

## Industrial sources

- Coal-, oil- and gas-fired power boilers and industrial boilers
- Cement kilns and lime kilns
- Glass melting furnaces
- Steel: sintering machines, coke ovens, reheating furnaces
- Waste incineration and biomass combustion
- Nitric acid production and nitration process vents

## Relevant properties (Literature Value)

| Property | NO | NO₂ |
| --- | --- | --- |
| Molar mass | 30.01 g/mol | 46.01 g/mol |
| Boiling point | −151.8 °C | 21.2 °C |
| Water solubility | Low | Reactive with water (HNO₃ formation) |
| Corrosivity | Moderate | High in humid gas (acid dew point) |

NO₂ in humid flue gas condenses as nitric acid, which sets the acid-dew-point constraint for
low-temperature equipment downstream of any NOx device.

## Treatment challenges

1. **No single pollutant** — the NO/NO₂ ratio changes with temperature, oxygen and residence time; test and design for both.
2. **Temperature window** — SCR catalysts work in a defined window (typical 200–420 °C for conventional V-Mo-Ti); below it ammonium bisulfate deposits, above it NH₃ oxidizes back to NOx.
3. **Catalyst poisons** — SO₂ (forming sulfates and ammonium bisulfate), alkali and alkaline-earth metals, arsenic, phosphorus; each fuel carries its own poison profile.
4. **Ammonia management** — the reducing agent itself is regulated; slip must stay controlled.
5. **Dust and erosion** — high-dust gas wears catalyst channels and plugs pitch.

## Suitable materials

- **V-Mo-Ti SCR catalysts** (plate or honeycomb) — the industrial standard; see the [SCR DeNOx Complete Guide](../scr-denox/index.md).
- **Low-temperature SCR formulations** for 150–200 °C duties — see [Low-Temperature SCR](../scr-denox/scr-low-temperature-catalyst.md).
- Zeolites and activated carbon serve NOx roles only in specialized niches (low-temperature adsorption, combined systems), not as primary NOx destruction materials.

## Suitable technologies

- **SCR** — selective catalytic reduction with NH₃ (or urea): the default for large flows and high removal (design 80–95%); [SCR vs SNCR](../scr-denox/scr-sncr-comparison.md).
- **SNCR** — reagent injection without catalyst, for moderate removal at lower capital cost.
- **Absorption/scrubbing** — for NO₂-rich streams (e.g. nitric acid plants).

## Operating conditions that matter

- NOx inlet concentration and NO/NO₂ split
- Gas temperature at the catalyst (and its stability over load changes)
- SO₂ / SO₃ concentration and humidity (bisulfate and acid-dew-point limits)
- Dust concentration and particle size (erosion, plugging)
- NH₃/NOx molar ratio (typical operating range 0.8–1.05 — beyond 1, slip rises)

*Data type:* the parameter ranges above are Typical Value engineering references; product-specific
windows come from manufacturer specification. See [Data Classification](../methodology/data-classification.md).

## Testing

- Catalyst activity is verified by simulation testing on actual gas — [SCR Activity Testing](../scr-denox/scr-activity-testing.md).
- Inlet/outlet NOx by continuous emission monitoring (CEMS) or extractive sampling — [CEMS & Monitoring](../compliance/cems-continuous-monitoring.md).

## Limitations

- SCR below ~200 °C (conventional catalysts): poor activity and bisulfate risk.
- High SO₂ fuels shorten conventional catalyst life and raise SO₂→SO₃ oxidation.
- NO alone resists scrubbing; wet routes only suit NO₂-rich streams.
- Ammonia supply and slip compliance add system complexity.

## Related materials

- [SCR DeNOx Catalysts](../scr-denox/index.md) — the material layer
- [Activated Carbon](../activated-carbon/index.md) — limited NOx roles (see flue gas treatment page)

## Related processes

- [SCR vs SNCR](../scr-denox/scr-sncr-comparison.md)
- [Flue Gas Treatment with Activated Carbon](../activated-carbon/activated-carbon-flue-gas-treatment.md)
- [China Ultra-Low Emission Standards](../compliance/china-ultra-low-emission-standards.md)
