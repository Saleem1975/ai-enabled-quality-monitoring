# Methodology

## Objective

The objective is to classify Phase I control chart patterns using a multimodal deep learning model.

## Input data

The proposed model uses three input types:

1. Phase I control chart image
2. Histogram image
3. Numerical features:
   - Mean
   - Standard deviation
   - Skewness

## Model architecture

The model contains two primary paths:

### Visual path

A 2D-CNN extracts features from:

- Control chart images
- Histogram images

### Numerical path

A dense neural network processes statistical features.

### Fusion and classification

The extracted visual and numerical features are concatenated into a unified representation. A fully connected classifier with Softmax activation classifies the pattern into one of nine classes.

## Data simulation

Monte Carlo simulation is used to generate synthetic control chart patterns. Each sample has 64 data points. The paper uses 4,000 samples per pattern and repeats the experiments 30 times.

## Evaluation

Model performance is evaluated using classification accuracy, standard deviation, confusion matrix, ROC curve, training accuracy, validation accuracy, and validation loss.
