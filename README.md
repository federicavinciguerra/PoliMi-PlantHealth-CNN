# PoliMi-PlantHealth-CNN

## Project Overview

**PoliMi-PlantHealth-CNN** is a machine learning project for classifying plant health status using Convolutional Neural Networks (CNNs). Developed for the Artificial Neural Networks and Deep Learning course at Politecnico di Milano (A.Y. 2023/2024), this project aims to create a binary classifier for detecting healthy and unhealthy plant conditions. Key techniques employed include CNN architectures, transfer learning, fine tuning, data preprocessing, and hyperparameter optimization.

## Dataset

The dataset contains a total of 5,200 plant images, with a final cleaned set of 5,003 after filtering. Images are labeled into two classes:

- **Healthy**: 3,100 images
- **Unhealthy**: 1,903 images

### Data Details
- **Image Size**: 96x96 pixels
- **Color Space**: RGB
- **Format**: `.npz`
- **Classes**: `{0: "healthy", 1: "unhealthy"}`

## Model Architecture and Techniques

The project utilizes a series of CNN architectures, applying transfer learning with models such as ResNet-152 and ConvNext to improve classification accuracy. The final model integrates these techniques:

1. **Baseline CNN**: Initial model with basic convolutional and pooling layers.
2. **Transfer Learning**: Using pre-trained models on ImageNet like ResNet50.
3. **Fine tuning**: Fine-tuning pre-trained models like ResNet and EfficientNet.
5. **Data Augmentation**: Enhancing model generalization through transformations.

The model training includes tuning hyperparameters, experimenting with various data augmentation strategies, and optimizing metrics.

