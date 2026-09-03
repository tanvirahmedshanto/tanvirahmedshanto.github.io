---
layout: page
permalink: /projects/patents/
title: patents
description: One granted and one pending U.S. patent covering printhead-integrated in-situ annealing for fused filament fabrication.
nav: false
toc:
  sidebar: left
---

[← Back to research overview]({{ '/projects/' | relative_url }})

---

## Fused filament fabrication print head system

**U.S. Patent 12,496,776 B2** — granted 16 December 2025

<!-- Patent drawings are public domain. Download a figure from the patent record and drop it in
     assets/img/research/, then uncomment:
{% include figure.liquid path="assets/img/research/patent-us12496776.png" alt="Printhead assembly drawing from US Patent 12,496,776 B2" caption="Printhead assembly: nozzle, heating block, and upstream cooling element." zoomable=true %}
-->

Taylor, R. M., Rane, R., Mrinal, M., Patel, P. T., & **Shanto, T. A.**
Assignee: University of Texas System. Filed 27 July 2023 (application 18/360,150); priority 9 August 2022.

A fused filament fabrication print head that applies thermal treatment **during** printing rather than
after it. Three elements work together: a nozzle for material deposition, a heating block carrying a
thermal element, and a cooling mechanism positioned upstream. The upstream cooling is what makes the
design work — it keeps the incoming filament rigid before it reaches the heating zone, preserving the
back pressure needed to extrude material through the nozzle at all.

The result is improved mechanical properties in printed parts **without** the geometric distortion that
post-process oven annealing causes, directly addressing the porosity and weak inter-layer bonds inherent
to conventional FFF.

[View the patent record](https://patents.google.com/patent/US12496776B2/en)

---

## Fused filament fabrication adaptive annealing print head system

**U.S. Patent Application 19/660,770** — pending

<!-- Image to be supplied.
{% include figure.liquid path="assets/img/research/patent-adaptive-annealing.png" alt="Adaptive annealing printhead drawing" caption="Adaptive annealing printhead." zoomable=true %}
-->

**Shanto, T. A.**, Taylor, R. M., Mrinal, M., Ahmed, R., Patel, P. T., Rahman, M. M., Dola, I. S., & Deshpande, R.

The adaptive variant of the printhead, which adjusts the applied thermal energy in response to printing
conditions rather than holding a fixed setting. This matters because the effectiveness of in-situ
annealing depends strongly on deposition kinematics and part layout — as the batch-printing study
showed, print speed and inter-sample spacing govern how much interfacial healing actually occurs. A
fixed thermal setting that is correct for one configuration is wrong for another; adapting it keeps the
weld interface in the productive temperature window across varying conditions.
