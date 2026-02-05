---
title: "Exploring SRGAN-Based Model for Image Super-Resolution"
collection: publications
category: manuscripts
permalink: /publication/exploring-srgan-based-model-for-image-super-resolution
excerpt: "This paper explores the performance of SRGAN and SRResNet architectures for image super-resolution under different training strategies and evaluation metrics."
date: 2024-11-01
venue: "CONF-MLA 2024 Workshop on Semantic Communication Based Complexity Scalable Image Transmission System for Resource-Constrained Devices"
paperurl: "/files/Exploring_SRGAN-Based_Model_for_Image_Super-Resolu.pdf"
citation: "Yang, R. (2024). <i>Exploring SRGAN-Based Model for Image Super-Resolution</i>. Proceedings of the CONF-MLA 2024 Workshop on Semantic Communication Based Complexity Scalable Image Transmission System for Resource-Constrained Devices."
---

### Abstract

Transforming low-resolution (LR) images into their high-resolution (HR) counterparts is a challenging endeavor, referred to as image super-resolution (SR). The emphasis of this 
research is on the Super-Resolution Generative Adversarial Network (SRGAN), a sophisticated deep learning approach that can generate aesthetically pleasing high-resolution images. 

Initially, a backbone model is trained with mean squared error (MSE) loss function to enhance image details. Then, the author took this pretrained the backbone and used it to initialize the generator part of SRGAN, after which the author performed adversarial training where various content accuracy - visual realism tradeoffs were considered during optimization process. This work tested models on standard benchmarks like Set5, Set14, and BSD100 with Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM). 

The best results were achieved when using intermediate learning rates combined with 16 batch size – those settings resulted in highest PSNR and SSIM values across all datasets that have been tested. 

To sum up, SRGAN has proven itself effective at solving problems related to image super resolution but there is still room left for improvement by adjusting hyperparameters or modifying architecture design based on findings from this paper.
