# IMAGE-CLASSIFICATION-MODEL

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: VANSHIKA TIWARI

**INTERN ID**: CTIS7866

**DOMAIN**: MACHINE LEARNING

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTOSH
---

## Overview
This repository contains the implementation of a Convolutional Neural Network (CNN) for image classification. This project was developed as Task 3 during my Machine Learning Internship at CODTECH IT Solutions.

## Objective
To architect, train, and evaluate a deep learning model capable of extracting visual features from images and classifying them into distinct categories, while explicitly utilizing techniques to prevent model overfitting.

## Dataset
The model is trained on the **Fashion MNIST** dataset, which consists of 70,000 grayscale images representing 10 different categories of clothing and accessories.

## Tech Stack
* **Language:** Python
* **Framework:** TensorFlow & Keras
* **Libraries:** NumPy, Matplotlib, Seaborn, scikit-learn
* **Environment:** VS Code (Jupyter Notebook)

## Architecture & Strategy
* **Feature Extraction:** Utilized multiple `Conv2D` and `MaxPooling2D` layers to identify edges, shapes, and textures.
* **Overfitting Prevention:** Intentionally integrated a `Dropout(0.5)` layer before the final dense layers to force the network to generalize, ensuring a highly robust, realistic performance rather than an overfitted 100% accuracy.
* **Evaluation:** Plotted training vs. validation accuracy/loss curves to visually validate the model's generalization capabilities.

## Output
<img width="1189" height="490" alt="Image" src="https://github.com/user-attachments/assets/bccfcdfe-4613-403c-b311-42b1e2166dea" />
