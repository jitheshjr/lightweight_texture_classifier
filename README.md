Lightweight Texture-Based Classification for Embedded Vision Systems

This repository contains the implementation of a lightweight machine learning pipeline inspired by the research paper “Enhanced Classification System for Real-Time Embedded Vision Applications”.

The project focuses on efficient crosswalk image classification using:

GLCM texture features (24 → 10 → 5)

Feature complexity analysis using Θ(n)

Correlation-Based Feature Selection (CFS)

Optimized SVM classifier

Comparison with a CNN benchmark model

The objective is to develop a compact, fast, and memory-efficient model suitable for embedded devices such as Raspberry Pi, microcontrollers, and low-power computer vision systems.

Dataset

This project uses the publicly available Crosswalk Dataset from Kaggle:
https://www.kaggle.com/datasets/davidsilvam/crosswalkdataset

Dataset details:

600 images

4 balanced classes (C1, C2, C3, C4)

Originally captured at 1280×720 resolution
