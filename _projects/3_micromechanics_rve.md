---
layout: page
title: μ-CT-Informed Micromechanics
description: Representative volume elements built from real scanned bead geometry, used to predict effective properties of printed material.
importance: 3
category: research
---

A printed part is not a solid block of polymer — it is a bonded assembly of beads with voids between
them. Predicting stiffness from the bulk material data sheet therefore overestimates real performance,
often badly.

This project builds **representative volume elements (RVEs) from X-ray μ-CT scans** of actual printed
material, so the modeled geometry carries the real void morphology rather than an idealized one.

## Approach

- RVEs generated for both standard and in-situ-annealed bead architectures
- Three-axis virtual homogenization to extract the full anisotropic property set
- Mesh convergence studies to confirm results were not discretization artifacts
- Low, mid, and high engineering-property envelopes rather than single-point predictions

## Outcome

The property envelopes give downstream structural models a defensible range to work with, and directly
quantify how much of the measured strength gain from in-situ annealing is attributable to void
reduction versus improved interfacial bonding.
