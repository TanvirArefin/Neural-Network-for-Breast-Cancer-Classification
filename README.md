# Breast Cancer Classification using Neural Networks (PyTorch)

## Overview
This project implements a deep neural network using PyTorch to classify breast cancer tumors as benign or malignant using the Breast Cancer Wisconsin (Diagnostic) dataset. The model is trained on a balanced subset of the dataset and achieves good performance in distinguishing between the two classes.

## Dataset
The dataset used is the [Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) dataset, which contains 569 samples with 30 features each. The target variable is the diagnosis (benign or malignant). The dataset was balanced by selecting 200 samples from each class, resulting in 400 total samples.

## Features
- Data preprocessing and standardization  
- Neural network architecture with one hidden layer  
- Training and evaluation pipeline  
- Loss visualization  
- Implements PyTorch for model building and training  

## Requirements
- Python 3.x  
- PyTorch 2.3.1  
- pandas 2.2.2  
- numpy 1.26.4  
- matplotlib 3.8.0  
- scikit-learn 1.5.0  
- ucimlrepo 0.0.7  

## Usage
Run the Jupyter notebook Neural Network for Breast Cancer Classification.ipynb to train and evaluate the model.

## The notebook includes:

-Data loading and preprocessing
-Model definition and training
-Performance evaluation
-Loss visualization
-Model Architecture

## The neural network consists of:
1.Input layer: 30 neurons (one for each feature)
2.Hidden layer: 64 neurons with ReLU activation
3.Output layer: 2 neurons (for binary classification)

## Results: The model shows decreasing training and test loss over epochs, indicating successful learning. The balanced dataset helps prevent bias toward either class.

## License: This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license, the same as the dataset.

## Acknowledgments
University of California, Irvine for hosting the dataset

PyTorch development team

scikit-learn and other open-source contributors 

## Installation

Clone this repository:
```bash
git clone https://github.com/TanvirArefin/Neural-Network-for-Breast-Cancer-Classification.git
cd breast-cancer-classification

