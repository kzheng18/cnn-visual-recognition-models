## Overview

**CNN Visual Recognition Models** is a deep learning computer vision project focused on building, evaluating, and extending convolutional neural networks (CNNs) for real-world visual recognition tasks.

The project emphasizes **practical model development**, **transfer learning**, and **model limitations**, following a workflow closer to applied research and ML engineering than coursework.

---

## What This Project Does

- Trains CNNs for image classification on standard vision datasets
- Applies **transfer learning** using pretrained backbones
- Extends classifiers toward **weak object localization**
- Analyzes performance through metrics, learning curves, and failure cases

---

## Project Scope

### Image Classification
- Baseline and improved CNN architectures
- Data augmentation, normalization, and regularization
- Quantitative evaluation and error analysis

### Transfer Learning
- Feature extraction vs. fine-tuning
- Generalization and overfitting analysis
- Efficient training with pretrained models

### Localization
- Sliding-window inference for object localization
- Analysis of CNN limitations without detection heads
- Motivation for modern detection architectures

---

## Tech Stack

- **Python**
- **PyTorch / Torchvision**
- **NumPy**
- **Matplotlib**
- **scikit-learn**
- **Jupyter Notebooks**

GPU acceleration supported (CUDA optional).

---

## Why It Matters

This project demonstrates:
- End-to-end CNN model development
- Thoughtful experimentation and analysis
- Practical understanding of modern computer vision pipelines

It serves as a foundation for scaling toward **object detection**, **model interpretability**, and **production-ready vision systems**.

---

## Future Directions

- Replace sliding-window localization with YOLO / Faster R-CNN
- Add Grad-CAM and attention-based interpretability
- Explore Vision Transformers (ViTs)
- Package training and evaluation as reusable modules
