---
layout: page
title: Brillouin microscopy
description:
importance: 1
category: Current projects
---

Brillouin microscopy measures the **mechanical response** of a material all-optically and without any contact. When light propagates through a sample, it is scattered by thermally-driven acoustic waves (phonons): the scattered light is frequency-shifted by ±ν<sub>B</sub> — the Brillouin shift — around the elastic (Rayleigh) line. This shift is directly related to the **longitudinal elastic modulus** (through the speed of sound and the density), while the linewidth reflects the viscosity. Measuring ν<sub>B</sub> point by point therefore yields a quantitative, label-free map of the local stiffness of the sample.

{% include figure.liquid loading="eager" path="assets/img/brillouin_fig1.png" class="img-fluid rounded z-depth-1" caption="Brillouin scattering: the incident light exchanges energy with acoustic phonons, producing Stokes / anti-Stokes peaks shifted by ±ν<sub>B</sub> on either side of the elastic line. The shift ν<sub>B</sub> encodes the longitudinal modulus, its width the viscosity." %}

The main experimental challenge is that the Brillouin signal is extremely weak and sits only a few GHz away from the much stronger elastic line. This calls for a spectrometer that is both high-resolution and high-extinction. We use a **VIPA spectrometer**: a VIPA is a tilted, partially-reflective etalon that angularly disperses the optical frequencies, turning a tiny GHz shift into a measurable displacement on the camera. Crossing two VIPAs and adding a spatial mask rejects the residual elastic light and provides the extinction needed to recover the Brillouin peaks.

{% include figure.liquid path="assets/img/brillouin_fig2bis.png" class="img-fluid rounded z-depth-1" caption="Spectral response of the cross-axis two-VIPA spectrometer. The mask suppresses the strong elastic line, giving the extinction required to detect the weak Brillouin signal (here the water peak); the measured free spectral range is ≈ 28.9 GHz." %}

As a proof of concept, we image a polystyrene bead immersed in water: the maps of Brillouin shift, linewidth and intensity clearly resolve the mechanical contrast between the stiff bead and its soft surroundings.

{% include figure.liquid path="assets/img/brillouin_fig3.png" class="img-fluid rounded z-depth-1" caption="Brillouin imaging of a polystyrene bead — maps of the Brillouin shift, linewidth and peak intensity (scale bar 4 µm)." %}

The goal is now to apply this approach to **soft connective tissues** — vocal cords, cartilage, cornea — to probe their biomechanics in situ. Combined with **second-harmonic generation** imaging of the collagen network, Brillouin microscopy lets us correlate the architecture of the tissue with its local mechanical properties, linking structure and function at the microscale.