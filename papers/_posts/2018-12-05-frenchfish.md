---
layout: paper
title: "FrenchFISH: Poisson models for quantifying DNA copy-number from fluorescence in situ hybridisation of tissue sections"
image: /images/papers/macintyre-frenchfish.png
authors:  Geoff Macintyre, Anna M. Piskorz, Edith Ross, David B. Morse,  Ke Yuan, Darren Ennis, Jeremy A. Pike, Teodora Goranova,  Iain A. McNeish,  James D. Brenton,  Florian Markowetz.
year: 2018
ref: Macintyre et al. 2018. bioRxiv.
journal: "bioRxiv 487926."
doi: 10.1101/487926
---

# Abstract

Chromosomal aberration and DNA copy number change are robust hallmarks of cancer. Imaging of spots generated using fluorescence in situ hybridisation (FISH) of locus specific probes is routinely used to detect copy number changes in tumour nuclei. However, it often does not perform well on solid tumour tissue sections, where partially represented or overlapping nuclei are common. To overcome these challenges, we have developed a computational approach called FrenchFISH, which comprises a nuclear volume correction method coupled with two types of Poisson models: either a Poisson model for improved manual spot counting without the need for control probes; or a homogenous Poisson Point Process model for automated spot counting. We benchmarked the performance of FrenchFISH against previous approaches in a controlled simulation scenario and exemplify its use in 12 ovarian cancer FFPE-tissue sections, for which we assess copy number alterations in three loci (c-Myc, hTERC and SE7). We show that FrenchFISH outperforms standard spot counting approaches and that the automated spot counting is significantly faster than manual without loss of performance. FrenchFISH is a general approach that can be used to enhance clinical diagnosis on sections of any tissue.