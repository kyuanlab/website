---
layout: paper
title: "Pathology GAN: Learning deep representations of cancer tissue"
image: /images/papers/adal-pathgan.png
authors: Adalberto Claudio Quiros, Roderick Murray-Smith, Ke Yuan
year: 2020
ref: Quiros et al. 2020. MIDL.
journal: "Medical Imaging with Deep Learning (MIDL)"
github: https://github.com/AdalbertoCq/Pathology-GAN
arxiv: arXiv:1907.02644 
---

# Abstract

We apply Generative Adversarial Networks (GANs) to the domain of digital pathology.
Current machine learning research for digital pathology focuses on diagnosis, but we suggest a different approach and advocate that generative models could drive forward the
understanding of morphological characteristics of cancer tissue. In this paper, we develop
a framework which allows GANs to capture key tissue features and uses these characteristics to give structure to its latent space. To this end, we trained our model on 249K
H&E breast cancer tissue images, extracted from 576 TMA images of patients from the
Netherlands Cancer Institute (NKI) and Vancouver General Hospital (VGH) cohorts.

We show that our model generates high quality images, with a Fr´echet Inception Distance (FID) of 16.65. We further assess the quality of the images with cancer tissue
characteristics (e.g. count of cancer, lymphocytes, or stromal cells), using quantitative
information to calculate the FID and showing consistent performance of 9.86. Additionally, the latent space of our model shows an interpretable structure and allows semantic
vector operations that translate into tissue feature transformations. Furthermore, ratings
from two expert pathologists found no significant difference between our generated tissue
images from real ones. The code, generated images, and pretrained model are available at
https://github.com/AdalbertoCq/Pathology-GAN
