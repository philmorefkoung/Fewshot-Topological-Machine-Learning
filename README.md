# Fewshot-Topological-Machine-Learning
 - Convolutional Neural Network Augmented with Topological Features to Boost Fewshot Accuracy and AUROC in Medical Image Classification
 - In this project, demonstrate that topological data analysis (TDA) combined with convolutional neural networks (CNN) can improve key metrics and model robustness in medical image classification
 - Accepted by IEEE-EMBS International Conference on Biomedical and Health Informatics (BHI) 2024 for Poster and Rapid Fire presentation

Data
---
We utilized a subset of the Blood, Breast, Pneumonia, and Derma MNIST datasets from the [MedMNIST](https://medmnist.com/) website

Results
---
Our methods show that topological data analysis complements well with deep learning by consistently improving accuracy and AUROC when combined together in limited data environments
# Table I
## AUC Performances for Our Models with Different Splits

| Split    | Blood (CNN) | Blood (TDA) | Blood (CNN+TDA) | Breast (CNN) | Breast (TDA) | Breast (CNN+TDA) |
|----------|-------------|-------------|-----------------|--------------|--------------|------------------|
| 80/20    | 50.68       | 76.52       | 77.04           | 56.25        | 87.75        | 78.25            |
| 200/50   | 80.41       | 83.63       | 87.12           | 58.36        | 75.56        | 81.34            |
| 400/100  | 65.09       | 87.24       | 86.56           | 70.72        | 71.76        | 72.01            |

| Split    | Pneumonia (CNN) | Pneumonia (TDA) | Pneumonia (CNN+TDA) | Derma (CNN) | Derma (TDA) | Derma (CNN+TDA) |
|----------|-----------------|-----------------|---------------------|-------------|-------------|-----------------|
| 80/20    | 52.75           | 72.00           | 65.25               | 50.65       | 59.73       | 63.79           |
| 200/50   | 81.08           | 65.24           | 88.99               | 62.21       | 58.84       | 63.11           |
| 400/100  | 86.84           | 70.89           | 88.56               | 66.29       | 57.62       | 68.70           |


