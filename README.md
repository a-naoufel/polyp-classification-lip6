# Polyp Classification — LIP6 Internship

Machine learning and deep learning for the classification of colorectal polyps from colonoscopy images, in the context of colorectal cancer diagnosis.

> **Internship — Master 1** · LIP6, Sorbonne Université  
> **Supervisor:** [name] · **Period:** June–August 2026

---

## 📋 Table of Contents

- [Overview](#overview)
- [Objective](#objective)
- [Project Structure](#project-structure)
- [Sample Images](#sample-images)
- [Setup](#setup)
- [Usage](#usage)
- [Data](#data)
- [Experiment Tracking](#experiment-tracking)
- [Roadmap](#roadmap)
- [Author](#author)

---

## Overview

This project investigates and compares modern deep learning architectures
for the automated characterization and classification of colorectal polyps
from endoscopic (colonoscopy) images. Accurate polyp classification is a key
step in early colorectal cancer screening and diagnosis.

## Objective

Study and develop approaches to improve the characterization and
classification of colorectal polyps from endoscopic images, focusing on:

- **Convolutional Neural Networks (CNNs)** — e.g., ResNet, EfficientNet
- **Transformer-based architectures** — e.g., ViT, Swin Transformer
- **Comparative evaluation** of performance, interpretability, and robustness

## Project Structure

```text
polyp-classification-lip6/
├── src/         # Reusable source code (data, models, training, utils)
├── notebooks/   # Exploratory analysis
├── configs/     # Experiment configuration files
├── scripts/     # CLI entry points
├── results/     # Final figures and tables
├── docs/        # Notes and report drafts
└── data/        # Dataset location (not tracked — see data/README.md)
```
## Sample Images

To train robust classification models, our dataset includes multiple morphological classes of colorectal tissue. Below are representative examples of the primary categories targeted by our deep learning pipeline:

<img width="3053" height="872" alt="WJG-26-2276-g001-2158250079" src="https://github.com/user-attachments/assets/2bd38d22-3eda-400a-9425-6b0195f4cd7b" />

<p align="center"><em>Morphological variations under endoscopy. Left to Right: <strong>Adenomatous Polyp</strong> (neoplastic, tube-like vascular network), <strong>Hyperplastic Polyp</strong> (benign, smooth and pale surface), and <strong>Sessile Serrated Adenoma</strong> (pre-cancerous, flat structure often covered with mucus). (Source: Wikimedia Commons)</em></p>
