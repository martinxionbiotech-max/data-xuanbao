---
title: "PAC vs GAC in Water Treatment: How to Choose Powdered or Granular Carbon"
description: "Powdered vs granular activated carbon in water treatment: kinetics, contact time, dosing and regeneration compared - with design ranges and Chinese municipal practice."
---

# PAC vs GAC: Choosing Powdered or Granular Activated Carbon in Water Treatment

> **Part of the [Water & Purification: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** PAC (powdered activated carbon) is a throwaway, fast-kinetics tool dosed as a slurry for seasonal or emergency contaminant events, typically at 5–30 mg/L in Chinese design practice. GAC (granular activated carbon) is a fixed-bed barrier with slower kinetics and long contact time, typically designed around an empty-bed contact time (EBCT) of 8–20 minutes, that can be thermally reactivated. The two are complementary: PAC handles spikes, GAC provides a standing barrier.

---

## 1. What the two forms are

| Dimension | PAC | GAC |
| --- | --- | --- |
| Particle size | Mostly below 100 μm; by ASTM D5158 definition, the bulk passes an 80-mesh (0.30 mm) sieve; drinking-water grades are often below 200 mesh | Typically 0.5–4 mm granules (roughly 8×30 mesh class) |
| Kinetics | Short diffusion path → adsorption rate far higher than granular carbon | Slower kinetics; performance controlled by contact time (EBCT) |
| Contact mode | Slurry dosing into the flow, removed with the sludge | Fixed bed or filter (contactors, carbon filters, carbon-sand dual-layer filters) |
| Regeneration | Single-use, not recoverable | Thermally reactivatable: 850–950 °C, restoring 85–95% of original activity with 5–10% carbon loss per cycle |
| Role in a plant | Emergency / seasonal tool (taste & odor events, algae blooms, pollution incidents) | Standing advanced-treatment barrier (O3-BAC, trace-organics compliance) |

Sources: particle-size definitions and kinetics (ScienceDirect); reactivation conditions (sorbitech.com; osti.gov).

## 2. PAC: design and dosing practice

- **Typical dose.** Chinese water-supply design references cite **5–30 mg/L** as the general PAC dosing range (secondary Wenku citations of the water-supply design guidance; corroborated by the 5–15 mg/L operating range reported by Chinese plant operators). For routine seasonal taste-and-odor control, international sources give 1–20 mg/L; algae-toxin events 20–50 mg/L; emergency response can reach 100–200 mg/L.
- **Contact time.** PAC's effective adsorption window is roughly **15–30 minutes** before floc blankets the particles; Chinese operational guidance commonly states 30–60 minutes of hydraulic contact. Both views are compatible — one measures effective adsorption, the other vessel residence time.
- **Dosing point.** Best practice is dosing upstream of the coagulant by several minutes (adsorption before floc formation), or at the raw-water intake where contact time is longest but doses must be larger. Two-stage dosing (split across two points) has been shown in Chinese practice to outperform single-point dosing: a study at an East Taihu plant found a 12.8% higher removal with two-stage PAC dosing during a 2-MIB episode (Jing Shui Ji Shu, 2019, 38(11)).
- **Performance reference.** At 30 mg/L PAC, geosmin removal of 70–87% is reported; at 2–8 mg/L, removal often cannot bring taste-and-odor compounds below sensory thresholds (zhongchuangcarbon.com technical article).

**Chinese emergency case (Wuxi, Lake Taihu source).** When raw water 2-MIB reached roughly 80 times the limit, PAC pre-treatment at 30–40 mg/L combined with ozone-biological activated carbon (O3-BAC) polishing reduced finished-water 2-MIB to below 10 ng/L — a ~98% removal (Jiao Jie et al., China Water & Wastewater, 2016, 32(11)). GB 5749-2022 sets the 2-MIB and geosmin limits at 10 ng/L, which is the regulatory driver behind PAC emergency dosing and O3-BAC adoption in China.

## 3. GAC: design and operating practice

- **EBCT.** The Chinese industry standard CJJ 32-2011 gives an EBCT of generally **8–15 minutes** for taste-and-odor GAC filters (not less than 10 minutes for algae-laden water). International guidance: 10–20 minutes for taste & odor, 20–40 minutes for PFAS removal.
- **Bed geometry.** CJJ 32-2011: bed depth 1.5–2.5 m, empty-bed filtration velocity 7.5–15 m/h. The Shenzhen Meilin plant demonstration: 2.0–2.1 m bed, EBCT 13.3 min (new) / 8.4 min (expansion), 0.3 m quartz-sand support layer (secondary sources).
- **Replacement cycles.** International vendor guidance: a municipal biological-carbon bed keeps adsorption effectiveness 12–18 months; full replacement every 2–3 years; large facilities commonly send carbon for thermal reactivation. Chinese practice differs materially: O3-BAC plants have run carbon for 7+ years without regeneration while effluent still met GB 5749-2006, because biological degradation — not adsorption — does most of the work and early plants lacked reactivation infrastructure (water8848.com, 2018). Buyers should not compare replacement cycles across these two regimes without knowing which mechanism dominates.
- **Chinese large-scale references.** Guangzhou Nanzhou plant: 1,000,000 m³/d conventional + O3-BAC, commissioned 2004 — China's first million-ton-class O3-BAC plant. Nanjing Jiangning Shuangzha source plant: 450,000 m³/d PAC dosing system (30 mg/L max, 5% slurry) at the intake.

## 4. When to use which

| Situation | Choice | Why |
| --- | --- | --- |
| Seasonal taste-and-odor (geosmin / 2-MIB) spikes | PAC | Fast deployment, no capital bed, dose scales with event |
| Standing compliance with a 10 ng/L odor limit (GB 5749-2022) | GAC (O3-BAC) | Continuous barrier, biological + adsorptive removal |
| Pollution incident response | PAC at intake, high dose | Longest contact time before the plant |
| Trace organics with long-term regulation (e.g., PFAS) | GAC with 20–40 min EBCT | Sufficient contact for slow-diffusing contaminants |
| Decolorization / high turbidity processes | PAC | Disposable, high-rate polishing |

The two are frequently combined in one plant: PAC for the event, GAC for the baseline.

## 5. Quality parameters to specify

- **PAC for liquid duty**: iodine number ≥ 800 mg/g is commonly advised; drinking-water use favors fine powder below 200 mesh (zhongchuangcarbon.com).
- **High-grade coconut GAC**: iodine 1000–1200 mg/g, ball-pan hardness > 97%; reported to extend bed life 30–40% (yuxingchem.com).
- **Test standards (China)**: iodine number GB/T 7702.7-2023; methylene blue adsorption GB/T 7702.6-2008; caramel decolorization for coal-based GAC GB/T 7702.18-2008. Always ask under which standard and test conditions a quoted number was measured.

## 6. Data confidence notes

- PAC dose ranges (5–30 mg/L) rest on secondary citations of Chinese design guidance; the specific clause number was not verified. Treat as planning range, not code text.
- Replacement-cycle numbers are regime-dependent (adsorption-driven vs biological-driven operation) and must not be compared directly across regions.
- Emergency-case figures are single-plant studies — directionally reliable, not universal.

For how carbon properties relate to adsorption behavior, see [Adsorption Mechanism](../activated-carbon/activated-carbon-adsorption-mechanism.md) and [Quality Indicators](../activated-carbon/activated-carbon-quality-indicators.md); for municipal gas-phase applications, see [Flue Gas Treatment](../activated-carbon/activated-carbon-flue-gas-treatment.md).
