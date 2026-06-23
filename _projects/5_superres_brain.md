---
layout: page
title: Super-resolution brain imaging
description: In vivo STED and shadow imaging (SUSHI) of dendritic spines and the brain extracellular space.
importance: 1
category: Past projects
---

Conventional fluorescence microscopy is limited by diffraction to about 250 nm — too coarse to resolve many neuronal structures. **STED microscopy** [(Hell & Wichmann, 1994)](https://doi.org/10.1364/OL.19.000780) breaks this limit by adding, on top of the excitation spot, a doughnut-shaped depletion beam that switches off fluorescence everywhere except at its very centre: the effective focal spot shrinks well below the diffraction limit, down to a few tens of nanometres. Shaping this depletion beam (2D, z or 3D STED) tailors the resolution gain in the lateral and axial directions.

<div class="proj-figrow">
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid loading="eager" path="assets/img/sted_fig1.png" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="proj-cap">
    <p class="caption" style="text-align: justify;">STED principle: a doughnut-shaped depletion beam confines fluorescence to a sub-diffraction spot (a); the STED microscope (c); and the resulting PSFs and beads for 2P, 2D-, z- and 3D-STED (d–e).</p>
  </div>
</div>

Applied **in vivo**, STED makes it possible to image dendritic spines — the tiny postsynaptic compartments that underlie synaptic plasticity — directly in the brain of a living mouse, through a cranial window and at nanoscale resolution [(Bancelin et al., 2023)](https://doi.org/10.1117/1.nph.10.4.044402). Chronic, time-lapse imaging then reveals how individual spines change shape and turn over in their native environment.

<div class="proj-figrow">
  <div class="proj-cap">
    <p class="caption" style="text-align: justify;">In vivo STED imaging of dendritic spines along a dendrite in the living mouse brain (top, 14×7 µm²), and a 3D comparison of a spine imaged with two-photon vs STED microscopy (bottom).</p>
  </div>
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid path="assets/img/sted_fig2.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

A complementary approach, **super-resolution shadow imaging (SUSHI)** [(Tønnesen et al., 2018)](https://doi.org/10.1016/j.cell.2018.02.007), flips the contrast: instead of labelling sparse structures, the extracellular space is filled with a fluorescent dye, so that every cell and process appears as a dark "shadow" against the bright background. A single STED acquisition then reveals the complete, densely-packed anatomy of the tissue — neurons, glia, blood vessels and the extracellular space itself — non-invasively and in vivo.

<div class="proj-figrow">
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid path="assets/img/sted_fig3.png" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="proj-cap">
    <p class="caption" style="text-align: justify;">SUSHI (super-resolution shadow imaging): the extracellular space is labelled so that cells and processes appear as dark shadows, revealing the full tissue anatomy in vivo.</p>
  </div>
</div>