 BY IBRAHIM ALHAMMADI(202170162)
    Emad Alqadasi(202170195)
    Souhil nabil(202170286)
ENG.YOUSEF Alqaiz

Brain Tumor Detection Project

Project Overview

This project aims to detect brain tumors using various machine learning techniques. The workflow includes image processing, embedding extraction, classification, and evaluation. It provides an automated way to identify tumors in brain images, potentially aiding in medical diagnosis.

Workflow Components

1. Import Images
The first step involves importing brain MRI images into the system. This step provides the raw data needed for further processing.

2. Image Embedding

The imported images are processed to extract image embeddings. These embeddings represent the essential features of the images, enabling effective analysis.

3. Machine Learning Models

The project employs multiple machine learning models for classification:

Logistic Regression: A basic classifier used to distinguish between tumor and non-tumor images.
k-Nearest Neighbors (kNN): A non-parametric algorithm used for tumor detection based on similarity between images.
Neural Network: A deeper model used for accurate classification of the brain tumor images.

4. Testing and Evaluation

Test and Score: This step involves testing the models against a portion of the dataset to measure their accuracy. The performance of each model is evaluated to determine which performs best.
Confusion Matrix: The confusion matrix is used to visualize the performance of the classification models by showing true positives, false positives, true negatives, and false negatives.

5. Save Model and Predictions

The best-performing model can be saved for future use, and predictions are generated for new images.
