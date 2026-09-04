---
layout: page
permalink: /research/patents/
title: patents
description: One granted and one pending U.S. patent covering printhead-integrated in-situ annealing for fused filament fabrication.
nav: false
toc:
  sidebar: left
---

[← Back to research overview]({{ '/research/' | relative_url }})

---

## Fused filament fabrication print head system

**U.S. Patent 12,496,776 B2** — granted 16 December 2025
Application 18/360,150, filed 27 July 2023 · Priority 9 August 2022
Assignee: University of Texas System

Taylor, R. M., Rane, R., Mrinal, M., Patel, P. T., & **Shanto, T. A.**

{% include figure.liquid path="assets/img/research/patent-1.jpg" alt="Photograph and exploded CAD view of the print head, labelling the insulation tube, fan, duct, fins, throat, heater block and nozzle" caption="The print head as built and as an exploded assembly: insulation tube, fan, duct, fins, throat, heater block, and the wide nozzle that delivers heat to the deposited layer." zoomable=true %}

A print head that applies thermal treatment **during** printing rather than after it. A heating block
delivers energy at the deposition zone while an upstream cooling stack — fan, duct, and finned heat
sink — keeps the incoming filament rigid, preserving the back pressure needed to extrude at all. That
pairing is what makes in-process annealing feasible: heat the weld without softening the feed.

The result is improved mechanical properties without the geometric distortion that post-process oven
annealing causes on thin geometries.

[View the patent record](https://patents.google.com/patent/US12496776B2/en)

---

## Fused filament fabrication adaptive annealing print head system

**U.S. Patent Application 19/660,770** — pending

**Shanto, T. A.**, Taylor, R. M., Mrinal, M., Ahmed, R., Patel, P. T., Rahman, M. M., Dola, I. S., & Deshpande, R.

{% include figure.liquid path="assets/img/research/patent-2.jpg" alt="Assembly and exploded views of the adaptive annealing print head, labelling the mounting bracket, locking nuts, stepped screw, thermistor hole, heater clamp, ring heater, annealing plate, adapter, fixed frame, heat sink, heating block and nozzle" caption="The adaptive print head: a ring heater drives a separate annealing plate whose temperature is controlled independently, and whose height is set through the stepped screw." zoomable=true %}

The adaptive variant separates annealing from extrusion. A **ring heater drives its own annealing
plate**, giving two controls the first design did not have: plate temperature, set independently of the
nozzle, and plate height, adjusted through a stepped screw.

Those two degrees of freedom matter because the effectiveness of in-situ annealing is not a property of
the printhead alone — it depends on print speed, part spacing, and geometry. A fixed thermal setting
correct for one configuration is wrong for another. Independent control of plate temperature and
standoff is what allows the weld interface to be held in its productive temperature window as conditions
change, and it is the mechanism behind the
[adaptive annealing study]({{ '/research/journal/' | relative_url }}), which reports a 3.8-fold rise in
bonding potential and a threefold reduction in void fraction.

_Patents are identified by patent and application number rather than DOI._
