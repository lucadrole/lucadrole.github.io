---
title: "Deep Learning Approaches for Medical Image Segmentation: A Comparative Study"
collection: publications
category: manuscripts
permalink: /publication/2024-deep-learning-segmentation
excerpt: 'Comprehensive evaluation of state-of-the-art deep learning architectures for medical image segmentation tasks across multiple modalities.'
date: 2024-08-20
venue: 'Journal of Biomedical Engineering and Technology'
paperurl: ''
citation: 'Drole, L. (2024). "Deep Learning Approaches for Medical Image Segmentation: A Comparative Study." <i>Journal of Biomedical Engineering and Technology</i>. Under Review.'
---

This study provides a comprehensive comparison of modern deep learning architectures for medical image segmentation, evaluating their performance across different imaging modalities and clinical applications.

## Motivation
Medical image segmentation is a critical task in clinical diagnosis and treatment planning. With the rapid advancement of deep learning techniques, numerous architectures have been proposed, but systematic comparisons across modalities and applications remain limited.

## Methodology
We evaluated multiple state-of-the-art architectures including:
- U-Net and variants (U-Net++, Attention U-Net)
- DeepLab family (DeepLabV3+)
- Transformer-based approaches (Swin-UNet, TransUNet)
- Hybrid CNN-Transformer models

## Experimental Setup
* **Datasets**: Multi-modal medical imaging datasets (CT, MRI, X-ray)
* **Metrics**: Dice coefficient, IoU, Hausdorff distance, clinical relevance scores
* **Validation**: Cross-validation with clinical expert annotations
* **Implementation**: PyTorch framework with standardized training protocols

## Key Findings
The study reveals performance trade-offs between computational efficiency and segmentation accuracy, with transformer-based approaches showing superior performance on complex anatomical structures while traditional CNN approaches maintain advantages in computational efficiency.

## Impact
This research provides practical guidance for selecting appropriate deep learning architectures for specific medical imaging applications, contributing to more effective clinical AI implementation.

*Research conducted as part of master's thesis work at ETH Zurich*