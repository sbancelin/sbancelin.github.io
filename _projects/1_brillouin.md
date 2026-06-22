---
layout: page
title: Brillouin microscopy
description: Brillouin microscopy recently emerged as a non-contact technique to probe the mechanical response of biological materials.
importance: 1
category: Current projects
---

Brillouin microscopy measures the **mechanical response** of a material all-optically and without any contact [(Scarcelli & Yun, 2008)](https://doi.org/10.1038/nphoton.2007.250). When light propagates through a sample, it is scattered by thermally-driven acoustic waves (phonons): the scattered light is frequency-shifted by ±ν<sub>B</sub> — the Brillouin shift — around the elastic (Rayleigh) line. This shift is directly related to the **longitudinal elastic modulus** (through the speed of sound and the density), while the linewidth reflects the viscosity. Measuring ν<sub>B</sub> point by point yields a quantitative, label-free map of the local stiffness.

<div class="proj-figrow">
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid loading="eager" path="assets/img/brillouin_fig1.png" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="proj-cap">
    <p class="caption">Brillouin scattering: light exchanges energy with acoustic phonons, giving Stokes / anti-Stokes peaks shifted by ±ν<sub>B</sub> around the elastic line. The shift ν<sub>B</sub> encodes the longitudinal modulus, its width the viscosity.</p>
  </div>
</div>

The main experimental challenge is that the Brillouin signal is extremely weak and sits only a few GHz away from the much stronger elastic line. This calls for a spectrometer that is both high-resolution and high-extinction. We use a **VIPA spectrometer**: a VIPA is a tilted, partially-reflective etalon that angularly disperses the optical frequencies, turning a tiny GHz shift into a measurable displacement on the camera. Crossing two VIPAs and adding a spatial mask rejects the residual elastic light and provides the extinction needed to recover the Brillouin peaks.

<div class="proj-figcenter" style="width: 90%;">
  {% include figure.liquid path="assets/img/brillouin_fig2.png" class="img-fluid rounded z-depth-1" caption="The two-VIPA Brillouin spectrometer: optical layout (left), raw dispersed pattern on the camera (centre) and resulting spectral response (right), with a measured free spectral range of ≈ 28.9 GHz." %}
</div>

As a proof of concept, we image a polystyrene bead immersed in water: the maps of Brillouin shift, linewidth and intensity clearly resolve the mechanical contrast between the stiff bead and its soft surroundings.

<div class="proj-figrow">
  <div style="flex: 0 0 48%; max-width: 48%;">
    {% include figure.liquid path="assets/img/brillouin_fig3.png" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="proj-cap">
    <p class="caption">Brillouin imaging of a polystyrene bead — maps of the Brillouin shift, linewidth and peak intensity (scale bar 4 µm).</p>
  </div>
</div>

The goal is now to apply this approach to **soft connective tissues** — vocal cords, cartilage, cornea — to probe their biomechanics in situ [(Prevedel et al., 2019)](https://doi.org/10.1038/s41592-019-0543-3). Combined with **second-harmonic generation** imaging of the collagen network, Brillouin microscopy lets us correlate the architecture of the tissue with its local mechanical properties, linking structure and function at the microscale.