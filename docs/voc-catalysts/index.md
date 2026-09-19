# VOC Catalytic Oxidation: The Complete Guide

**Direct answer:** VOC catalytic oxidation destroys volatile organic compounds by
oxidizing them to CO₂ and water over a catalyst at 200–450°C — typically 300–500°C
cooler than thermal oxidation, cutting fuel consumption drastically. Catalysts use
platinum, platinum-palladium or non-precious-metal active systems on ceramic
honeycomb substrates. This guide is the hub for the entire VOC catalyst topic.

---

## 1. The technology in one paragraph

VOC-laden air passes through a catalyst bed where hydrocarbons oxidize:

CₓHᵧ + O₂ → CO₂ + H₂O

Because the catalyst lowers the activation energy, destruction happens at 200–450°C
instead of 700–800°C. This makes catalytic oxidation (RCO when paired with
regenerative heat recovery) the lowest-fuel oxidation route — provided the stream
contains no catalyst poisons.

## 2. The three catalyst systems

| System | Active component | Typical range | Best for |
| --- | --- | --- | --- |
| Platinum (Pt) | Pt on γ-Al₂O₃ washcoat | 200–400°C | General VOC, low-temperature light-off |
| Platinum-Palladium (Pt-Pd) | Bimetallic | 220–450°C | Broader species range, sulfur-bearing streams |
| Non-precious metal | Transition metal oxides | 250–450°C | Cost-sensitive, clean streams |

Full selection logic — temperature, species list, poison check, duty pattern — is
in [VOC Catalyst Selection](voc-catalyst-selection.md).

## 3. Key design parameters

| Parameter | Typical range | Notes |
| --- | --- | --- |
| Operating temperature | 200–450°C | Set by light-off + 20–40°C margin |
| Space velocity (GHSV) | 10,000–30,000 h⁻¹ | Higher for easy species, lower for hard ones |
| Inlet concentration | 0.5–4 g/Nm³ | Above ~4 g/Nm³: adiabatic rise and LEL limits |
| Destruction efficiency | 90–99% | Species- and temperature-dependent |
| Pressure drop | ~1–3 kPa | Honeycomb face velocity driven |

Sizing step-by-step — including adiabatic temperature rise and deactivation
margin — is in [Space Velocity Design](voc-space-velocity-design.md)
- [Catalytic vs Thermal Oxidation](voc-catalytic-vs-thermal-oxidation.md) — choosing the route.
- [Precious vs Non-Precious Metal](voc-precious-vs-non-precious.md) — chemistry, cost, lifecycle.
- [Halogenated VOC Treatment](voc-halogenated-treatment.md)
- [Coating & Paint Shops](voc-coating-industry.md) — concentration + oxidation architecture.
- [Printing Industry](voc-printing-industry.md) — solvents, dryers, recovery economics. — what catalysts can and cannot do..

## 4. What kills VOC catalysts

The poison list matters more than the catalyst choice:

- **Silicones** (siloxanes) — a few ppm can kill a catalyst in weeks; irreversible
  silica masking.
- **Halogens** (chlorinated solvents) — attack metal and washcoat.
- **Sulfur** — poisons precious metals, partially reversible above ~300°C.
- **Heavy metals** (Pb, Zn, Hg) — irreversible accumulation.
- **Particulates** — blind the face; pre-filter.
- **Polymerizing species** (styrene, acrylates) — foul at low temperature.

Full mechanism detail and the prevention checklist are in
[VOC Catalyst Deactivation](voc-catalyst-deactivation.md).

## 5. Lifecycle and regeneration

Typical life is 2–5 years depending on duty. Thermal regeneration (in-situ
burn-off at 350–450°C) recovers polymerization fouling but cannot reverse
silicone, halogen or heavy-metal poisoning. Monitoring practice: track conversion
at a fixed reference condition; regenerate when it falls 10–15% below baseline;
replace when regeneration intervals become uneconomical —
[Regeneration & Lifecycle](voc-catalyst-lifecycle.md).

## 6. RCO vs RTO

With regenerative heat recovery, catalytic oxidation becomes RCO — the
fuel-sipper choice for clean, stable streams. Thermal oxidation (RTO) tolerates
poisons and particulates but burns more fuel at 750–850°C. The full trade-off
table is in [RCO vs RTO](../voc-engineering/rco-vs-rto.md).

## 7. Quick reference: symptom → cause

| Symptom | Most likely cause | Go to |
| --- | --- | --- |
| Conversion falls fast, weeks | Silicone poisoning | [Deactivation](voc-catalyst-deactivation.md) |
| Conversion falls, recovers after heat soak | Sulfur poisoning | [Deactivation](voc-catalyst-deactivation.md) |
| Hot spots, sintering | Concentration too high / adiabatic rise | [Space Velocity](voc-space-velocity-design.md) |
| Face blinded | Particulates | [Selection](voc-catalyst-selection.md) |
| Cold-start failure | Below light-off | [Selection](voc-catalyst-selection.md) |

## 8. The complete VOC catalyst series

- [VOC Catalyst Selection](voc-catalyst-selection.md) — Pt / Pt-Pd / non-precious, the selection questions.
- [VOC Catalyst Deactivation](voc-catalyst-deactivation.md) — poisons, fouling, thermal aging.
- [Regeneration & Lifecycle](voc-catalyst-lifecycle.md) — burn-off, monitoring, replacement budgeting.
- [Space Velocity Design](voc-space-velocity-design.md) — GHSV, contact time, adiabatic rise, sizing margin.

## 9. Manufacturer perspective

The single most valuable document in a VOC inquiry is the species-level VOC
analysis. With it we can predict deactivation modes, choose the active system and
size correctly; without it, every catalyst is a gamble. We ask for it before
quoting non-standard applications — and we flag poison risks explicitly rather
than selling a catalyst that will die early.

## Related products

- [Platinum VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/platinum-catalyst/)
- [Platinum-Palladium VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/platinum-palladium-catalyst/)
- [Non-Precious-Metal VOC Catalyst](https://xuanbaoenvironment.com/products/voc-catalysts/non-precious-metal-catalyst/)
