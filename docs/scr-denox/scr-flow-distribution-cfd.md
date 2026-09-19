# SCR Flow Distribution and CFD Modeling: Why Uniformity Decides Performance

> **Part of the [SCR DeNOx: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.

**Direct answer:** SCR catalyst performance depends on how evenly flue gas and ammonia reach the catalyst
face. Maldistribution of velocity, NOx or NH₃ means parts of the layer work harder than others, raising
ammonia slip and shortening life. CFD modeling plus inlet flow devices (turning vanes, mixers, static
mixers, rectifier grids) is the standard engineering answer.

## Why distribution matters

A catalyst layer converts NOx in proportion to the gas actually reaching it:

- **Velocity maldistribution** — high-velocity channels see higher local area velocity, less residence time
  and faster erosion; low-velocity channels are underused.
- **NOx maldistribution** — regions with concentrated NOx need more ammonia than the average; if ammonia is
  uniform, those regions slip NOx while others slip NH₃.
- **NH₃ maldistribution** — an ammonia plume that misses half the reactor creates local ammonia-rich and
  ammonia-starved zones simultaneously.

The practical result: a catalyst sized with 10% margin on paper can fail its slip target in the field if
distribution is poor.

## What CFD modeling delivers

Computational fluid dynamics simulates the ductwork from economizer (or heater) outlet to catalyst face:

- Velocity contours at the catalyst inlet plane, judged against the ±15% RMS uniformity criterion.
- NH₃/NOx mixing simulation with the AIG (ammonia injection grid) in place.
- Pressure drop mapping and duct recirculation zones.
- Design iterations on guide vanes, mixer position and AIG nozzle layout before steel is cut.

## Flow devices in practice

- **Turning vanes** — steer gas around duct elbows without flow separation.
- **Static mixers** — generate turbulence downstream of the AIG to blend ammonia into the gas.
- **Rectifier grids / perforated plates** — flatten the velocity profile immediately before the catalyst.
- **AIG tuning** — zone-wise nozzle flow adjustment matched to measured NOx distribution.

## Verification after commissioning

CFD predicts; field measurement confirms. After startup, traverse the duct upstream of the catalyst with
velocity and NOx sampling to verify the modeled distribution, then tune the AIG against measured data. This
closes the loop between the model and the permit requirement.

## Manufacturer perspective

We treat distribution as a design input, not a hope: flow conditioning devices and mixing distance are
specified before the reactor is sized, and the catalyst volume is chosen for the measured — not assumed —
uniformity.

## Related articles

- [Ammonia Slip Control](scr-ammonia-slip-control.md)
- [SCR Catalyst Volume Calculation](scr-catalyst-volume-calculation.md)
- [Ash, Erosion & Mechanical Life](scr-ash-erosion.md)

[← Back to the SCR DeNOx: The Complete Guide](index.md)

## Related products

- [Plate-Type SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/plate-type-scr-catalyst/)
- [Honeycomb SCR DeNOx Catalyst](https://xuanbaoenvironment.com/products/scr-denox-catalysts/honeycomb-scr-catalyst/)
