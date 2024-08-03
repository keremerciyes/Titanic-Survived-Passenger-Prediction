# Titanic Passengers Survival Prediction

## Overview

This project predicts the 'Survived' feature of Titanic passengers using a machine learning pipeline that includes One-Hot Encoding, Principal Component Analysis (PCA), and Isolation Forest. The dataset is preprocessed by removing unnecessary data to improve the prediction accuracy.

## Table of Contents

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Introduction

The Titanic dataset is used to predict whether a passenger survived or not. The dataset is preprocessed to remove irrelevant features, encoded using One-Hot Encoding, and reduced in dimensionality using PCA. The Isolation Forest algorithm is then applied to make predictions on the 'Survived' feature.

## Data Preprocessing

The data preprocessing steps include:
1. **Removing unnecessary data:** Columns that do not contribute to the prediction are removed.
2. **One-Hot Encoding:** Categorical features are converted into numerical format using One-Hot Encoding.
3. **PCA:** Principal Component Analysis is used to reduce the dimensionality of the dataset, retaining the most important features.

## Modeling

The Isolation Forest algorithm is used to predict the 'Survived' feature. This unsupervised learning algorithm identifies the anomalies in the dataset, which in this context are considered as survival predictions.

## Results

The results of the predictions are evaluated and presented in the Jupyter Notebook `isolation_forest_titanic_data.ipynb`.

## Installation

To run this project, you will need Python and the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib

## Usage

1. **Open the Jupyter Notebook:**

Open `isolation_forest_titanic_data.ipynb` in Jupyter Notebook or JupyterLab.

2. **Run the Notebook:**

Execute the cells in the notebook to preprocess the data, apply PCA, and make predictions using Isolation Forest.
