---
title: CTC Activity and Methylene Blue Number: What These Adsorption Tests Actually Measure
description: How to read carbon tetrachloride (CTC) activity and methylene blue adsorption values on activated carbon certificates — what pore sizes they probe, which test standards apply, and why they cannot be compared across methods.
---

# CTC Activity and Methylene Blue Number: Reading the Certificate Correctly

**Direct answer:** CTC activity and methylene blue number are two different "windows" into the pore structure of activated carbon. CTC (carbon tetrachloride) activity measures the weight of CTC vapor a carbon adsorbs under saturated conditions — a gas-phase test that mainly reflects total pore volume and is widely used for VOC/solvent-recovery grades. Methylene blue number measures liquid-phase adsorption of a mid-size dye molecule and mainly reflects mesopore (2–50 nm) volume — the number that matters for decolorization duty. Neither is a universal quality score: each answers one specific question about one specific pore-size range.

---

## 1. The two tests side by side

| Dimension | CTC activity | Methylene blue number |
|---|---|---|
| Phase | Gas (saturated CTC vapor, fixed temperature) | Liquid (aqueous dye solution) |
| Probe molecule | CCl₄, effective diameter ≈0.55 nm | Methylene blue, a mid-size organic dye |
| Pore window | Micro- and small mesopores — total pore volume proxy | Mesopores (roughly 2–5 nm) |
| Typical application read | VOC adsorption, solvent recovery, gas-phase capacity | Decolorization (sugar, syrup, oil, wastewater), mesopore development |
| Chinese standard | GB/T 7702.13 (coal-based granular carbon CTC adsorption, 2022 revision published) | GB/T 7702.6-2008 (methylene blue adsorption, coal-based) |
| Reported unit | % (weight gain) or g/100g | mg/g |

The kinetic diameters explain the split: iodine (≈0.27 nm) and CTC (≈0.55 nm) are small and reach micropores; methylene blue is far larger and only fits mesopores. This is why the three numbers — iodine, CTC, methylene blue — used together sketch the pore distribution: iodine → micro; CTC → micro + small meso; methylene blue → meso.

## 2. What CTC activity means for gas-phase buying

- A high CTC activity indicates high total pore volume — the raw storage capacity for VOC molecules of similar size to CTC.
- CTC activity is the classic specification for **solvent-recovery grades**; in the Chinese system it appears in the GB/T 7701/7702 series for coal-based carbons.
- The number is strongly test-condition dependent (temperature of the saturated vapor environment, contact time, pre-drying) — compare only values from the same standard and same stated conditions.
- CTC activity says nothing about **selectivity under humidity or low concentration**. A high-CTC carbon can still fail humid, low-concentration duty; see [Humidity & Temperature](activated-carbon-humidity-temperature.md).

## 3. What methylene blue number means for liquid-phase buying

- Methylene blue number is the standard proxy for **mesopore volume** and, in practice, for **decolorization power**.
- Chinese vendor tables rank methylene blue adsorption by raw material: wood powder > wood granular > peach shell > apricot shell > coal > coconut shell — the same ranking as mesopore development. This explains why wood-based carbons dominate sugar and syrup decolorization in China.
- A coconut-shell carbon with a very high iodine number can still have a modest methylene blue number — its pores are mostly too small for the dye. High iodine + low methylene blue = microporous decolorizer is *not* what you are buying.
- The coconut-shell group standard (2023) pairs the two explicitly: iodine ≥1000 mg/g **and** methylene blue ≥135 mg/g — a two-window specification worth imitating in your own purchase documents.

## 4. Reading a certificate: the five checks

1. **Which standard and which method version?** GB/T 7702.6-2008 vs GB/T 12496.10 vs ASTM or JIS methods differ in concentration, contact time and reporting. Same-number-different-method comparisons are meaningless.
2. **Which raw material is the standard written for?** The GB/T 7702 series is written for coal-based carbons, GB/T 12496 for wood-based, GB/T 13803 for wood products, and new family standards (coconut-shell group standard, bamboo GB/T 48061-2026) carry their own. Ask the lab to test against the standard that matches the carbon family you are buying.
3. **CTC test conditions stated?** Temperature and saturation setup must be on the certificate; absence of conditions is a reason to ask.
4. **Iodine + CTC + methylene blue read together** — one number alone cannot describe a carbon with both micro- and mesopores.
5. **Vendor typical ranges are marketing, standard thresholds are anchors.** Compare vendor claims against the standard thresholds for the family (see the table in [Raw Materials Comparison](activated-carbon-raw-materials.md)).

## 5. Common interpretation mistakes

- **"Higher iodine = better carbon"** — only true for microporous duty. For decolorization, methylene blue and molasses numbers matter more.
- **"CTC activity equals VOC capacity"** — CTC is a single-component saturated-vapor measurement; real VOC streams are low-concentration, humid and multi-component. Use CTC for ranking, breakthrough data for design.
- **"Methylene blue tests water-purification ability"** — it tests mesopore volume. Municipal water carbons are specified by iodine (GB/T 7701.2, CJ/T 345), not methylene blue.
- **Cross-method comparisons** — iodine values from GB/T 7702.7-2023, GB/T 12496.8 and ASTM D4607 are not directly interchangeable; fix one method in your specification (the 2023 revision of GB/T 7702.7 explicitly extended the range and shapes covered, which matters for granular vs pellet comparisons).

**Bottom line:** CTC activity answers "how much gas-phase pore volume is there?"; methylene blue answers "how much mesopore is there for large molecules?" Ask both — plus iodine — and read them as three windows on one pore system, each tied to its own standard and test conditions.

---

*Data classification: test-mechanism descriptions are General technical knowledge; standard designations and thresholds are Regulatory/standard class (High); raw-material methylene-blue ranking is vendor-table class (Medium). Related: [Quality Indicators](activated-carbon-quality-indicators.md), [Raw Materials Comparison](activated-carbon-raw-materials.md), [Reading Test Reports](../testing/reading-test-reports.md).*
