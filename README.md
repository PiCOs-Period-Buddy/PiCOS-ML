# PiCOS-ML
> PiCOS-ML

## LINK
https://colab.research.google.com/drive/1gqK1OsIWBqrsdQYqFfbUq_rYmOO3XSWr?usp=sharing </br>
https://colab.research.google.com/drive/1KO25mqtaKtkZ1ojStP-XXky3L4El3yOy?usp=sharing </br>

## Table of contents
* [Brief Description](#brief-description)
* [Tools Needed](#tools-needed)
* [Download the Dataset](#download-the-dataset)
* [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
* [Building & Training Model](#building--training-model)
* [Author](#author)

## Brief Description
PiCOS-ML is a repository contains of files that used to provide machine learning for PCOS self-assessment feature in PiCOS app.
The following are the step-by-step in replicating our works:
1. Downloading dataset
2. Cleaning data
3. Preprocessing data
4. Building model
5. Importing model

## Tools Needed
1. Spreadsheet / excel
2. Google colab

## Download the Dataset
We use an open dataset contains about 500 rows detecting PCOS with its symptoms
https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos

## Data Cleaning and Preprocessing
### The steps in cleaning data:
1. Removing nulls, unnecessary data
2. Removing unnecesary columns
3. Discretize age and marrital years data

### Preprocessing data:
1. Data labeling
2. Dataset splitting
3. Feature scaling
4. Data augmenting (adding noise), oversampling imbalance dataset

## Building & Training Model
Model built with neural networks, using dropout and batch normalization to minimize overfitting

## Author
* Nabila Aprilia Putri&nbsp;&nbsp;(Sistem Informasi ITS)
* Venny Caecillia&nbsp;&nbsp;(Sains Data ITERA)
