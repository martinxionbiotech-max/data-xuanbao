---
title: "Xuanbao Engineering Views: Engineering Positions on Recurring Selection Questions"
description: "Xuanbao engineering positions on recurring selection questions: iodine number limits, humidity effects, adsorption vs catalytic oxidation, SCR performance decline, catalyst poisoning and inlet conditions."
---

# Xuanbao Engineering Views

**Direct answer:** This page collects Xuanbao's engineering positions on the
recurring selection questions we see in quotation requests. Each position is
structured the same way — *fact → principle → engineering impact → Xuanbao
viewpoint → limitations* — and each links to the full article behind it.

We mark the knowledge level of every statement: **Industry fact** (established
in the published literature), **Published knowledge** (codified in standards or
widely used engineering practice) and **Xuanbao engineering observation** (what
we see in application work). Nothing here is invented — where our observation
rests on a documented field test, the [Evidence Registry](../methodology/evidence-registry.md)
is cited.

## 1. Why iodine number alone is not enough for VOC carbon selection

- **Industry fact:** iodine number measures micropore development for small molecules; two carbons with identical iodine values can differ sharply in working capacity for a given VOC.
- **Principle:** the useful capacity for a specific adsorbate is set by the match between pore size distribution and molecule size, not by any single index.
- **Engineering impact:** buying carbon on iodine number alone routinely over-specifies micropore carbon for mid-sized solvents, raising cost without raising bed life.
- **Xuanbao viewpoint:** select carbon against the actual contaminant, concentration and humidity — ask for the working-capacity curve for your specific compound, not the headline iodine value.
- **Limitations:** single-index comparison remains useful as a quick authenticity check, just not as the selection basis.
- Full article: [Quality Indicators](../activated-carbon/activated-carbon-quality-indicators.md), [How to Select Activated Carbon](../activated-carbon/activated-carbon-selection.md).

## 2. How humidity affects activated carbon adsorption

- **Industry fact:** water competes with organic adsorbates for surface sites; capacity falls as relative humidity rises.
- **Principle:** above roughly 50% RH on standard carbons, water adsorption erodes VOC working capacity — the effect is worst for low-concentration, weakly adsorbed species.
- **Engineering impact:** humid duty needs hydrophobic carbons, zeolites, or humidity control upstream — otherwise beds are sized on dry-lab data and underperform in service.
- **Xuanbao viewpoint:** state the real RH range when requesting sizing; a bed designed for 80% RH behaves differently from one designed for 40% RH.
- **Limitations:** published RH thresholds are indicative; the definitive answer is a working-capacity test at your conditions.
- Full article: [Humidity & Temperature Effects](../activated-carbon/activated-carbon-humidity-temperature.md).

## 3. When adsorption is preferable to catalytic oxidation

- **Industry fact:** adsorption wins at low concentration and near-ambient temperature; catalytic oxidation wins at higher concentration where heat release pays for the energy input.
- **Principle:** below light-off temperature a catalyst cannot convert; below economical concentration thresholds oxidation consumes more energy than it destroys pollutant.
- **Engineering impact:** choosing the wrong route either wastes energy (forced oxidation of dilute streams) or bed capacity (carbon on concentrated streams).
- **Xuanbao viewpoint:** treat adsorption and oxidation as one system — adsorption as the concentration step feeding oxidation is often the right combined answer.
- **Limitations:** the crossover concentration depends on the specific species, flow and energy cost — it is calculated, not assumed.
- Full article: [Adsorption vs Catalytic Oxidation](../voc-engineering/adsorption-vs-catalytic-oxidation.md), [Material Selection Guide](../voc-engineering/gas-purification-material-selection.md).

## 4. Why SCR catalyst performance declines

- **Industry fact:** SCR catalysts lose activity through poisoning, fouling and erosion; the rate depends on the fuel and gas cleaning upstream.
- **Principle:** poisons (arsenic, alkali metals) deactivate the active sites irreversibly; dust and ammonium bisulfate add physical blockage on top.
- **Engineering impact:** performance decline is designed for — catalyst volume includes a deactivation margin, and layer replacement is planned, not improvised.
- **Xuanbao viewpoint:** the same NOx target can need 20–40% more volume on a high-poisoning fuel; fuel analysis is a sizing input, not an afterthought.
- **Limitations:** deactivation rates are fuel- and site-specific; observed rates come from operation, not from catalog values.
- Full article: [Catalyst Poisoning](../scr-denox/scr-catalyst-poisoning.md), [SCR Catalyst Selection](../scr-denox/scr-catalyst-selection.md).

## 5. How catalyst poisoning occurs

- **Industry fact:** poisons act by blocking sites (fouling), occupying active centres (chemical poisoning) or destroying the structure (erosion, thermal damage).
- **Principle:** poisoning is a surface phenomenon — trace concentrations in the gas concentrate on the catalyst surface over thousands of operating hours.
- **Engineering impact:** poison exposure sets the deactivation margin; protecting stages (dedusting, acid removal) extend life more cheaply than adding catalyst.
- **Xuanbao viewpoint:** inlet conditions matter more than generic removal claims — a catalyst specified without the poison profile is specified blind.
- **Limitations:** laboratory poisoning tests approximate field exposure; they rank materials, they do not predict site life exactly.
- Full article: [Catalyst Poisoning](../scr-denox/scr-catalyst-poisoning.md), [CO Catalyst Deactivation](../co-oxidation/co-catalyst-deactivation.md).

## 6. Why inlet conditions matter more than generic removal claims

- **Industry fact:** removal efficiency is a system property: it depends on temperature, space velocity, concentration, moisture and poisons at the reactor inlet — not on the catalyst alone.
- **Principle:** the same catalyst can deliver 99% conversion on one stream and 80% on another; the difference is the inlet.
- **Engineering impact:** a "≥95% conversion" claim without stated conditions is not a sizing basis — the reactor is sized from your actual gas.
- **Xuanbao viewpoint:** we size from the current fuel and gas analysis, the measured velocity distribution and the outage window — and recommend simulation testing with the actual gas before large orders.
- **Limitations:** inlet conditions change over plant life (fuel switching, process changes) — sizing should include that drift, not just today's sample.
- Full article: [Reading Test Reports](../testing/reading-test-reports.md), [Flue Gas Sampling](../testing/flue-gas-sampling.md).

## 7. Documented field evidence behind these positions

Two of our positions rest on documented field tests, both registered in the
[Evidence Registry](../methodology/evidence-registry.md):

- **XB-EV-001** — sintering machine CO: 1,499 ppm → 18 ppm (derived removal ≈ 98.8%), test date 2022-08-23. Partially recorded: operating conditions not published.
- **XB-EV-002** — medical waste incinerator CO: 11,224.2 mg/Nm³ → 16.2 mg/Nm³ (derived removal ≈ 99.86%), test date 2023-03-20. Partially recorded: operating conditions not published.

These support the general claim that catalytic CO oxidation achieves high
single-pass conversion on real industrial streams — within the limits stated in
the registry, not as universal guarantees.

## Related pages

- [Data Classification](../methodology/data-classification.md) — the seven data types used across this knowledge center.
- [Evidence Registry](../methodology/evidence-registry.md) — every documented claim and its verification status.
