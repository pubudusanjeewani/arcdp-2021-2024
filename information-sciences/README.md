# Unified Graph-Based Framework for Visual Explainability in Convolutional Neural Networks
## Overview

This repository contains the code for the paper titled **"Unified Graph-Based Framework for Visual Explainability in Convolutional Neural Networks"** by Basim Azam, Pubudu Sanjeewani, Brijesh Verma, Ashfaqur Rahman, and Lipo Wang. The proposed method identifies critical input regions, enhancing understanding of model behavior through intuitive visual heatmaps and graph-based representations. 


### Authors:
- **Basim Azam** (Griffith University, Australia)
- **Pubudu Sanjeewani** (Griffith University, Australia)
- **Brijesh Verma** (Griffith University, Australia)
- **Ashfaqur Rahman** (CSIRO, Australia)
- **Lipo Wang** (Nanyang Technological University, Singapore)

### Corresponding Author:
- **Basim Azam** (b.azam@griffith.edu.au)

---

## Abstract

In deep learning, understanding the decision-making processes of complex models is essential for advancing interpretability and trust in artificial intelligence systems. We introduce Causal Relational Attribution Graph (C-RAG), designed to deliver comprehensive, multi-perspective explanations of convolutional neural networks (CNNs) via a graph representation. C-RAG integrates gradient-based local attribution with global feature importance by constructing a graph-based representation that captures hierarchical feature inter-dependencies. In this framework, feature clusters are represented as graph nodes, and their interactions are quantified through combined localized and global attribution metrics, ensuring interpretable insights into model behavior. We evaluate C-RAG across diverse benchmark datasets (ImageNet, CIFAR-10, MNIST) and CNN architectures (ResNet18, VGG19, DenseNet201, LeNet), demonstrating significant advancements over state-of-the-art explainability methods in faithfulness, robustness, and computational efficiency. The proposed approach facilitates accurate spatial feature localization, robust dependency mapping, and efficient explanation generation, making it a valuable tool for critical applications such as medical imaging and autonomous systems. We provide a novel graph-based explainability framework, which bridges the gap between local and global interpretability, C-RAG addresses key limitations in existing methods, establishing a robust foundation for explainable AI in computer vision.

---

## Highlights

- Graph view unifies local and global attributions.
- C-RAG models feature dependencies with weighted edges.
- Higher faithfulness and robustness across CNN backbones.
- Tighter localization with lower explanation complexity.
- Scales to real-time with efficient computation.

---

## Installation

---

## Citations

If you use this code or framework in your work, please cite the following paper:

```bash
@inproceedings{azam2025crag,
  author = {Azam, Basim and and Sanjeewani, Pubudu and Verma, Brijesh and Rahman, Ashfaqur and Wang, Lipo},
  title = {Unified Graph-Based Framework for Visual Explainability in Convolutional Neural Networks},
  booktitle = {Information Sceinces},
  volume = {},
  number = {},
  year = {2025},
  doi = {https://www.sciencedirect.com/science/article/pii/S0020025525007819?via%3Dihub}
```

## Contributions & Queries

We welcome any questions or contributions related to this work. Please feel free to reach out to us:

Basim Azam: b.azam@griffith.edu.au / basimazam0@gmail.com<br>
Pubudu Sanjeewani: p.thihagodagamage@griffith.edu.au / pubudusanjeewani91@gmail.com<br>

We look forward to hearing from you!


