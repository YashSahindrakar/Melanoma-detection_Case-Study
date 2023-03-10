# Melanoma-detection Case-Study
In this assignment, we have build a multiclass classification model using a custom convolutional neural network in TensorFlow.

## Table of Contents
1. Problem statement
2. Acknowledgements
3. Technologies Used
4. Conclusions


## Problem statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Project Pipeline  
1) Data Reading/Data Understanding
2) Dataset Creation
3) Dataset visualisation
4) Model Building & training
5) Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
6) Model Building & training on the augmented data
7) Class distribution
8) Handling class imbalances
9) Model Building & training on the rectified class imbalance data


## Conclusions
- The issue of overfitting was tackled successfully by doing Data Augmentation, adding a drop out layer.

- The model performed well on both training and validation datasets.


## Acknowledgements 
This project was inspired by UpGrad.


## Technologies Used
Keras
TensorFlow
Python 3
Pandas, Numpy, Matplotlib,
Augmentor



## Contact
Created by [@YashSahindrakar] - feel free to contact me!
