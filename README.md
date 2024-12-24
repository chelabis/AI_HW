# AI homeworks
## This repo includes my AI course internship homeworks


## 1- HW1- Student Performance Prediction
### Supervised Regression problem, dataset: Student_Performance.csv


## 2- HW2- Adult Income Classification
### Supervised Classification problem, dataset: adult_income.csv

#### Detail: An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, etc. In this dataset, you can find some individuals classified incomes(income <= 50K or income > 50K) alongside their respective influential features.
#### Task 1: Clean the data, use any statistical, visualization and preprocessing techniques.
#### Task 2: Find the best classification model for this data and report its performance measures on the validation set.


## 3- HW3- Customer Segmentation
### Unsupervised clustering problem, dataset: Wholesale customers data.csv

#### Dataset description:
This dataset contains information about customers' annual spending on various product categories.
#### Dataset Features:
 * Channel: The distribution channel (Retail or Horeca)
 * Region: The region of the customer
 * Fresh: Annual spending on fresh products
 * Milk: Annual spending on milk products
 * Grocery: Annual spending on grocery products
 * Frozen: Annual spending on frozen products
 * Detergents_Paper: Annual spending on detergents and paper products
 * Delicatessen: Annual spending on delicatessen products

#### Task 1: Preprocess and clean the data
#### Task 2: Use anomaly detection techniques to find the abnormal instances
#### Task 3: Use sufficient clustering models for customer segmentation regarding the processed dataset
#### Task 4: Use dimensionality reduction techniques to present the results


## 4- HW4- Deep Neural Networks
### Part 1- Customer Churn Prediction, dataset: Churn_Modelling.csv
### Part 2- Concrete Surface Crack Detection, dataset: 40k images with size 227x227 can be downloaded from web

#### Part 1 Details:
#### This is the dataset of the customers in a company. Our goal is to predict whether a customer will exit the company regarding a set of measured features.

#### Task 1: clean and process the data
#### Task 2: construct and train a fully connected Neural Network for predicting the customer churn and optimize it
#### Task 3: calculate the performance measures and analyze the results

#### Part 2 Details:
#### The datasets contain images of various concrete surfaces with and without crack. The image data is divided into two as negative (without crack) and positive (with crack) in a separate folder for image classification. Each class has 20000 images with a total of 40000 images with 227 x 227 pixels with RGB channels. The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). High resolution images found out to have high variance in terms of surface finish and illumination condition. No data augmentation in terms of random rotation or flipping or tilting is applied. Our goal is to detect if a picture is showing a surface crack or not.

#### Task 1: preprocess the images(channel normalization)
#### Task 2: construct and train a convolutional neural network for detecting the surface cracks and optimize it.
#### Task 4: calculate the performance measures and analyze the results.
*Bonus Task: use data augmentation (rotation, flipping, tilting and etc) to enhance the network's performance.
