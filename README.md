# diabetic-retinopathy
This repository contains the code and resources for a project aimed at classifying diabetic retinopathy using deep learning techniques on retinal fundus images.

## Project Overview
Diabetic retinopathy is a leading cause of blindness worldwide. Early detection is crucial for effective treatment and prevention of vision loss. This project leverages deep learning to classify diabetic retinopathy from retinal fundus images, demonstrating the potential of AI in medical diagnostics.

## Dataset
The dataset used in this project consists of retinal fundus images sourced from Kaggle. The images are labeled by medical experts for accurate classification.

## Data Preprocessing
* Data Augmentation: Strategies like zca_whitening, rotation, pixel filling were employed to increase the variability of the dataset, enhancing the model's robustness.

## Model Development
* Transfer Learning Models: Pre-trained networks such a ResNet50,EfficientNetB3,DenseNet121, and InceptionV3 were utilized.
* Fine-Tuning: These models were fine-tuned to adapt to the specific characteristics of the retinal fundus images, optimizing them for high accuracy in classifying diabetic retinopathy.

## Results
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The results demonstrated high classification performance, showcasing the efficacy of deep learning in medical image analysis.
