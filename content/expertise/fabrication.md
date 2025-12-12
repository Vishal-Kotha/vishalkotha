---
title: "Nanodevice Fabrication (Lithography)"
date: 2024-01-01
cover:
    image: "/images/action-ebl.jpg"
    alt: "Electron Beam Lithography System"
description: "Design and fabrication of sub-10nm device architectures for quantum transport."
weight: 1
---

### The Engineering Challenge
Extracting intrinsic electronic properties (carrier density, mobility) from novel nanomaterials requires establishing **Ohmic contacts** with minimal Schottky barriers. Standard 2-probe measurements often fail due to contact resistance dominating the signal.

### Methodology: The 5-Probe Architecture
To overcome geometric crosstalk between longitudinal ($R_{xx}$) and transverse ($R_{xy}$) voltages, I optimized a **5-Probe Asymmetric Hall Bar** geometry.

**Fabrication Workflow:**
1.  **Substrate Prep:** Silicon/SiO2 wafers cleaned via Piranha etch and $O_2$ plasma.
2.  **Resist Coating:** Spin-coating PMMA (A4) bi-layer resists for optimal lift-off profiles.
3.  **Patterning:** Using **Electron Beam Lithography (EBL)** to define sub-micron electrode paths. 

[Image of Electron Beam Lithography schematic]

4.  **Metallization:** E-beam evaporation of Ti/Au (5nm/50nm) followed by lift-off in acetone.

### Visual Evidence
<div class="project-grid">
    <figure>
        <a href="/images/device-5probe.jpg" class="lightbox-trigger" data-caption="Optical micrograph of the fabricated 5-probe device. The asymmetric design ensures precise separation of Hall and Longitudinal signals.">
            <img src="/images/device-5probe.jpg" alt="5-Probe Device">
        </a>
        <figcaption>Figure 1: Custom 5-Probe Hall Device</figcaption>
    </figure>
    <figure>
        <a href="/images/action-ebl.jpg" class="lightbox-trigger" data-caption="Optimizing dose parameters on the EBL system to correct for proximity effects.">
            <img src="/images/action-ebl.jpg" alt="EBL Operation">
        </a>
        <figcaption>Figure 2: Lithography Optimization</figcaption>
    </figure>
</div>