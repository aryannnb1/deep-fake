# DeepFake Detection on Celeb-DF V2 Dataset using Multiscale Vision Transformer

This repository contains the implementation of a deepfake detection model using Multiscale Vision Transformer (MViT) on the Celeb-DF V2 dataset. The goal of this project is to develop a robust and efficient approach to detect deepfakes, leveraging the power of transformer-based architectures.

## Overview

Deepfake videos have become increasingly prevalent, posing significant threats to security, privacy, and trust in digital media. This project uses the Celeb-DF V2 dataset, a large-scale and high-quality dataset for deepfake detection, to train a Multiscale Vision Transformer (MViT) for identifying fake videos with high accuracy.

## Dataset

The [Celeb-DF V2 dataset](https://github.com/yuezunli/celeb-deepfakeforensics) is a high-quality dataset for deepfake detection. It contains:

- Real videos from celebrities.
- Fake videos generated using deepfake algorithms.

The dataset is publicly available and provides a challenging benchmark for deepfake detection tasks.

## Model

The Multiscale Vision Transformer (MViT) is chosen for this project due to its ability to capture both local and global features effectively. Key features of the model include:

- **Multiscale Attention Mechanism**: Enables the model to process information at different scales.
- **Transformer-based Architecture**: Provides robustness and scalability.
- **Pretrained Weights**: The model uses pretrained weights on ImageNet for initialization.

## Results

The model achieves state-of-the-art performance on the Celeb-DF V2 dataset. Detailed results can be found in the `results/` directory.

| Metric    | Train  | Validation | Test   |
| --------- | ------ | ---------- | ------ |
| Accuracy  | 91.05% | 86.37%     | 79.72% |
| Precision | 90.71% | 89.77%     | 82.92% |
| Recall    | 90.62% | 90.67%     | 89.00% |
| F1-Score  | 90.67% | 90.22%     | 85.85% |
| AUC       | 93.69% | 89.72%     | 82.96% |
| EER       | 8.64%  | 14.29%     | 23.13% |
