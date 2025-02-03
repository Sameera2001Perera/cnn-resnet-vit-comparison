# CNN, ResNet, and Vision Transformer (ViT) - Image Classification

## 📌 Overview
This repository contains the implementation and comparison of **Convolutional Neural Networks (CNNs), Residual Networks (ResNet), and Vision Transformers (ViTs)** for image classification tasks using the **CIFAR-10 dataset**.

The project explores how different deep learning architectures perform on a small-scale dataset, evaluating their efficiency, accuracy, and computational cost.


## 📊 Models Implemented
1. **CNN (Convolutional Neural Networks)** - Traditional deep learning model for image classification.
2. **ResNet (Residual Networks)** - Introduces residual connections to address vanishing gradient problems.
3. **Vision Transformers (ViT)** - Utilizes self-attention mechanisms to process images as sequences of patches.

## 🗂 Dataset
- **Dataset Used:** [CIFAR-10](https://www.kaggle.com/c/cifar-10/)
- **Number of Classes:** 10 (Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck)
- **Image Size:** 32x32 pixels
- **Train/Test Split:** 50,000 training images, 10,000 test images

## 🏆 Model Performance
| Model         | Accuracy | Precision | Recall | F1 Score |
|--------------|---------|----------|--------|----------|
| **CNN**      | 80.66%  | 80.47%   | 80.66% | 80.50%   |
| **ResNet**   | 72.46%  | 73.25%   | 72.46% | 72.57%   |
| **ViT**      | 68.73%  | 68.87%   | 68.73% | 68.56%   |

## 🖥️ Usage
- Train the models from scratch using the Jupyter notebook.
- Modify and extend the implementation to experiment with different architectures.
