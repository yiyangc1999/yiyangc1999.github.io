---
layout: archive
title: "Research Experiences"
permalink: /research-experiences/
author_profile: true
---

## Washington University in St. Louis

### Multidimensional Single-Molecule Nanoscopy to Elucidate the Structure and Conformational Dynamics of Cell Membrane Proteins

*2022 - present | Advisor: Dr. Matthew D. Lew*

My doctoral research lies in single-molecule orientation-localization microscopy (SMOLM), where I ask questions about how to extract information from the images from individual fluorophores and how much can we learn from those information. My work spans the full imaging pipeline: I formulate mathematical models, develop computational methods, build and characterize optical systems, and apply these tools to biological questions. Ultimately, I aim to acquire information that conventional spatial images cannot provide, including local chemical environments, fluorophore-target interactions, and the conformational dynamics of membrane proteins.

**Theoretical modeling.** Distinguishing closely spaced emitters is a fundamental challenge in optical imaging since the discovery of Rayleigh's curse. I approached this problem from an orientational perspective: can two spatially overlapping molecules with different orientations be distinguished through their polarization signatures? I demonstrated that SMOLM methods that modulate only excitation or only emission cannot distinguish a pair of dipole emitters from a single rotating emitter because these methods measure only second-order orientational moments. In collaboration with Yuanxin Qiu, I then designed a joint excitation-and-emission modulation scheme that accesses fourth-order orientational moments. This higher-dimensional measurement resolves the ambiguity between the two cases and improves the precision of angular-separation measurements by 200%–400%. Inspired this study, I am now investigating how direct measurements of fourth-order moments can improve the accuracy and precision of measuring rotational dynamics at the single-molecule level.

**Computational imaging and optical systems.** I build computational tools to extract information efficiently from single-molecule images. I started with dipole-spread function (DSF) engineering, using convex optimization to maximize Fisher information for targeted molecular orientations. I also contribute to DeepSMOLM3D, a deep-learning algorithm for estimating 3D localization and 3D orientation sequentially, with a focus on physics-informed network training and validation. Across simulations and cell-membrane experiments spanning a range of molecular densities and signal levels, DeepSMOLM3D outperforms traditional maximum-likelihood estimation in accuracy, precision, and reconstruction speed. I also had the experience of building and aligning a dual-polarization 4f optical system that uses a spatial light modulator (SLM) for phase modulation and DSF engineering, enabling accurate and precise SMOLM measurements.

**Biophysical and biochemical applications.** I apply SMOLM to diverse biological systems to demonstrate the information that multidimensional single-molecule imaging can reveal. First, I measured the orientations of lipophilic fluorogenic dyes—including Nile Red, Nile Blue, and Merocyanine 540—on supported lipid bilayers and cell membranes, showing that these dyes adopt distinct orientations upon membrane binding. Second, in collaboration with the [Dai Lab](https://sites.wustl.edu/dailab/), I used hydroxyphenyl fluorescein (HPF) for single-molecule imaging of redox reactions within biomolecular condensates, showing interface-dependent redox reaction activity in G3BP1 condensates. Finally, in collaboration with the [Vahey Lab](https://vaheylab.wustl.edu/), I am designing and characterizing protein-labeling strategies that rigidly couple fluorophores to proteins of interest. This work seeks to establish a platform for inferring membrane-protein conformational dynamics from fluctuations in fluorophore orientation.

<!-- Together, these projects form an integrated research program that connects mathematical theory, computational analysis, optical instrumentation, and biological discovery. -->

<!-- A full list of my papers and talks is available on the [Publications](/publications/) page. -->


## Nankai University

### The Study of Deformability of Human Erythrocyte Based on Microfluidics

*2019 - 2021 | Advisor: Dr. Leiting Pan*

My undergraduate research explored the membrane structure and properties of human red blood cells. On the macroscopic level, I quantified cell deformability by measuring how fast cells traveled through narrow microfluidic channels, then designed and simulated a microfluidic ratchet chip in COMSOL Multiphysics to test whether cells could be sorted by age-related differences in deformability. On the microscopic level, I turned to single-molecule localization microscopy (SMLM), analyzing the actin-spectrin network and the diffusivity of CD47 on red blood cell membranes. This project was my first exposure to single-molecule imaging and to the connection between physical measurement, optical instrumentation, and biological function — a connection that continues to shape my research today.
