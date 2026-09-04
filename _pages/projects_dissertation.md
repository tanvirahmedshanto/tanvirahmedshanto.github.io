---
layout: page
permalink: /research/dissertation/
title: doctoral dissertation
description: Improving Strength and Fracture Resistance in Fused Filament Fabrication Through Printhead-Integrated In-Situ Annealing. Ph.D., The University of Texas at Arlington, 2026.
nav: false
toc:
  sidebar: left
---

[← Back to research overview]({{ '/research/' | relative_url }})

---

# Improving Strength and Fracture Resistance in Fused Filament Fabrication Through Printhead-Integrated In-Situ Annealing

**Ph.D. in Mechanical Engineering** · The University of Texas at Arlington · Summer 2026
Advisor: **Dr. Robert M. Taylor** · Defended 14 August 2026

[View in the UTA MavMatrix repository](https://mavmatrix.uta.edu/mechaerospace_dissertations2/8)

{% include figure.liquid path="assets/img/research/diss-fig1.jpg" alt="Dissertation title slide showing the in-situ annealing printhead assembly" caption="Improving Strength and Fracture Resistance in Fused Filament Fabrication Through Printhead-Integrated In-Situ Annealing." zoomable=true %}

---

## Problem

Fused filament fabrication builds parts layer by layer, and polymer healing across each interlayer weld
is usually incomplete. The result is anisotropic behaviour: parts are strong along the print direction
and weak across it.

Post-process annealing can strengthen those interfaces, but heating the whole part risks dimensional
distortion and warpage. On thin geometries that trade is rarely acceptable.

## Approach

This work reheats each layer locally as it is deposited, using a heated annular plate integrated into
the printhead. Softening the incoming filament would destroy the back pressure that drives extrusion,
so the design pairs the heating element with upstream cooling that keeps the feed rigid.

The studies cover neat ABS and short-carbon-fiber ABS (ABS-CF), combining non-isothermal healing theory
with in-process measurement. Bonding potential, welding time, and critical bonding temperature link the
measured thermal history to interfacial healing.

### Methods

- **In-process infrared thermography** for interfacial thermal history and welding time above the glass
  transition
- **X-ray micro-computed tomography** for void morphology and volume fraction
- **SEM fractography** to identify whether failure ran along the interface or through the polymer
- **Tensile testing, DMA, and Mode-I fracture testing** to ASTM D5528 (DCB) and ASTM D5045 (SENB)
- **Full-factorial design of experiments** analysed with GLM/ANOVA and Tukey HSD

{% include figure.liquid path="assets/img/research/diss-fig2.jpg" alt="Mechanical characterisation equipment: dynamic mechanical analyser, tensile test, two three-point bend configurations, and a Mode-I fracture toughness test" caption="Mechanical characterisation: DMA, tensile, three-point bending, and Mode-I fracture testing." zoomable=true %}

{% include figure.liquid path="assets/img/research/diss-fig3.jpg" alt="Material characterisation equipment: Bruker SkyScan 1273 micro-CT, scanning electron microscope, FLIR in-situ thermal monitoring, and a FARO arm scanner" caption="Material characterisation: micro-CT, SEM, FLIR thermography, and FARO arm scanning." zoomable=true %}

---

## Results

**Neat ABS, batch printing.** A full-factorial study established a practical operating window for
localized annealing and produced an average **48.5% increase in build-direction toughness**, rising to
68% under the best condition of low speed and close spacing.

**ABS-CF.** Higher interfacial thermal exposure gave a **39% increase in tensile strength**, **63% in
glassy storage modulus**, and **92% in Mode-I fracture resistance**. Scatter fell as well: the
coefficient of variation in fracture toughness dropped from **20.1% to 9.5%**, because annealing closed
the large voids sitting on the load path rather than densifying the part uniformly.

**Adaptive printhead.** With independent control of plate temperature and standoff, plate temperature
dominated within the process window. The best condition raised tensile strength by 34% and toughness by
58%. A thin-wall box beam gained **55% in flexural strength**.

**Fracture.** DCB conditional propagation resistance rose **84.3%** and SENB total work **96.2%**, while
elastic stiffness stayed largely unchanged. The benefit therefore sits in the interlayer damage and
fracture process, not in bulk stiffening.

## Conclusion

Controlling local thermal history during printing improves interlayer healing, reduces critical
mesostructural defects, and raises strength and fracture resistance, without the dimensional risk of
whole-part annealing.

One limit is worth stating. Performance does not rise without bound as heat input increases. The useful
window is set jointly by material, geometry, print speed, plate temperature, and standoff, and thermal
exposure is a property of the process and geometry together rather than of the setting alone.

---

## Outputs

| Output | Detail |
| --- | --- |
| Patents | 1 granted (US 12,496,776 B2), 1 pending (19/660,770) |
| Journal articles | 5 published, 3 under review |
| Conference papers | 9 peer-reviewed |
| Commercialization | [Increscent, Inc.]({{ '/research/industry/' | relative_url }}), $50,000 NSF I-Corps Team award |

[Journal articles]({{ '/research/journal/' | relative_url }}) ·
[conference papers]({{ '/research/conference/' | relative_url }}) ·
[patents]({{ '/research/patents/' | relative_url }})
