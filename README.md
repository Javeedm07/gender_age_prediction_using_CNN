# Gender and Age Prediction using CNN

This project utilizes Convolutional Neural Networks (CNNs) to accurately predict the gender and age of individuals from facial images. Trained on the comprehensive UTKFace dataset, the model is adept at recognizing gender and estimating age ranges.

## Table of Contents
1. Overview  
2. Dataset  
3. Technologies Used  
4. Model Architecture  
5. Usage  
6. Results  
7. Acknowledgements  

## Overview
Facial recognition and prediction systems are integral to various fields, including security, healthcare, and entertainment. This project builds a deep learning solution that:  
- Predicts Gender: Classifies individuals as Male or Female  
- Estimates Age: Provides an age prediction using facial features  

By leveraging the capabilities of CNNs, this model efficiently identifies patterns in images to deliver precise predictions.

## Dataset
This project uses the widely recognized UTKFace dataset, which contains over 20000 facial images with labels for age, gender, and ethnicity.  

Dataset Details:  
- Download: UTKFace Dataset from https://www.kaggle.com/datasets/jangedoo/utkface-new?resource=download or from the repo.
- Ensure the dataset is downloaded and extracted to the appropriate directory before running the scripts  

## Technologies Used
The following tools and libraries are used in this project:  
- Python (Version 3.x)  
- TensorFlow (Version 2.x)  
- Keras  
- OpenCV  
- NumPy  
- Matplotlib  

## Model Architecture
The CNN model is structured with the following layers:  
1. Convolutional Layers: Extract spatial features from input images  
2. Pooling Layers: Downsample features and reduce overfitting  
3. Fully Connected Layers: Generate final classifications and predictions  
4. Activation Functions: Use ReLU and Softmax for non-linear transformations  

Outputs:  
- Gender: Binary classification (Male or Female)  
- Age: Estimated either as a continuous value or as a category  

## Usage
### Prerequisites
Ensure all required libraries are installed. Install dependencies using:  
pip install -r requirements.txt  
