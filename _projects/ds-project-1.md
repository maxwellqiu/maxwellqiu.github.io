---
title: "SE-Lightweight U-Net for Breast Cancer Segmentation"
category: "Data Science"
description: "Published research: a lightweight U-Net with Squeeze-and-Excitation attention blocks for breast ultrasound image segmentation. Achieves 88.88% Dice and 81.26% mIoU with only 3.10M parameters and 0.72 GFLOPs."
stack:
  - Python
  - PyTorch
  - Albumentations
  - Docker
  - Kubernetes
  - OpenCV
order: 1
github: "https://github.com/maxwellqiu"
---

## Overview

Published research conducted at the **Salehanil Lab, Concordia University**. The goal was to build a medical image segmentation model capable of near real-time breast cancer detection from ultrasound images, small enough for clinical deployment.

## The Problem

Existing segmentation models like Attention U-Net are accurate but computationally heavy. Clinical deployment requires models that run quickly on standard hardware without sacrificing diagnostic reliability.

## Approach

- Integrated **Squeeze-and-Excitation (SE) attention blocks** into a lightweight U-Net backbone to improve channel-wise feature recalibration
- Preprocessed the **BUS-BRA dataset** (2,000 files) with Python and Albumentations for augmentation diversity
- Containerized the entire ETL pipeline in **Docker** for reproducibility
- Executed training as **Kubernetes Jobs** with resource requests/limits for parallel, reproducible runs
- Implemented a **hybrid loss function (BCE + Dice)** to improve optimization stability

## Results

| Metric | Score |
|--------|-------|
| Dice coefficient | **88.88%** |
| mIoU | **81.26%** |
| Parameters | 3.10M |
| GFLOPs | 0.72 |

Outperformed U-Net, Attention U-Net, and SSL baselines. False positives reduced by 2% over baseline.

## Publication

Wenyang Qiu, Ethan Hamburg, Yinkun Zhou, Yaser Esmaeili Salehani — *Concordia University, Department of Computer Science and Software Engineering*, August 2025.
