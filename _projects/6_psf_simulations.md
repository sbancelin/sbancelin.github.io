---
layout: page
title: PSF simulation and Adaptive optics
description: Vectorial simulation of the point-spread function (FASER) and adaptive-optics aberration correction for deep STED microscopy.
importance: 2
category: Past projects
---

In STED microscopy, resolution is created by a doughnut-shaped depletion beam that switches off fluorescence everywhere except at its central zero. The quality of that zero — and therefore the resolution — depends critically on the exact shape of the point-spread function (PSF), which is extremely sensitive to the beam polarization, to the objective and to the optical properties of the sample. Being able to **simulate the vectorial PSF** realistically [(Török et al., 1995)](https://doi.org/10.1364/JOSAA.12.000325) is thus essential to design, align and interpret a STED microscope. To this end we developed **[FASER](https://github.com/jhnnsrs/faser)**, an open-source tool that computes the focal field for arbitrary polarization states and refractive-index conditions, with an interactive Napari interface for single or batch simulations.

<div class="proj-figrow">
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid loading="eager" path="assets/img/psf_fig1.png" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="proj-cap">
    <p class="caption" style="text-align: justify;">FASER: (a) vectorial focusing model accounting for polarization and refractive-index mismatch, (b) the Napari-based interface, and (c) simulated PSFs (xy and xz) for different polarization states and degrees of depolarization (<a href="https://doi.org/10.1117/1.nph.12.1.017801">Roos et al., 2025</a>).</p>
  </div>
</div>

Deep inside tissue, optical aberrations distort the doughnut, fill in its central zero and quickly destroy the STED resolution. By modelling how each aberration (defocus, astigmatism, coma, spherical…) deforms the PSF, the dominant, depth-dependent terms can be identified and pre-compensated with **adaptive optics** [(Booth, 2014)](https://doi.org/10.1038/lsa.2014.46). Correcting the leading aberration as a function of depth restores the depletion zero, recovers signal and preserves nanoscale resolution much deeper into living brain tissue.

<div class="proj-figrow">
  <div class="proj-cap">
    <p class="caption" style="text-align: justify;">Effect of aberrations on the STED PSF (a–b) (<a href="https://doi.org/10.1117/1.nph.12.1.017801">Roos et al., 2025</a>) and depth-dependent aberration correction: the optimal correction varies linearly with depth (c), restoring signal (d) and preserving resolution (mean spine-neck diameter) far deeper than the uncorrected case (e) (<a href="https://doi.org/10.1117/1.nph.8.3.035001">Bancelin et al., 2021</a>).</p>
  </div>
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid path="assets/img/psf_fig2.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>