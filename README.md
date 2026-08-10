# Adversarial Attacks on Deep CNNs (ResNet-34)

This repository explores the vulnerability and robustness of Deep Convolutional Neural Networks (CNNs) against adversarial attacks. Using PyTorch and pre-trained vision models (ResNet-34), this project demonstrates how small, carefully designed perturbations can fool state-of-the-art image classifiers.

## 📌 Overview
Deep Neural Networks achieve high accuracy on standard classification benchmarks, yet they are vulnerable to small, imperceptible noise added to input images. This project implements adversarial generation strategies and evaluates model performance using Top-1 and Top-5 error metrics across benchmark datasets such as CIFAR-10 and TinyImageNet.

## 🔑 Key Features
- **Model Architecture:** PyTorch ResNet-34 evaluated under zero-shot and fine-tuned settings.
- **Evaluation Framework:** Measurement of loss, Top-1 accuracy, and Top-5 accuracy under clean and adversarial conditions.
- **Visualization:** Utility scripts for displaying original images, prediction probability distributions, and added adversarial noise.
- **Tooling:** Built using PyTorch, Torchvision, and PyTorch Lightning.

## 🛠️ Installation & Requirements
Ensure Python 3.8+ and GPU support are available, then install dependencies:

```bash
pip install torch torchvision pytorch-lightning matplotlib seaborn tqdm scikit-learn
