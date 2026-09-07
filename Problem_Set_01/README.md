# Chest X-Ray Pneumonia Classification Using Custom CNN

## Introduction

Pneumonia is a respiratory disease that can be identified from chest X-ray images. In this project, a Custom Convolutional Neural Network (CNN) is developed to classify chest X-ray images into two categories:

* NORMAL
* PNEUMONIA

The project demonstrates the use of deep learning for automated medical image classification.

## Problem Statement

The objective is to develop a CNN model that can classify a given chest X-ray image as either NORMAL or PNEUMONIA.

## Objectives

The main objectives of this project are:

* To preprocess chest X-ray images.
* To apply data augmentation.
* To develop a custom CNN using TensorFlow/Keras.
* To handle class imbalance using class weights.
* To train and validate the CNN model.
* To evaluate the model on unseen test images.

## Dataset Description

The dataset was provided by the instructor and contains two classes:

* NORMAL
* PNEUMONIA

The dataset is divided into:

* Training: 5,216 images
* Validation: 16 images
* Testing: 624 images

## Model and Results

The CNN uses convolutional layers, batch normalization, max pooling, global average pooling, dense layers, and dropout.

The model achieved:

* **Test Accuracy:** 88.14%
* **Test AUC:** 0.9394
* **Macro F1-Score:** 0.8714

The confusion matrix and classification report were also used to evaluate the model's performance.

