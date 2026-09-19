# VOC Adsorption Bed Design: Velocity, Bed Depth and Breakthrough

> **Part of the [VOC Treatment Engineering: The Complete Guide](index.md)** — this article is one of the detailed pages in the guide.
>


**Direct answer:** A VOC adsorption bed is defined by four design numbers — face
velocity, bed depth, contact time and breakthrough criterion. Typical designs run
0.2–0.5 m/s face velocity and 0.3–1.0 m bed depth for granular carbon, giving
contact times of 1–3 seconds. The bed must be sized so breakthrough occurs after
the planned service interval, not before.

## The design sequence

1. **Define the duty:** flow, VOC species, inlet concentration, outlet limit,
   operating temperature and humidity.
2. **Pick the adsorbent working capacity** for the species at the service
   conditions (from isotherm or manufacturer data).
3. **Compute adsorbent mass** for the service interval at the design concentration.
4. **Set geometry** — face velocity and bed depth from the velocity and pressure
   drop constraints.
5. **Check the mass transfer zone** — ensure the bed depth comfortably exceeds
   the MTZ length, or early breakthrough will occur despite adequate total mass.
6. **Verify pressure drop** against fan economics.

## Velocity rules

- **Too fast:** shallow MTZ control, channelling, high pressure drop, premature
  breakthrough.
- **Too slow:** oversized vessels, poor distribution.
- Granular carbon beds: commonly 0.2–0.5 m/s. Honeycomb structured carbons
  tolerate higher face velocities (1–3 m/s) at low pressure drop — the reason
  they suit high-flow, low-concentration duties.

## The mass transfer zone (MTZ)

Adsorption does not happen evenly: a zone of partial saturation moves through the
bed. The MTZ length depends on velocity, particle size and species kinetics —
faster gas and larger particles stretch the zone. When the MTZ front reaches the
bed outlet, breakthrough begins. The bed must be deep enough that the MTZ
represents a fraction of total depth, keeping breakthrough sharp and predictable.

## Humidity and temperature effects

- High humidity reduces VOC capacity — water competes for sites. Hydrophobic
  adsorbents (high-silica zeolites) or dehumidification upstream are the cures.
- Adsorption is exothermic: high concentrations raise bed temperature and lower
  capacity; the classic correction is dilution or pre-cooling.
- Capacity falls as temperature rises — size on the worst-case warmest stream.

## Bed configuration choices

- **Single bed:** simple, cheapest — service stops during change-out.
- **Lead-lag (two beds in series):** the lead bed saturates, the lag bed
  polishes; swap positions at breakthrough. Higher adsorbent utilization.
- **Multiple parallel beds:** isolates sections for maintenance on large flows.

## Manufacturer perspective

We size from isotherm data at the actual humidity and temperature, not from dry
catalogue capacity, and we always check the MTZ depth. A bed that looks correct
on total mass but is too shallow fails early — the most common design error we
see in inquiries.

## Related articles

- [Adsorption Engineering](voc-adsorption-engineering.md)
- [Zeolite vs Activated Carbon](zeolite-vs-activated-carbon.md)

[← Back to the VOC Treatment Engineering: The Complete Guide](index.md)

## Related products

- [Honeycomb Activated Carbon](https://xuanbaoenvironment.com/products/activated-carbon/honeycomb-activated-carbon/)
- [Coal-Based Columnar Carbon](https://xuanbaoenvironment.com/products/activated-carbon/coal-based-columnar-carbon/)
- [Modified 13X Molecular Sieve](https://xuanbaoenvironment.com/products/zeolite-molecular-sieve/modified-13x/)
