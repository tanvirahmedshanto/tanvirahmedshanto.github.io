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

**U.S. Patent 12,496,776 B2**, granted 16 December 2025
Application 18/360,150, filed 27 July 2023. Priority 9 August 2022.
Assignee: University of Texas System

Taylor, R. M., Rane, R., Mrinal, M., Patel, P. T., & **Shanto, T. A.**

{% include figure.liquid path="assets/img/research/patent-1.jpg" alt="Photograph and exploded CAD view of the print head, labelling the insulation tube, fan, duct, fins, throat, heater block and nozzle" caption="The print head as built and as an exploded assembly: insulation tube, fan, duct, fins, throat, heater block, and nozzle." zoomable=true %}

A print head that applies thermal treatment during printing rather than after it. A heating block
delivers energy at the deposition zone. Upstream, a fan, duct, and finned heat sink keep the incoming
filament rigid so the back pressure needed for extrusion is preserved.

That combination is what makes in-process annealing workable: the weld is heated without softening the
feed, so parts gain mechanical performance without the distortion that oven annealing causes on thin
geometries.

[View the patent record](https://patents.google.com/patent/US12496776B2/en)

---

## Fused filament fabrication adaptive annealing print head system

**U.S. Patent Application 19/660,770**, pending

**Shanto, T. A.**, Taylor, R. M., Mrinal, M., Ahmed, R., Patel, P. T., Rahman, M. M., Dola, I. S., & Deshpande, R.

{% include figure.liquid path="assets/img/research/patent-2.jpg" alt="Assembly and exploded views of the adaptive annealing print head, labelling the mounting bracket, locking nuts, stepped screw, thermistor hole, heater clamp, ring heater, annealing plate, adapter, fixed frame, heat sink, heating block and nozzle" caption="The adaptive print head. A ring heater drives a separate annealing plate, controlled independently of the nozzle and adjustable in height through the stepped screw." zoomable=true %}

The adaptive design separates annealing from extrusion. A ring heater drives its own annealing plate,
adding two controls the first design lacked: plate temperature, set independently of the nozzle, and
plate height, adjusted through a stepped screw.

Both matter because annealing effectiveness is not fixed by the printhead alone. It depends on print
speed, part spacing, and geometry, so a setting correct for one configuration is wrong for another.
Independent control of temperature and standoff holds the weld interface in its productive window as
conditions change. The [adaptive annealing study]({{ '/research/journal/' | relative_url }}) reports a
3.8-fold rise in bonding potential and a threefold drop in void fraction.

_Patents are identified by patent and application number rather than DOI._
