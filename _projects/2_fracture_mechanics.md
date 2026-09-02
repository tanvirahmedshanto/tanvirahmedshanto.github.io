---
layout: page
title: Fracture Mechanics of 3D-Printed Polymers
description: Cohesive-zone models calibrated against DCB and SENB testing to predict crack growth in anisotropic printed parts.
importance: 2
category: research
---

Printed polymers fracture along paths set by their bead architecture, so classical isotropic fracture
assumptions do not transfer. This project builds **cohesive-zone models** that reproduce measured crack
growth, then uses them to explore designs without printing and testing every variant.

## Experimental

Mode-I fracture behavior was characterized using:

- **ASTM D5528** double cantilever beam (DCB) testing
- **ASTM D5045** single-edge notched bend (SENB) testing

Force–displacement data was synchronized with optical crack tracking, giving calibration and validation
targets for the cohesive laws rather than a single lumped toughness value.

## Computational

Abaqus/Explicit DCB and SENB models were constructed with traction–separation cohesive behavior. One-factor
studies isolated the influence of:

- bulk solid properties
- normal cohesive strength, $$T_n^0$$
- Mode-I fracture energy, $$G_{Ic}$$

Load–displacement curves, peak load, stiffness, and fracture-work metrics were extracted automatically
from the output databases so that large parameter sweeps stayed tractable.

## Why it matters

Once a cohesive law is calibrated to real specimens, it becomes possible to ask design questions —
bead layout, annealing strategy, notch sensitivity — in simulation, and only print the candidates that
survive that screening.
