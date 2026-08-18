---
layout: archive
title: "Research Experiences"
permalink: /research-experiences/
author_profile: true
---

## Washington University in St. Louis

### Multi-dimensional Single Molecule Nanoscopy to Elucidate the Structure and Conformational Dynamics of Cell Membrane Proteins

*2022 - present | Advisor: Dr. Matthew D. Lew*

My doctoral research asks how much we can learn about the orientation and rotational dynamics of individual molecules from the light they emit. I work in single-molecule orientation-localization microscopy (SMOLM), combining theoretical modeling, optical engineering, and computational imaging to measure molecular position and orientation at the nanoscale, with the ultimate goal of using these measurements to read out the structure and conformational dynamics of cell membrane proteins.

**Theoretical modeling.** One central challenge in SMOLM is distinguishing two molecules whose images spatially overlap. I discovered a fundamental degeneracy that limits how precisely this can be measured and proved mathematically that resolving certain orientational differences requires access to fourth-order orientation moments — information standard methods never collect. Building on this result, I designed an imaging strategy that combines excitation-polarization modulation with an engineered dipole-spread function (DSF), improving angular-separation precision by 200-400% and centroid-orientation precision by roughly 50% over the state of the art. This work was published in *Physical Review Letters* (2025) and presented at the Optica Biophotonics Congress (2025). I'm now extending it to directly measure fourth-order moments, widening the range of orientational dynamics we can observe.

**Computational imaging.** I build computational tools that turn these theoretical insights into practical imaging methods: engineering DSFs by maximizing Fisher information through convex optimization, and designing a physics-informed data-generation pipeline that produces high-fidelity training data for DeepSMOLM3D, a deep-learning estimator for sequential 3D localization and orientation. Across simulations and cell-membrane experiments spanning a range of molecular densities and signal levels, DeepSMOLM3D outperforms traditional maximum-likelihood estimation in accuracy, precision, and reconstruction speed; this work is currently in preparation for publication with co-first-author Xiao Li.

**Optical systems & biophysical applications.** Experimentally, I built and calibrated a dual-polarization 4f microscope with spatial-light-modulator-based phase control. I use this system to perform PAINT imaging of supported lipid bilayers and cell membranes with fluorogenic probes, revealing how probe chemistry shapes measured binding and rotational dynamics — work synthesized, together with the lab's broader body of SMOLM research, in an invited review in *Accounts of Chemical Research* (2026). I've also contributed to a lab collaboration on fused deep learning for 6D single-molecule localization, published in *Methods and Applications in Fluorescence* (2026). My current work develops protein-tag-based labeling strategies to measure membrane-protein orientation and rotational dynamics directly in living cells.

A full list of my papers and talks is available on the [Publications](/publications/) page.


## Nankai University

### The Study of Deformability of Human Erythrocyte Based on Microfluidics

*2019 - 2021 | Advisor: Dr. Leiting Pan*

My undergraduate research examined how the mechanical properties of human red blood cells relate to their membrane organization. I quantified cell deformability by measuring how fast cells traveled through narrow microfluidic channels, then designed and simulated a microfluidic ratchet chip in COMSOL Multiphysics to test whether cells could be sorted by age-related differences in deformability.

To examine the membrane at a smaller scale, I turned to single-molecule localization microscopy (SMLM), analyzing the actin-spectrin network and the diffusivity of CD47 on red blood cell membranes. This project was my first exposure to single-molecule imaging and to the connection between physical measurement, optical instrumentation, and biological function — a connection that continues to shape my research today.
