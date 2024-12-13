# A Novel Graph-Based Framework for Understanding of Decision-Making Process in Deep Learning Models

This repository contains the code and resources for the paper titled **"A Novel Graph-Based Framework for Understanding of Decision-Making Process in Deep Learning Models"**. The paper has been accepted for **IEEE Symposium Series on Computational Intelligence (SSCI), Trondheim, Norway, 2025**.

## Paper Information

- **Title**: A Novel Graph-Based Framework for Understanding of Decision-Making Process in Deep Learning Models
- **Author**: Pubudu Sanjeewani Thihagoda Gamage
- **Accepted**: SSCI 2025

## Introduction

This project presents a novel framework for understanding decision-making processes in deep learning models. By using graph-based representations, the framework aims to provide insight into how deep learning models make predictions and how these decisions are influenced by the structure of data. The goal is to enhance model interpretability, which is crucial for fields like medical diagnostics, autonomous vehicles, and more.

## Code Overview

The code provided in this repository uses the **ResNet50V2** deep learning model to perform image classification. It applies advanced interpretability techniques such as **Grad-CAM**, **Grad-CAM++**, and **Integrated Gradients** to visualize the decision-making process of the model. Additionally, the code creates a graph-based representation of the model's predictions, and spectral clustering is applied to reveal clusters of decision-making patterns.

### Key Features:
- **Grad-CAM** and **Grad-CAM++** visualizations for explaining model decisions.
- **Integrated Gradients** for computing the importance of features in predictions.
- **Graph-based representation** of model predictions, using clustering techniques to identify patterns.

## Requirements

To run this project, the following Python libraries are required:

- `matplotlib` - For plotting and visualizing graphs.
- `networkx` - For graph creation and manipulation.
- `scikit-learn` - For clustering (spectral clustering).
- `tensorflow` - For deep learning models and image classification.
- `numpy` - For numerical operations.
- `scikit-image` - For image processing.

You can install these dependencies by running:

```bash
pip install matplotlib networkx scikit-learn tensorflow numpy scikit-image
```

## Note on Code Development

**Generative AI** (ChatGPT) was used in developing the code for this project in tasks such as code generation. However, the ideas, overall approach, and implementation are the result of the authors' contributions.

## Citations

If you use this code or framework in your work, please cite the following paper:

```bash
@inproceedings{azam2025graph,
  author = {Azam, Basim and Sanjeewani, Pubudu and Verma, Brijesh and Rahman, Ashfaqur and Wang, Lipo},
  title = {A Novel Graph-Based Framework for Understanding of Decision-Making Process in Deep Learning Models},
  booktitle = {IEEE Symposium Series on Computational Intelligence (SSCI)},
  year = {2025},
  address = {Trondheim, Norway}
```

## Contributions & Queries

We welcome any questions or contributions related to this work. Please feel free to reach out to us:

Pubudu Sanjeewani: p.thihagodagamage@griffith.edu.au / pubudusanjeewani91@gmail.com <br>
Basim Azam: b.verma@griffith.edu.au / basimazam0@gmail.com

We look forward to hearing from you!
