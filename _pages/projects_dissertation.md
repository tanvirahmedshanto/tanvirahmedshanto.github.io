---
layout: page
permalink: /projects/dissertation/
title: doctoral dissertation
description: Improving Strength and Fracture Resistance in Fused Filament Fabrication Through Printhead-Integrated In-Situ Annealing — Ph.D., The University of Texas at Arlington, 2026.
nav: false
toc:
  sidebar: left
---

[← Back to research overview]({{ '/projects/' | relative_url }})

---

# Improving Strength and Fracture Resistance in Fused Filament Fabrication Through Printhead-Integrated In-Situ Annealing

**Ph.D. in Mechanical Engineering** · The University of Texas at Arlington · Summer 2026
Advisor: **Dr. Robert M. Taylor** · Defended 14 August 2026

[View in the UTA MavMatrix repository](https://mavmatrix.uta.edu/mechaerospace_dissertations2/8)

{% comment %} Hero image: printhead, print in progress, or a fracture surface
{% include figure.liquid path="assets/img/research/dissertation-hero.jpg" alt="In-situ annealing printhead during deposition" caption="The printhead-integrated in-situ annealing system during deposition." zoomable=true %}
{% endcomment %}

---

## The problem

Fused filament fabrication builds a part one bead at a time, and every bead has to weld to the one
beneath it while that material is already cooling. The result is a structural anisotropy that has
limited the technology for decades: parts are strong along the print direction and weak across it. In
the z-direction, printed polymers fail at interfaces that never fully healed, through voids that the
process itself creates.

The conventional remedy is to anneal the finished part in an oven. That works thermally but fails
practically — the part loses geometric accuracy as it softens, and internal interfaces deep inside the
geometry never see the heat they need.

## The central idea

Rather than treating the part after it is built, deliver thermal energy **at the bond line, while the
bond is forming**. This dissertation designs, patents, and validates a printhead that does exactly that,
then characterises what happens inside the material as a result.

The engineering difficulty is not simply adding a heater. Softening the incoming filament destroys the
back pressure that drives extrusion, so the printhead has to heat the deposition zone while keeping the
filament upstream rigid — which is why the patented design pairs a heating block with an upstream
cooling element.

---

## Approach

The work spans hardware design, designed experimentation, multi-modal characterisation, and modelling,
with each stage anchoring the next.

### Hardware

Adaptive in-situ annealing printheads designed using GD&T and DFM/DFA principles, yielding one issued
and one pending U.S. patent.

### Designed experimentation

Randomized full-factorial programmes — including a 2×3×5 design across 60 print batches — examining
printhead type, print speed, inter-sample spacing, bead overlap, and build-volume temperature. Analysis
used GLM/ANOVA with Type III sums of squares, interaction and residual diagnostics, and Tukey HSD
comparisons.

### Characterisation

{% comment %} {% include figure.liquid path="assets/img/research/dissertation-microct.jpg" alt="μ-CT reconstruction of internal voids" caption="X-ray μ-CT reconstruction showing void distribution along the crack path." zoomable=true %} {% endcomment %}

- **MWIR thermography** — interfacial thermal history, including welding time above the glass transition
  temperature, measured in situ during deposition
- **X-ray μ-CT** — void morphology and volume fraction inside the bond region
- **SEM fractography** — whether failure ran along interfaces or through the polymer itself
- **DMA, tensile, and Mode-I fracture testing** — ASTM D5528 (DCB) and ASTM D5045 (SENB)

### Modelling

- μ-CT-informed representative volume elements in Abaqus, with three-axis virtual homogenization and
  mesh convergence, producing low/mid/high engineering-property envelopes
- Abaqus/Explicit cohesive-zone DCB and SENB models, with parameter studies on normal cohesive strength
  and Mode-I fracture energy, calibrated against the physical tests
- Supervised machine-learning models predicting mechanical performance from process parameters and
  thermal features

---

## Principal findings

The through-line is that **thermal history at the interface predicts mechanical performance**, and that
history can be controlled during printing.

**In ABS under batch printing.** In-situ annealing raised toughness by up to **68%** at low speed and
close spacing, increased bonding potential **83-fold**, and reduced void volume by **9%**. ANOVA
identified a significant printhead–speed interaction and a main effect of spacing — meaning the benefit
is not automatic, but depends on deposition kinematics and how parts are laid out on the plate.

**In short-carbon-fiber ABS printed vertically.** Ultimate tensile strength rose **39%**, elastic modulus
**30%**, glassy storage modulus **63%**, and Mode-I fracture resistance roughly **92%**. Crack-path void
content fell from about **4.0% to 0.7%**, and fracture shifted from interfacial to cohesive — the
material began failing through the polymer rather than along the weld.

**In PLA with programmed interlayer cooling.** The enhanced printhead with a cooling pause reached
**53.4 ± 2.7 MPa**, about **86% of bulk PLA**, with the best specimen at **56.8 MPa (~92% of bulk)** and
porosity of 0.885%. Thermography explained why: a standard printhead leaves the interface below the
glass transition, limiting chain diffusion; continuous heating pushes it past the cold-crystallization
onset, where crystallization arrests healing. Cycling the weld between those two temperatures sustains
chain mobility without letting crystallization set in.

**In tall thin-walled structures.** In-situ thermal energy more than doubled bending strength while
maintaining or improving geometric accuracy and surface finish — the combination oven annealing cannot
deliver.

---

## Outputs

| Output | Detail |
| --- | --- |
| Patents | 1 granted (US 12,496,776 B2), 1 pending (19/660,770) |
| Journal articles | 5 published, 3 under review |
| Conference papers | 9 peer-reviewed |
| Commercialization | [Increscent, Inc.]({{ '/projects/industry/' | relative_url }}), $50,000 NSF I-Corps Team award |

Related work by category: [journal articles]({{ '/projects/journal/' | relative_url }}) ·
[conference papers]({{ '/projects/conference/' | relative_url }}) ·
[patents]({{ '/projects/patents/' | relative_url }})
