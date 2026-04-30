# MNIST Digit Classification using CNN

A deep learning project that classifies handwritten digits (0–9) from the 
MNIST dataset using a Convolutional Neural Network built with TensorFlow/Keras.

## Overview
- **Dataset:** MNIST (60,000 training / 10,000 test images, 28×28 grayscale)
- **Model:** CNN with 2 Conv blocks, BatchNorm, Dropout, Dense layers
- **Accuracy:** ~99%+ on test set
- **Framework:** TensorFlow / Keras
- **Environment:** Google Colab

## Model Architecture
- Conv2D (32 filters) → BatchNorm → MaxPooling → Dropout(0.25)
- Conv2D (64 filters) → BatchNorm → MaxPooling → Dropout(0.25)
- Flatten → Dense(128) → Dropout → Dense(10, softmax)

## How to Run

### Option 1: Google Colab (recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

### Option 2: Local Setup
```bash
git clone https://github.com/YOUR_USERNAME/mnist-digit-classification.git
cd mnist-digit-classification
pip install -r requirements.txt
jupyter notebook MNIST_Digit_classification_Model.ipynb
```

## Results
- Test Accuracy: 99.52%
- Includes: confusion matrix, classification report, prediction on custom images

## Project Structure
```
├── MNIST_Digit_classification_Model.ipynb  # Main notebook
├── MNIST_Digit_Classification_Report.docx  # Detailed project report
├── requirements.txt                        # Python dependencies
└── assets/                                 # Result visualizations
```
