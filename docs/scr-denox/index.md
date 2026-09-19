# SCR DeNOx: The Complete Guide

**Direct answer:** Selective Catalytic Reduction (SCR) removes NOx from flue gas by
reacting it with ammonia over a V-Mo-Ti (vanadium-based) catalyst, converting NOx to
nitrogen and water. It is the workhorse NOx control technology for coal power, steel,
cement, glass and waste incineration — typically delivering 80–95% NOx removal within
a defined temperature window. This guide is the hub: it summarizes the whole SCR
topic and links to detailed articles on every part of it.

---

## 1. What SCR does and where it is used

SCR converts nitrogen oxides (NO and NO₂, together NOx) into harmless N₂ and water
using ammonia as the reducing agent:

4NO + 4NH₃ + O₂ → 4N₂ + 6H₂O

The catalyst makes this reaction proceed at 200–420°C instead of the ~900°C that
uncatalyzed thermal reduction would need. Applications:

| Industry | Typical duty |
| --- | --- |
| Coal-fired power | NOx compliance on high-dust flue gas |
| Steel & sintering | Sinter machine exhaust NOx |
| Cement | Kiln exhaust with high alkali dust |
| Glass & ceramics | High-temperature furnace NOx |
| Waste incineration | Municipal and hazardous waste flue gas |
| Chemical & refining | Tail gas and process vents |

## 2. How the catalyst works

The catalyst is titanium dioxide (TiO₂) support carrying vanadium pentoxide (V₂O₅)
as the active component and tungsten or molybdenum trioxide (WO₃/MoO₃) as promoters
that widen the temperature window and suppress SO₂ oxidation.

- **Standard SCR:** NO dominates; 4NO + 4NH₃ + O₂ → 4N₂ + 6H₂O.
- **Fast SCR:** NO₂ present accelerates the reaction at lower temperature.
- **Side reaction to control:** SO₂ oxidation to SO₃ (target ≤1%) and NH₃ oxidation
  at high temperature.

Ammonia is injected upstream — in coal power as anhydrous NH₃, aqueous ammonia or
urea (decomposed to NH₃) — and mixed across the duct by an ammonia injection grid
(AIG).

## 3. Catalyst types: plate vs honeycomb

Two geometries dominate. Details in [Plate vs Honeycomb](plate-vs-honeycomb-scr.md).

- **Plate-type:** metal mesh support with rolled catalyst paste — open channels,
  high erosion tolerance, the standard choice for high-dust coal flue gas.
- **Honeycomb:** extruded homogeneous catalyst — higher specific activity per
  volume, preferred where dust is moderate and volume is constrained.

Both are modular: elements are assembled into steel frames (modules) stacked in the
reactor, typically 2+1 or 3+1 layers with a spare layer position.

## 4. Key design parameters

| Parameter | Typical range | Notes |
| --- | --- | --- |
| Operating temperature | 200–420°C | Below window: low activity + bisulfate; above: NH₃ oxidation |
| Space velocity (SV) | 2,000–8,000 h⁻¹ | Depends on gas conditions and required conversion |
| Face velocity | 4–6 m/s | Balances pressure drop and erosion |
| Channel pitch | ~6–9 mm (plate), 6–20 cells (honeycomb) | Larger pitch for high dust |
| NH₃/NOx molar ratio | 0.8–1.05 | Above 1: rising ammonia slip |
| SO₂ oxidation rate | ≤1% | Formulation-dependent; SO₃ drives bisulfate issues |
| Design NOx removal | 80–95% | Set by permit and economic trade-off |

The selection decision path is covered step-by-step in the articles below — the
short version: define gas conditions (temperature, NOx, SO₂, dust, moisture),
choose geometry, size volume with deactivation margin, then verify with simulation
testing on the actual gas.

## 5. Operation: the three watched numbers

SCR health is monitored through three trends, always together:

1. **NOx conversion** at a fixed reference load and temperature.
2. **NH₃ slip** — the early warning of active-site loss.
3. **Pressure drop** — the signal for plugging and mechanical issues.

The details of controlling ammonia distribution, slip and flow conditioning are in
[Ammonia Slip Control](scr-ammonia-slip-control.md).

## 6. Deactivation: how catalysts die

| Mode | Mechanism | Reversible? | Article |
| --- | --- | --- | --- |
| Arsenic poisoning | As₂O₃ vapor blocks pores | Mostly no | [Poisoning](scr-catalyst-poisoning.md) |
| Alkali (K, Na) poisoning | Neutralizes acid sites | Partially (washing) | [Poisoning](scr-catalyst-poisoning.md) |
| Ammonium bisulfate | SO₃ + NH₃ deposit below ~280–320°C | Yes (thermal/cleaning) | [Poisoning](scr-catalyst-poisoning.md) |
| Ash plugging & erosion | Mechanical damage | Cleaning helps; erosion is terminal | [Ash & Erosion](scr-ash-erosion.md) |
| Thermal sintering | High-temperature structure loss | No | [Replacement](scr-catalyst-replacement.md) |

When performance falls, the decision between regeneration and replacement follows a
measured sequence — [Regeneration](scr-catalyst-regeneration.md) and
[Replacement](scr-catalyst-replacement.md) cover both paths.

## 7. Performance verification

Catalyst activity is quantified as the activity K (m/h), derived from conversion at
defined space velocity. Verification runs in three tiers: laboratory
characterization, simulation with the real gas, and in-situ field testing —
[Activity Testing](scr-activity-testing.md).

## 8. Quick reference: symptom → cause

| Symptom | Most likely cause | Go to |
| --- | --- | --- |
| Conversion falls, slip rises | Chemical deactivation | [Poisoning](scr-catalyst-poisoning.md) |
| Conversion falls, ΔP rises | Plugging / ash | [Ash & Erosion](scr-ash-erosion.md) |
| Slip high, conversion fine | AIG imbalance or over-injection | [Ammonia Slip](scr-ammonia-slip-control.md) |
| Performance falls after cleaning only slightly recovers | Irreversible poisoning | [Regeneration](scr-catalyst-regeneration.md) |
| ΔP doubled since commissioning | Channel erosion/plugging | [Replacement](scr-catalyst-replacement.md) |

## 9. The complete SCR article series

- [Plate vs Honeycomb SCR](plate-vs-honeycomb-scr.md) — geometry choice for dust, erosion and activity.
- [SCR Catalyst Poisoning](scr-catalyst-poisoning.md) — arsenic, alkali metals, SO₂/SO₃ effects.
- [SCR Regeneration](scr-catalyst-regeneration.md) — when washing works and when it doesn't.
- [SCR Replacement](scr-catalyst-replacement.md) — deciding when to change, sizing the replacement.
- [Ammonia Slip Control](scr-ammonia-slip-control.md) — AIG tuning, distribution, stoichiometry.
- [Ash, Erosion & Mechanical Life](scr-ash-erosion.md) — pitch, face velocity, flow conditioning.
- [Activity Testing](scr-activity-testing.md) — K value, lab/simulation/field verification.

## 10. Manufacturer perspective

SCR is a systems problem, not a catalyst purchase. The same NOx target can require
20–40% more catalyst volume on a high-poisoning fuel, and a world-class catalyst
behind a badly tuned AIG will slip ammonia from day one. We size from the current
fuel and flue gas analysis, the measured velocity distribution and the outage
window — and we recommend simulation testing with your actual gas before large
orders.

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [Honeycomb SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/honeycomb-scr-catalyst/)
