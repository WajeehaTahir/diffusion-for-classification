# Diffusion for Classification

This project explores how diffusion-generated synthetic images can help with image classification under class imbalance.

## Overview

The main workflow is implemented in `/home/runner/work/diffusion-for-classification/diffusion-for-classification/2-1-3.ipynb` and includes:
- Loading CIFAR-10 data
- Creating an imbalanced subset for selected classes
- Generating synthetic images with Stable Diffusion
- Combining real and synthetic data
- Training and evaluating a ResNet-18 classifier

## Tech Stack

- Python 3
- PyTorch
- Torchvision
- Hugging Face Diffusers

## Repository Contents

- `/home/runner/work/diffusion-for-classification/diffusion-for-classification/2-1-3.ipynb` — end-to-end notebook for data prep, synthetic generation, and classification
- `/home/runner/work/diffusion-for-classification/diffusion-for-classification/Tahir_Wajeeha_ Al-Shameri_Shaima_PRC2.pdf` — supporting report/document

## How to Use

1. Install the required Python packages (PyTorch, Torchvision, Diffusers, and notebook dependencies).
2. Open and run `/home/runner/work/diffusion-for-classification/diffusion-for-classification/2-1-3.ipynb` in Jupyter.
3. Follow notebook sections in order to reproduce results.

Documented by Copilot.
