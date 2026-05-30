# Steel Surface Defect Classification using CNN

## Overview

This project uses a Convolutional Neural Network (CNN) to automatically classify steel surface defects from images.

The model was trained using the NEU-DET dataset and can classify six different defect categories.

## Defect Classes

- Crazing
- Inclusion
- Patches
- Pitted Surface
- Rolled-in Scale
- Scratches

## Dataset

NEU-DET Steel Surface Defect Dataset

Total Images: 1440

## Methodology

1. Image Loading
2. Image Preprocessing
   - Resize to 128×128
   - Normalize pixel values
3. Train-Test Split
4. Label Encoding
5. CNN Model Development
6. Model Training
7. Performance Evaluation
8. Confusion Matrix Analysis

## CNN Architecture

- Conv2D (32 filters, 3×3)
- MaxPooling2D
- Flatten
- Dense (128 neurons)
- Dense (6 neurons, Softmax)

## Results

- Test Accuracy: ~81%
- Six-class defect classification
- Successful prediction on unseen test images

## Tools Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Future Improvements

- Data Augmentation
- Deeper CNN Architecture
- Transfer Learning
- Real-time Industrial Deployment

## Author

Gokul
M.Tech Production Engineering
IIT Delhi
