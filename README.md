# BeanSpeciesClassification--UAstat441

*This project is apart of the Statistic 441 class of W2024 @ the University of Alberta under Dr. Wenlu Tang*
**Github is inconsistent with showing all of the files at times. If needed, download the file and load it up locally**

## Overview
This project aims to classify different types of dry beans using machine learning techniques, specifically Support Vector Classifier (SVC) with Radial Basis Function (RBF) kernels. The goal is
to determine the species of bean based on the provided characteristics.

## Dataset
* Source: Dry Bean Dataset. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C50S4B.
* Description: The dataset comprises 13,611 samples (n) with 7 distinct classifications for the response variable
(‘Class’).).
* Features: Area, Perimeter, MajorAxisLength, MinorAxisLength,
AspectRatio, Eccentricity, ConvexArea, EquivalentDiameter, Extent, Solidity, Roundness, Compactness, ShapeFactor1, ShapeFactor2, ShapeFactor3, and ShapeFactor4
* Target Variable: Species

## Methodology
* Data Preprocessing / EDA
* Variable Transformation
* Visualization of heatmaps/correlation


## Model Training
* Algorithm: Support Vector Machine (SVM)
* Kernel: Radial Basis Function (RBF)

##Results
* ROC curve to assess the model's predictability of true pos which gave us a AUC of 95% for new testing data, and an accuracy of 91%.

##Future Improvements
* Check the accuracy with possible diferent shuffles using K-fold Cross Validation
* Test different parameters of SVM
* Test different SVM kernels such as lienar or polynomial

## Dependencies
* Direct to -- Code/1.0 CodeConcatenate.ipynb
