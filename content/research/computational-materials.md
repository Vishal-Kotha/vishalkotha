---
title: "Computational Materials Science: Boron Carbide"
date: 2016-06-01
description: "Ab-initio DFT calculations on the failure mechanisms of bulletproof armor."
tags: ["DFT", "Python", "Simulation"]
cover:
    image: "/images/boron-carbide.jpg"
    alt: "Boron Carbide"
    relative: false
weight: 4
---

### The Mystery of Boron Carbide
Boron Carbide ($B_4C$) is used in bulletproof jackets due to its hardness (30 GPa). However, it fails unexpectedly under high-velocity impact.

<div style="text-align: center; margin: 30px 0;">
    <img src="/images/boron-carbide.jpg" alt="Rhombohedral Structure of Boron Carbide" style="height: 300px; width: auto; object-fit: contain; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
    <p style="font-size: 0.9rem; color: #666; margin-top: 10px;">
        <strong>Figure 1:</strong> The Rhombohedral unit cell structure of Boron Carbide.
    </p>
</div>

### Methodology
During my M.Sc., I utilized **Density Functional Theory (DFT)** codes (VASP, Gaussian) to model the atomic bonding and identify structural weaknesses.

<div style="text-align: center; margin: 30px 0;">
    <img src="/images/vasp-model.jpg" alt="VASP Model" style="height: 300px; width: auto; object-fit: contain; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
    <p style="font-size: 0.9rem; color: #666; margin-top: 10px;">
        <strong>Figure 2:</strong> Electron density mapping generated using VASP.
    </p>
</div>

### Discovery
* **Bonding Analysis:** Identified that specific weak B-B bonds in the inter-polyhedral chains cause structural collapse under high pressure.

<div style="text-align: center; margin: 30px 0;">
    <img src="/images/crack-plane.jpg" alt="Crack Plane Analysis" style="height: 300px; width: auto; object-fit: contain; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
    <p style="font-size: 0.9rem; color: #666; margin-top: 10px;">
        <strong>Figure 3:</strong> Visualization of the crack plane propagation in the crystal lattice.
    </p>
</div>

* **Data Engineering:** Implemented Python and SQL scripts for efficient bookkeeping of simulation results and literature data.

---
### 💻 Open Source Contribution
I have open-sourced the Python scripts used for plotting the XRD data and automating the VASP log parsing.

[View Code on GitHub ↗](https://github.com/vishalkotha)