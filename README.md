
# PS-49: Hand Gesture Recognition for Touchless Control

## Project Overview
A deep learning-based image classification system designed to recognise ten hand gestures using near-infrared images from the LeapGestRecog dataset.

## Problem Statement
PS-49 – Hand Gesture Recognition for Touchless Control

The primary objective is to develop a CNN-based classifier that can recognise gestures performed by previously unseen individuals.

## Dataset
LeapGestRecog – Hand Gesture Recognition Database

- 20,000 images
- 10 subjects
- 10 gesture classes

Dataset: https://www.kaggle.com/datasets/gti-upm/leapgestrecog

## Gesture Classes
1. Palm
2. L
3. Fist
4. Fist moved
5. Thumb
6. Index
7. OK
8. Palm moved
9. C
10. Down

## Models
- Custom Convolutional Neural Network (CNN)
- MobileNetV2 Transfer Learning

## Methodology
- Dataset exploration and preprocessing
- Subject-independent train-validation-test split
- Image augmentation
- CNN model training
- Validation-based model selection
- Evaluation on unseen subjects
- Confusion matrix and error analysis

## Technologies
Python, TensorFlow, Keras, NumPy, Pandas, Scikit-learn, Matplotlib and Seaborn.

## Notebook
RA2311026050180_PS49.ipynb

## Author
R.V. Darsan
