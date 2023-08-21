---
title: "DP-NTK"
collection: publications
permalink: /publication/DP_NTK
excerpt: 'Differentially Private Neural Tangent Kernels for Privacy-Preserving Data Generation'
date: 2023-08-21
venue: 'arXiv'
paperurl: 'https://CRAN.R-project.org/package=GaSP'
citation: 'Yilin Yang, Kamil Adamczewski, Danica J. Sutherland, Xiaoxiao Li, & Mĳung Park. (2023). Differentially Private Neural Tangent Kernels for Privacy-Preserving Data Generation'
---
Differentially Private Neural Tangent Kernels for Privacy-Preserving Data Generation

Abstract:

Maximum mean discrepancy (MMD) is a particularly useful distance metric for differentially private data generation: when used with finite-dimensional features it allows us to summarize and privatize the data distribution once, which we can repeatedly use during generator training without further privacy loss. An important question in this framework is, then, what features are useful to distinguish between real and synthetic data distributions, and whether those enable us to generate quality synthetic data. This work considers the using the features of neural tangent kernels (NTKs), more precisely empirical NTKs (e-NTKs). We find that, perhaps surprisingly, the expressiveness of the untrained e-NTK features is comparable to that of the features taken from pre-trained perceptual features using public data. As a result, our method improves the privacy-accuracy trade-off compared to other state-of-the-art methods, without relying on any public data, as demonstrated on several tabular and image benchmark datasets.