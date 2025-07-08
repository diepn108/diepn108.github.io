---
layout: post
title: Review of Advances in Microwave and Millimetre-Wave NDT&E
subtitle: Principles and Applications
gh-badge: [star, fork, follow]
tags: [NDT&E, microwave, millimetre-wave, material characterization, surface crack detection, imaging, sensing]
category: NDE
comments: true
mathjax: true
author: Ngoc Diep Nguyen
---

{: .box-success}
This post reviews the paper *Review of advances in microwave and millimetre-wave NDT&E: principles and applications* by Brinker et al., covering key techniques in non-destructive testing and evaluation (NDT&E) using microwave and millimetre-wave technologies.

## Introduction

Non-Destructive Testing and Evaluation (NDT&E) inspects materials and structures without causing damage. Microwave and millimetre-wave NDT&E, operating between 300 MHz and 300 GHz, offer high-resolution flaw detection, particularly in dielectric materials. These methods are non-contact, low-power, real-time, and automation-compatible, making them cost-effective. This review explores four key techniques: **material characterization**, **surface crack detection**, **imaging**, and **sensing**.

## Material Characterization

Material characterization assesses complex permittivity (\(\varepsilon_r\)) and permeability (\(\mu_r\)) to reveal a material’s composition and condition. The real part of permittivity indicates energy storage, while the imaginary part (loss factor) shows energy absorption. Techniques include resonant, transmission/reflection, and imaging methods, sensitive to sample preparation, moisture, and temperature. Outputs include impedance, S-parameters, or Q-factors. Applications range from polymer curing to detecting porosity in ceramics.

### Resonant Techniques

Resonant techniques measure dielectric properties by analyzing resonance frequency and Q-factor shifts. Key methods include:

1. **Resonant/Re-entrant Cavity**: Highly accurate for low-loss materials but often destructive due to sample shaping requirements.

   ![Re-entrant Cavity](https://www.nature.com/articles/s41598-022-08662-7/figures/1){: .mx-auto.d-block :}
   *Source: https://www.nature.com/articles/s41598-022-08662-7*

   - **Panel (a)**: 3D cylindrical view with a central post creating a narrow gap for a strong electric field (E-field).
   - **Panel (b)**: Cross-sectional view showing:
     - Dimensions: cavity diameter (2b), post diameter (2a), length (l), gap distance (d).
     - TE\(_{111}\) mode field distribution: magnetic (H-field) and electric (E-field) fields.

2. **Split-Cylinder Resonator**: Non-destructive for thin materials placed between cavity halves.

   ![Split-Cylinder Resonator](https://www.researchgate.net/figure/Cross-sectional-diagram-of-a-split-cylinder-resonator_fig2_346761871){: .mx-auto.d-block :}
   *Source: https://www.researchgate.net/figure/Cross-sectional-diagram-of-a-split-cylinder-resonator_fig2_346761871*

   - Cross-sectional view showing two cylindrical cavities (height L, radius a) with a thin sample (thickness d) between them.
   - Coupling loops introduce microwave energy, and resonant frequency shifts determine permittivity.

3. **Microstrip Resonator**: Measures resonance shifts when a material is placed on a resonator.

   ![Microstrip Ring Resonator](https://www.researchgate.net/figure/Microstrip-ring-resonator-configuration-diagram_fig1_3132115){: .mx-auto.d-block :}
   *Source: https://www.researchgate.net/figure/Microstrip-ring-resonator-configuration-diagram_fig1_3132115*

   - **Panel (a)**: Ring resonator with capacitive coupling via feedlines.
   - **Panel (b)**: Two-port setup for S-parameter measurements.

4. **Dielectric Resonator**: Suitable for liquids, powders, or thin films.

   ![Dielectric Resonator](https://www.researchgate.net/figure/Dielectric-resonator-a-Side-view-b-top-view-c-E-field-of-TE-01d-mode-d_fig1_373957053){: .mx-auto.d-block :}
   *Source: https://www.researchgate.net/figure/Dielectric-resonator-a-Side-view-b-top-view-c-E-field-of-TE-01d-mode-d_fig1_373957053*

   - **Side View**: Shows dielectric disk (diameter D, height H) on a metal post.
   - **Top View**: Displays field patterns for various resonant modes.

5. **Open Resonator**: Non-contact, broadband testing using two reflectors.

   ![Open Resonator](https://www.researchgate.net/figure/Open-resonator-system-for-reflectarray-elements-characterization_fig3_230560413){: .mx-auto.d-block :}
   *Source: https://www.researchgate.net/figure/Open-resonator-system-for-reflectarray-elements-characterization_fig3_230560413*

   - Features a spherical and plane mirror forming a resonant cavity with a sample at the beam waist.

### Transmission and Reflection Techniques

- **Reflection Methods**: Use open-ended coaxial or waveguide probes. Coaxial probes are ideal for liquids and thin layers, while waveguides suit thick or multilayer materials.
- **Transmission/Reflection Methods**: Measure S\(_{11}\) and S\(_{21}\) parameters using coaxial lines, waveguides, coplanar waveguides, microstrips, or free-space systems. Free-space methods are non-contact and ideal for high-temperature tests.

## Surface Crack Detection

Microwave and millimetre-wave techniques detect surface-breaking cracks in metals by analyzing scattered waves caused by disrupted surface currents. Key probes include:

- **Open-Ended Waveguide Probe**: Uses TE mode to detect cracks perpendicular to current flow.
- **Open-Ended Coaxial Probe**: Wideband, high-resolution, but sensitive to geometry.
- **Resonant Probes**: Detect cracks via resonant frequency shifts using split-ring resonators or microstrip lines.

## Imaging

Microwave and millimetre-wave imaging maps electromagnetic properties like permittivity, permeability, or reflectivity. Techniques include:

- **Near-Field Imaging**: High-resolution flaw detection using probes like waveguides or coaxial lines.
- **Far-Field Imaging**: Uses lens antennas for thick structures at millimetre-wave frequencies.
- **Synthetic Aperture Radar (SAR)**: Simulates a large aperture for high-resolution 2D/3D imaging. Advanced methods like Piecewise SAR and Wiener-filter Layered SAR handle multilayered structures.

## Sensors and Sensing

Sensors measure parameters like temperature, strain, or dielectric properties. Categories include:

- **Transmission Media Probes**: Coaxial cables for strain sensing; waveguides for thickness or corrosion detection.
- **Wired Solutions**: Modulated scatter technique probes and microstrip patch antennas for embedded sensing.
- **Wireless Passive Sensors**: Frequency selective surfaces and chipless RFID tags for battery-free sensing of cracks, humidity, or temperature.

## Conclusion

Microwave and millimetre-wave NDT&E techniques offer versatile, high-resolution solutions for material characterization, crack detection, imaging, and sensing. Advances in miniaturization, algorithms, and sensor design continue to expand their industrial applications.
