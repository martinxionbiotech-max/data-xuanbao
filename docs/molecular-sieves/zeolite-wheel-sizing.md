---
title: "Zeolite Concentration Wheel Sizing: A Step-by-Step Calculation"
description: "How to size a zeolite concentration wheel: concentration ratio, rotor zoning, airflow vs capacity, dew-point and regeneration constraints, with an illustrative worked example."
---

# Zeolite Concentration Wheel Sizing: Calculating Rotor Duty and Dimensions

> **Part of the [Zeolite Molecular Sieves: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** Sizing a zeolite concentration wheel is a mass-balance and
capacity exercise in three parts — (1) establish the concentration ratio and the
desorption stream, (2) confirm the adsorption capacity holds under the operating
humidity and temperature, and (3) translate the required adsorption airflow into a
rotor area at the permitted face velocity. The result is a rotor diameter/depth and
a desorption-flow requirement that the downstream oxidizer must accept.

## The variables that define the problem

| Quantity | Symbol | What it sets |
| --- | --- | --- |
| Process airflow | Q (Nm³/h) | Rotor cross-section and fan duty |
| Inlet VOC concentration | C_in (mg/Nm³) | Adsorption loading and downstream duty |
| Concentration ratio | CR | Desorption flow = Q / CR |
| Face velocity | v (m/s) | Rotor area = Q / v |
| Desorption temperature | T_des (°C) | Set by VOC boiling point and zeolite desorption curve |
| Adsorption capacity at working RH | q (wt% or mg/g) | Rotor depth / cycle time |

## Step 1 — Define the concentration ratio

The concentration ratio is the ratio of the process (adsorption) airflow to the
desorption airflow:

CR = Q_process / Q_desorption

Typical industrial wheels run CR ≈ 5–20, set by the zeolite's capacity and the
regeneration-air temperature. Higher ratios shrink the desorption stream — and the
oxidizer — but risk incomplete desorption and residual VOC breakthrough.

## Step 2 — Confirm capacity at operating conditions

Zeolite working capacity depends on humidity and temperature, not just the headline
value. Two checks are mandatory:

- **Humidity correction.** Confirm the VOC capacity at the *actual* inlet relative
  humidity — hydrophobic zeolites retain more capacity in humid air than carbon, but
  the value still drops as RH rises.
- **Desorption completeness.** At the chosen T_des, confirm the zeolite releases the
  VOC within the desorption-sector residence time; a T_des too close to the boiling
  point leaves residual loading that bleeds into the next adsorption cycle.

## Step 3 — Size the rotor

Rotor area from face velocity:

A = Q_process / (3600 × v)

The rotor is divided into sectors by the design: adsorption (largest), desorption and
cooling (smallest). Rotor depth follows from the adsorption capacity and the required
cycle time — deeper rotors hold more VOC per pass but raise pressure drop.

## Step 4 — Match the downstream oxidizer

The desorption stream feeds a small RTO/RCO or other oxidizer. Its size is set by the
desorption flow and the concentrated VOC level — which must remain below the LEL
safety limit. The wheel and oxidizer are one system; the concentration ratio fixes
both the desorption flow and the oxidizer fuel balance.

## Illustrative worked example

> **The numbers below are illustrative only — they demonstrate the calculation
> method and are not measured field or product data.**

Assume a coating line vents Q = 40,000 Nm³/h at C_in = 300 mg/Nm³ VOC, and we target
a concentration ratio CR = 10.

- Desorption flow: Q_des = 40,000 / 10 = **4,000 Nm³/h**.
- Desorption concentration (mass-conserving, before oxidizer losses):
  C_des ≈ C_in × CR = 300 × 10 = **3,000 mg/Nm³** — well below typical LEL limits,
  leaving margin.
- At a design face velocity v = 2 m/s, rotor area:
  A = 40,000 / (3600 × 2) ≈ **5.6 m²** → a rotor of roughly 2.7 m diameter.
- Depth and rotation speed are then fixed by the zeolite working capacity at the
  operating RH and the desorption temperature.

> *Data type:* all values in this example are **illustrative Design Values** for
> demonstrating the method — not measured data and not product specifications. See
> [Data Classification](../methodology/data-classification.md).

## The constraints that override the arithmetic

- **Dew point / regeneration.** The desorption air must be heated above the VOC's
  desorption temperature without exceeding the zeolite's thermal limit; condensation
  in the cooling sector must be avoided.
- **Light VOC limit.** VOCs with boiling points below ~60–70°C slip through and
  should not be sent to a wheel.
- **Fouling species.** Paint mist, tar and high-boiling condensables must be removed
  upstream or they block the rotor permanently.
- **Pressure-drop budget.** Deeper rotors add back-pressure on the process fan.

## Manufacturer perspective

We size from the measured flow, concentration and the species-level VOC list — not
from a headline airflow alone. The decision between direct oxidation, adsorption beds
and a wheel-plus-oxidizer line is made on these numbers, and the wheel's concentration
ratio is chosen together with the downstream oxidizer, never in isolation.

## Related articles

- [Zeolite Concentration Wheels](zeolite-concentration-wheel.md) — rotor operation and when a wheel is right.
- [Zeolite vs Activated Carbon for VOC](../voc-engineering/zeolite-vs-activated-carbon.md)
- [RCO vs RTO](../voc-engineering/rco-vs-rto.md)

[← Back to the Zeolite Molecular Sieves: The Complete Guide](index.md)

## Related products

- [ZSM-5 Zeolite](https://xuanbaoenvironment.com/products/zeolite-molecular-sieve/zsm-5/)
- [NaY Zeolite](https://xuanbaoenvironment.com/products/zeolite-molecular-sieve/nay/)
