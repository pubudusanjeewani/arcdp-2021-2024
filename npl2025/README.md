# A Novel Non-Iterative Training Method for CNN Classifiers Using Gram-Schmidt Process

## Overview

This repository contains the code for the paper titled **"A Novel Non-Iterative Training Method for CNN Classifiers Using Gram-Schmidt Process"** by Basim Azam, Deepthi Kuttichira, Pubudu Sanjeewani, Brijesh Verma, Ashfaqur Rahman, and Lipo Wang. In this work, we propose a **non-iterative training method** for Convolutional Neural Networks (CNNs) using the **Gram-Schmidt process** to address challenges such as slow convergence, susceptibility to local minima, and hypersensitivity to learning rates.

### Authors:
- **Basim Azam** (Griffith University, Australia)
- **Deepthi Kuttichira** (Griffith University, Australia)
- **Pubudu Sanjeewani** (Griffith University, Australia)
- **Brijesh Verma** (Griffith University, Australia)
- **Ashfaqur Rahman** (CSIRO, Australia)
- **Lipo Wang** (Nanyang Technological University, Singapore)

### Corresponding Author:
- **Basim Azam** (b.azam@griffith.edu.au)

---

## Abstract

Convolutional neural networks have become prominent machine learning models, particularly in the realm of computer vision, due to their ability to predict and extract robust features from raw image data. CNNs, similar to other neural network models, undergo training via backpropagation, an iterative technique. However, the backpropagation algorithm has notable challenges, including slow convergence, susceptibility to local minima, and hypersensitivity to learning rates. These challenges not only impact the model’s accuracy but also make the training process computationally intensive. To address these limitations, We introduce a novel approach that trains the CNN classifier using a **non-iterative** learning method. The proposed approach involves automatic extraction of pertinent features from the raw-data, followed by the application of **Gram-Schmidt** process to decompose the feature matrix and determine classifier’s weights. The proposed method has shown enhanced predictive accuracy over state-of-the-art models when evaluated on two benchmark datasets, MNIST and CIFAR-10. The
extensive experimentation using most cited pre-trained experiments validate the effectiveness of our proposed method.

---

## Features

- Non-iterative training method for CNNs.
- Uses Gram-Schmidt process for weight computation.
- Benchmarked on **MNIST** and **CIFAR-10** datasets.
- Improved predictive accuracy over traditional CNN models.

---

## Installation

---

## Citations

If you use this code or framework in your work, please cite the following paper:
@inproceedings{azam2025gramschmidt,
  author = {Azam, Basim and Kuttichira, Deepthi and Sanjeewani, Pubudu and Verma, Brijesh and Rahman, Ashfaqur and Wang, Lipo},
  title = {A Novel Non-Iterative Training Method for CNN Classifiers Using Gram-Schmidt Process},
  booktitle = {Neural Processing Letters},
  year = {2025},
  address = {}

## Contributions & Queries

We welcome any questions or contributions related to this work. Please feel free to reach out to us:

Pubudu Sanjeewani: p.thihagodagamage@griffith.edu.au / pubudusanjeewani91@gmail.com
Basim Azam: b.azam@griffith.edu.au / basimazam0@gmail.com

We look forward to hearing from you!
