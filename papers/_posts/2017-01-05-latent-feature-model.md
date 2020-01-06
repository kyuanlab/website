---
layout: paper
title: A phylogenetic latent feature model for clonal deconvolution
image: /images/papers/marass-latent.png
authors: Francesco Marass, Florent Mouliere, Ke Yuan, Nitzan Rosenfeld, Florian Markowetz.
year: 2016
ref: Marass et al. 2016. Ann. Appl. Stat.
journal: "The Annals of Applied Statistics Volume 10, Number 4 (2016), 2377-2404."
doi: doi:10.1214/16-AOAS986
---

# Abstract

Tumours develop in an evolutionary process, in which the accumulation of mutations produces subpopulations of cells with distinct mutational profiles, called clones. This process leads to the genetic heterogeneity widely observed in tumour sequencing data, but identifying the genotypes and frequencies of the different clones is still a major challenge. Here, we present Cloe, a phylogenetic latent feature model to deconvolute tumour sequencing data into a set of related genotypes. Our approach extends latent feature models by placing the features as nodes in a latent tree. The resulting model can capture both the acquisition and the loss of mutations, as well as episodes of convergent evolution. We establish the validity of Cloe on synthetic data and assess its performance on controlled biological data, comparing our reconstructions to those of several published state-of-the-art methods. We show that our method provides highly accurate reconstructions and identifies the number of clones, their genotypes and frequencies even at a modest sequencing depth. As a proof of concept, we apply our model to clinical data from three cases with chronic lymphocytic leukaemia and one case with acute myeloid leukaemia.