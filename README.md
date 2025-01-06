# Automated Diabetic Retinopathy Detection

This project aims to automate the detection of Diabetic Retinopathy (DR) using deep learning techniques. The system is built using a Convolutional Neural Network (CNN) and trained on a dataset of retinal images.

## Table of Contents

- [Introduction]
- [Dataset]
- [Methodology]
- [Preprocessing]
- [Augmentation
- [Model Building]
- [Training]
- [Evaluation]
- [Results]
- [Conclusion]

## Introduction

Diabetic Retinopathy (DR) is a leading cause of vision loss among diabetic patients. Early detection and treatment are crucial to prevent blindness. This project utilizes deep learning to automate the DR detection process, making it more efficient and accessible.

## Dataset

The project utilizes the APTOS 2019 Blindness Detection dataset, which consists of thousands of retinal images labeled with different stages of DR severity.

## Methodology

The project follows these steps:

1. **Preprocessing:** Images are preprocessed to enhance features and improve model performance. This includes cropping, resizing, and contrast enhancement.
2. **Augmentation:** Data augmentation techniques are used to increase the dataset size and variability, improving model generalization.
3. **Model Building:** A CNN model, such as ResNet50, is employed for feature extraction and classification.
4. **Training:** The model is trained on the preprocessed and augmented dataset.
5. **Evaluation:** The trained model is evaluated on a separate test set to assess its performance.
6. **Results:** The results are analyzed to understand the model's accuracy and potential for real-world application.

## Preprocessing

- Images are cropped to remove dark parts around the edges.
- Images are resized to a standard size (e.g., 224x224).
- Contrast enhancement techniques are applied to improve image quality.

## Augmentation

- Random rotations, shifts, brightness changes, and flips are applied to generate new training samples.

## Model Building

- A pre-trained ResNet50 model is used as the
