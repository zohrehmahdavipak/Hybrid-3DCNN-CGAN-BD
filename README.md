# Hybrid-3DCNN-CGAN-BD

Hybrid 3D-CNN and Conditional GAN Framework for Bipolar Disorder Classification Using Multimodal MRI

## Overview

This repository contains the custom MATLAB code associated with the manuscript:

**"A Hybrid 3D-CNN and CGAN Approach for Bipolar Disorder Diagnosis Using VBM and SBC Features from Multimodal MRI"**

The proposed framework combines:

* Structural MRI (sMRI) features derived from voxel-based morphometry (VBM)
* Resting-state fMRI features derived from seed-based connectivity (SBC)
* A dual-branch 3D convolutional neural network (3D-CNN) for multimodal feature learning
* A conditional generative adversarial network (CGAN) for feature-space augmentation

The framework was developed for bipolar disorder (BD) versus healthy control (HC) classification using the UCLA Consortium for Neuropsychiatric Phenomics (CNP) dataset.

---

## Repository Contents

```text
CGAN/
    Generator and discriminator implementation
    CGAN training scripts

3DCNN/
    Dual-branch multimodal 3D-CNN architecture
    Training and testing scripts

Evaluation/
    Performance evaluation
    Nested cross-validation
    Held-out test assessment

README.md
```

---

## Dataset

The study uses the publicly available UCLA Consortium for Neuropsychiatric Phenomics (CNP) dataset:

OpenNeuro:
https://openneuro.org/datasets/ds000030

Version used in the study:
https://openneuro.org/datasets/ds000030/versions/00016

The MRI preprocessing and feature extraction procedures are described in the manuscript.

---

## Software Requirements

* MATLAB R2023b or later
* Deep Learning Toolbox
* Statistics and Machine Learning Toolbox

Preprocessing and feature extraction were performed using:

* SPM12
* CAT12
* CONN Toolbox

---

## Reproducibility

This repository contains the custom code used for:

* CGAN-based feature augmentation
* Multimodal 3D-CNN training
* Model evaluation

The repository is intended to support transparency and reproducibility of the published results.

---

## Citation

If you use this code, please cite:

Mahdavipak Z, Khadem A.

*A Hybrid 3D-CNN and CGAN Approach for Bipolar Disorder Diagnosis Using VBM and SBC Features from Multimodal MRI.*

Scientific Reports, 2026.

---

## DOI

Archived Zenodo release:

https://doi.org/10.5281/zenodo.20706097
