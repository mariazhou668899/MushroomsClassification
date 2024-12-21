# Species Classification Using CNN: A Case Study on Mushrooms

## Problem Statement
Accurately classifying diverse species is crucial for applications such as biodiversity studies, ecological monitoring, and resource management. Mushroom classification, for example, is essential for identifying edible and poisonous varieties, ensuring food safety, and supporting culinary practices. However, the inherent complexity of species characteristics—such as variations in shape, texture, and color—combined with the scarcity of large-scale annotated datasets presents significant challenges. These limitations underscore the need for innovative solutions to address species classification in resource-constrained scenarios.
## Introduction
This project explores the application of Convolutional Neural Networks (CNNs) for species classification using a very small image dataset, with a focus on mushroom classification as a case study. Leveraging the MobileNetV2 model, it classifies 215 mushroom types through data preprocessing techniques like resizing and augmentation to unify and expand the dataset. The study compares three CNN architectures—MobileNetV2, VGG16, and EfficientNetB0—and identifies the best-performing model. Optimizations such as unfreezing the last 50 layers, L2 regularization, learning rate adjustments, early stopping, a learning rate scheduler, and increased training epochs improved validation accuracy from 26% to 67%. Machine learning interpretation methods, including accuracy/loss metrics, Top N Correct and Misclassified Classes analyses, Accuracy/Loss plots, and Grad-CAM heatmaps, provide insights into model performance and outputs. By introducing an external mushroom dataset for validation, this work presents a novel framework for testing model generalizability. While focused on mushroom classification, the study addresses broader challenges of large-species classification with small datasets and demonstrates how lightweight CNNs can be adapted to resource-constrained environments, offering practical solutions for biodiversity studies, ecological monitoring, and other domains requiring efficient classification of diverse species.

## Goals and Objectives
- Primary Goals:
  - Develop an effective CNN model for classifying 215 mushroom species using a small dataset.
  - Achieve a significant improvement in validation accuracy through model optimization techniques.
  - Explore effective methods for interpreting image classification outputs.
  - Bridge the gap between machine learning model research and real-world applications.
- Secondary Goals:
  - Compare the performance of MobileNetV2, VGG16, and EfficientNetB0 models.
  - Provide interpretable insights into classification outcomes using advanced visualization techniques.
  - Validate model performance with external mushroom datasets to assess generalizability.

## Data Resource
This project is based on the Kaggle mushroom identification data set:
https://www.kaggle.com/datasets/daniilonishchenko/mushrooms-images-classification-215/data
- The Kaggle Mushrooms Images Classification 215 dataset, comprising 3,122 images (512x512 resolution) across 215 mushroom species, with at least 4 images per class, and a file mushrooms.txt containing names of all the mushrooms for the dataset.
-	External mushroom images are used to evaluate the well-trained model's generalizability.

## Implementation Architecture
![](https://raw.githubusercontent.com/mariazhou668899/MushroomsClassification/main/data_flow.png)


## Copyright © Maria Zhou 2024. All rights reserved.

