# Butterfly Species Classification (PyTorch)

## Overview
This project classifies butterfly species using an image dataset and a PyTorch deep learning pipeline. It includes custom dataset handling, image preprocessing, model training, and evaluation using a confusion matrix. Transfer learning with pretrained CNN architectures (e.g., ResNet) is used to improve accuracy and reduce training time.

---

## Objectives
- Build an end-to-end image classification workflow using PyTorch
- Apply image preprocessing (resize, normalization, augmentation)
- Train a CNN model (transfer learning using torchvision pretrained models)
- Evaluate performance with classification metrics and a confusion matrix

---

## Methods & Workflow
- Custom `Dataset` class for loading images and labels
- `DataLoader` pipelines for efficient batching
- `torchvision.transforms` for preprocessing
- Transfer learning using pretrained models (`torchvision.models`)
- Training loop with optimizer (Adam) and loss function (`nn`)
- Train/validation split using `train_test_split`
- Model evaluation using a confusion matrix

---

## Tools & Libraries Used
- Python
- PyTorch (`torch`, `Dataset`, `DataLoader`, `nn`, `optim`)
- Torchvision (`transforms`, pretrained `models` مثل ResNet)
- Pandas / NumPy
- Matplotlib
- PIL (Image)
- Scikit-learn (`train_test_split`, `confusion_matrix`)
- tqdm (training progress bar)

---

## Outputs
- Training/validation performance tracking
- Confusion matrix for class-level performance analysis
- Visualizations for sample images and model behavior

---

## Project Files
[Butterfly Dataset.pdf](https://github.com/user-attachments/files/24385847/Butterfly.Dataset.pdf)
