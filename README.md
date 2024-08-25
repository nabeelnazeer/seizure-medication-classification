# Seizure Medication Classification Task

This project involves the classification of EEG data from patients, with a dataset comprising around 2.5 million samples. The task is to classify EEG signals into different categories based on the medication the patients are taking.

## Overview

- **Models Used**: 
  - ResNet
  - Siamese Network

- **Custom Loss Functions**: 
  - Developed custom loss functions for the Siamese network.

- **Performance**:
  - Achieved an overall accuracy of 78% using a simple triplet loss function.
  - Currently experimenting with hard and semi-hard triplet loss functions to improve performance.

## Getting Started

To get started with this project, clone the repository and ensure you have the required dependencies installed.

```bash
git clone https://github.com/username/seizure-medication-classification.git
cd seizure-medication-classification
