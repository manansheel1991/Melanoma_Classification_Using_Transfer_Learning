# Melanoma Classification using Transfer Learning

Classification of Skin lesions into 3 classes of Skin Cancers, including Melanoma, using Transfer Learning on the popular VGG16 Architecture. This project was introduced to me in the Udacity Deep Learning Nanodegree.

## Skin Cancer Diagnosis Problem

Melanoma is the deadliest form of Skin Cancer. Melanoma is malignant, while Nevus and Seborrheic Keratosis are benign. Skin Cancer is diagnosed by a dermatologist, using visual inspection, that is looking at the skin lesion with naked eyes. This has been the traditional way to diagnose Skin Cancers upto now. But after the advancements in Deep Learning, research has shown that CNNs (Convolutional Neural Networks) can classify the same, with a performance that is better than the diagnosis made by the best of the dermatologists. This came as a surprise and a great promise in the field.

![](skin-disease-classes.png)

## In This Project

In this project, transfer learning is used on the VGG16 Architecture, by replacing the last layer of VGG16 with a linear fully connected layer that has 3 outputs corresponding to the 3 classes of Skin Cancer. Only the classifier layers are then trained (while freezing the parameters from the features layers). 

## Requirements

The requirements to run the project are included in 'requirements.txt'.
The dataset can be downloaded from [here](https://github.com/udacity/dermatologist-ai.git)

## Notebook

All the code for this project is present in 'Final_Tested_Melanoma_Classification_CNN.ipynb'. The code is explained with comments wherever necessary.

## Results

The model could achieve an accuracy of 68% on the test set.
