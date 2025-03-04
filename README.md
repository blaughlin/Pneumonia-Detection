# Pneumonia Detection with Deep Learning!
Deep learning for pneumonia detection 

## Overview
This project applies deep learning to detect pneumonia from chest X-ray images using fine-tuned ResNet50, DenseNet121, and a custom CNN model trained from scratch. The goal was to compare transfer learning vs. training a CNN from scratch and identify the best model for clinical deployment.

Through extensive experiments, ResNet50 emerged as the best-performing model, achieving high precision and the lowest false alarm rate, making it ideal for real-world medical applications.

## Dataset
### Sources
- NIH Chest X-ray Dataset (National Institutes of Health, 2017)
- Stanford PNA (Pneumonia) Dataset (CheXpert from Stanford University, 2019)
### Training Size
- 38,029 normal images from NIH data set
- 6,750 pneumonia images from NIH and Stanford
### Classes
- Nomal (0)
-  PNA (1)
### Preprocessing
- Images resized to 224×224
- Pixel values scaled to [0,1]
- Data Augmentation: rotation, shift, zoom, horizontal flip




