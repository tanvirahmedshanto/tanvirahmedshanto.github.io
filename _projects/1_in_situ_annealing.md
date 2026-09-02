---
layout: page
title: In-Situ Annealing Printhead
description: A patented printhead that reheats the interlayer bond line during extrusion, raising strength and fracture resistance in FFF parts.
importance: 1
category: research
related_publications: true
---

Fused filament fabrication builds parts layer by layer, and the weakest direction is almost always
across those layers. The bond between adjacent beads forms while the previously deposited material is
already cooling, so interlayer strength is governed by how much thermal energy is available at the
interface and for how long.

This project developed an **adaptive in-situ annealing printhead** that delivers localized heat to the
bond line as the part is being built, rather than post-processing the finished part in an oven — which
distorts geometry and cannot reach internal interfaces.

## Results

Applied to short-carbon-fiber ABS, in-situ annealing produced {% cite shanto2026situ %}:

- **39%** higher ultimate tensile strength
- **30%** higher elastic modulus
- **63%** higher glassy storage modulus
- **~92%** higher Mode-I fracture resistance
- Crack-path void content reduced from roughly **4.0% to 0.7%**, with a shift toward cohesive rather
  than interfacial fracture

## Method

Effects were resolved through a randomized 2×3×5 full-factorial program spanning 60 print batches,
analyzed with GLM/ANOVA using Type III sums of squares, interaction and residual diagnostics, and
Tukey HSD comparisons. Thermal history was captured with MWIR thermography and linked to void
morphology measured by X-ray μ-CT and SEM fractography.

## Intellectual property

The printhead is covered by U.S. Patent 12,496,776 B2 {% cite taylor2024fused %}, with a second
application pending for the adaptive annealing variant {% cite shanto2026adaptive %}. The technology is
being commercialized through [Increscent, Inc](/experience/).
