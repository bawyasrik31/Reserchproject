# 🩺 Analysis of Mamba, Transformer, and CNN Architectures on the NIH ChestX-ray14 Dataset

A comparative deep learning study evaluating the performance of **CNN**, **Transformer**, and **Mamba State Space Model (SSM)** architectures for **multi-label chest X-ray anomaly detection** using the **NIH ChestX-ray14** dataset.


## 📖 Project Overview

Chest X-ray interpretation is one of the most widely used diagnostic procedures for detecting thoracic diseases. This project investigates the effectiveness of three major deep learning architectures:

- Convolutional Neural Networks (CNNs)
- Vision Transformers (Transformers)
- Mamba State Space Models (SSMs)

The objective is to identify the most accurate and computationally efficient architecture for detecting multiple thoracic abnormalities from chest radiographs.

This work focuses on the challenges of:

- High-resolution chest X-ray images
- Weakly supervised image-level labels
- Grayscale intensity variations
- Overlapping anatomical structures
- Multi-label disease classification


# 🎯 Objectives

- Compare CNN, Transformer, and Mamba architectures on the NIH ChestX-ray14 dataset.
- Evaluate classification performance using standard medical imaging metrics.
- Analyze computational efficiency alongside prediction accuracy.
- Study how different architectures handle complex thoracic abnormalities.
- Identify the most suitable architecture for large-scale chest X-ray diagnosis. :contentReference[oaicite:1]{index=1}

# 🩻 Dataset

**Dataset:** NIH ChestX-ray14

The dataset contains thousands of chest radiographs with image-level annotations for multiple thoracic diseases.

### Challenges

- High-resolution images
- Weak supervision
- Overlapping anatomical structures
- Grayscale intensity variation
- Multi-label disease prediction :contentReference[oaicite:2]{index=2}


# 🏗️ Models Evaluated

## CNN Architectures

- DenseNet121
- ResNet34
- InceptionV3
- EfficientNet-B0

### Advantages

- Excellent local feature extraction
- Strong baseline performance
- Efficient feature reuse

## Transformer Architectures

- ConvFormer
- CaFormer
- Swin Transformer
- DeiT

### Advantages

- Captures long-range dependencies
- Learns global contextual relationships
- Strong performance on complex image features

:contentReference[oaicite:4]{index=4}


## Mamba Architectures

- VMamba
- MedMamba

### Advantages

- Computationally efficient
- Lower memory requirements
- Fast sequential processing


# 📊 Research Gap

Existing studies demonstrate that CNN and Transformer architectures achieve strong performance on ChestX-ray14, whereas Mamba-based models remain relatively underexplored and often underperform in detecting complex thoracic abnormalities.

This project aims to provide a comprehensive comparison of these architectures under identical experimental settings. :contentReference[oaicite:6]{index=6}


# 🚀 Project Workflow

NIH ChestX-ray14 Dataset
            │
            ▼
Data Preprocessing
            │
            ▼
 Image Augmentation
            │
            ▼
 Model Training
      │     │      │
      ▼     ▼      ▼
    CNN Transformer Mamba
      │     │      │
      └─────┼──────┘
            ▼
 Performance Evaluation
            │
            ▼
 Comparative Analysis

# 📈 Evaluation Metrics

The following metrics will be used for performance evaluation:

- Accuracy
- Precision
- Recall
- F1-Score
- AUROC
- Training Time
- Inference Time
- Computational Cost


# 💡 Novelty

- First comprehensive comparison of CNN, Transformer, and Mamba architectures for this task.
- Evaluation on weakly supervised chest X-ray images.
- Analysis of computational efficiency alongside diagnostic performance.
- Investigation of recent Mamba architectures (VMamba & MedMamba).
- Identification of the best model for scalable medical image analysis. :contentReference[oaicite:7]{index=7}


# 📌 Expected Outcome

This study aims to determine:

- Which architecture provides the highest diagnostic accuracy.
- Which model offers the best trade-off between accuracy and computational efficiency.
- Whether Mamba architectures can become a practical alternative to CNNs and Transformers for medical imaging applications.


# 📚 References

The project is based on recent research involving:

- CNN-based Chest X-ray classification
- Vision Transformers
- VMamba
- MedMamba
- ChestX-ray14 Benchmark
- Self-supervised Medical Image Learning
