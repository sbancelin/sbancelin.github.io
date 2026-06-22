---
layout: page
title: SHG imaging of connective tissues
description: Second-harmonic generation imaging of collagen architecture and biomechanics in connective tissues.
importance: 2
category: Current projects
---

Second-harmonic generation (SHG) is a **coherent** nonlinear process in which two photons of frequency ω are converted into a single photon at 2ω [(Campagnola & Loew, 2003)](https://doi.org/10.1038/nbt894). Unlike fluorescence, it requires no label and is emitted only by **non-centrosymmetric, dense and well-aligned** structures: because the process is coherent, the signal builds up as the square of the number of aligned emitters and vanishes when neighbouring emitters point in opposite directions. In biological tissue, only a handful of structures meet these conditions — most prominently **fibrillar collagen** [(Freund et al., 1986)](https://doi.org/10.1016/S0006-3495(86)83510-X), but also myosin in muscle and microtubules — which makes SHG an intrinsically specific, label-free probe of these assemblies.

<div class="proj-figrow">
  <div style="flex: 0 0 60%; max-width: 60%;">
    {% include figure.liquid loading="eager" path="assets/img/shg_fig1.png" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="proj-cap">
    <p class="caption">Principle of SHG (a): two photons at ω combine coherently into one photon at 2ω; the signal scales with the square of the aligned emitters and cancels for antiparallel arrangements. (b–e) the rare biological sources of SHG, dominated by fibrillar collagen.</p>
  </div>
</div>

Collagen is the main load-bearing protein of the body, and SHG gives a direct, three-dimensional view of its organisation in **connective tissues** — tendon, ligament, cornea, cartilage, skin, blood vessels. Each tissue has a characteristic collagen architecture that underlies its specific mechanical response: under load, fibres straighten, reorient and slide, producing the non-linear stress–strain behaviour typical of these tissues. By imaging collagen with SHG while the tissue is mechanically tested, we relate microscopic structural changes to the macroscopic **biomechanics**.

<div class="proj-figcenter" style="width: 60%;">
  {% include figure.liquid path="assets/img/shg_fig2.png" class="img-fluid rounded z-depth-1" caption="Collagen-rich connective tissues (a) and their characteristic non-linear stress–strain behaviour (b), set by the reorientation, straightening and sliding of the fibres; (c–h) SHG imaging of collagen across tissues." %}
</div>

Turning these images into numbers requires dedicated **image analysis**. From SHG images we quantify, for example, an orientation index that measures how aligned the collagen fibres are. In **skin**, following this index during a traction assay reveals how the initially crimped, randomly-oriented collagen network progressively straightens and aligns along the loading axis — directly correlating the optical measurement with the successive mechanical regimes of the tissue (toe, heel, linear) up to rupture.

{% include figure.liquid path="assets/img/shg_fig3.png" class="img-fluid rounded z-depth-1" caption="Image analysis of skin mechanics: the collagen orientation index extracted from SHG images is followed during a traction assay (a, schematic) and correlated with the measured stress–strain response (b), linking fibre reorientation to the mechanical regimes of skin." %}