# Machine-Learning
This repository contains projects related to machine learning.

## Project 1

### Dataset: Air Quality Dataset
The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level,within an Italian city. Data were recorded from March 2004 to February 2005 (one year)representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer. Evidences of cross-sensitivities as well as both concept and sensor drifts are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors concentration estimation capabilities. Missing values are tagged with -200 value.
This dataset can be used exclusively for research purposes. Commercial purposes are fully excluded.

link to the dataset: https://archive.ics.uci.edu/ml/datasets/Air+Quality


Followings aspects have been considered in this project:
1. Ridge Regression
2. Preprocessing the data
3. Stochastic Gradient Descent
4. Random Forest
5. Pipelines

For the detailed information and code please check either the Jupyter Notebook or Python file.


## Project 2

### Dataset A: MedMNIST
MedMNIST v2, a large-scale MNIST-like collection of standardized biomedical images, including 12 datasets for 2D and 6 datasets for 3D. All images are pre-processed into 28x28 (2D) or 28x28x28 (3D) with the corresponding classification labels, so that no background knowledge is required for users. Covering primary data modalities in biomedical images, MedMNIST v2 is designed to perform classification on lightweight 2D and 3D images with various data scales (from 100 to 100,000) and diverse tasks (binary/multi-class, ordinal regression and multi-label). The resulting dataset, consisting of 708,069 2D images and 10,214 3D images in total, could support numerous research / educational purposes in biomedical image analysis, computer vision and machine learning. We benchmark several baseline methods on MedMNIST v2, including 2D / 3D neural networks and open-source / commercial AutoML tools.
**In this project BreastMNIST and OCTMNIST datasets were used** 

link to the dataset: https://github.com/MedMNIST/MedMNIST


### Dataset B: FashionMNIST
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

link to the dataset: https://github.com/zalandoresearch/fashion-mnist

Followings aspects have been considered in this project:
1. Logistic Regression
2. Convolutional Neural Networks
3. Principal component analysis
4. Spectral Clustering
5. Autoencoders

For the detailed information and code please check either the Jupyter Notebook or Python file.
