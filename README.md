# Diabetes Prediction Model

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains code for a diabetes prediction model using the SVM (Support Vector Machine) algorithm. The model aims to predict whether a person is diabetic or not based on various features such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.

## Dataset

The dataset used for training and testing the model is stored in the `diabetes.csv` file. It contains 768 samples with 9 columns, including the target variable 'Outcome' (0 for non-diabetic, 1 for diabetic). 

## Getting Started

To get started with the code, follow the instructions below:

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/diabetes-prediction-model.git
   ```

2. Install the required dependencies. This can be done using the following command:

   ```shell
   pip install -r requirements.txt
   ```

3. Run the `Diabetes prediction.ipynb` script:
   

## Model Training and Evaluation

The code performs the following steps:

1. Data Pre-processing: The dataset is loaded and pre-processed. Descriptive statistics are calculated, and data standardization is applied.

2. Train-Test Split: The dataset is split into training and testing sets using a ratio of 80:20. Stratified sampling is used to ensure a balanced distribution of the target variable in both sets.

3. Model Training: The SVM model with a linear kernel is trained on the training data.

4. Model Evaluation: The trained model is evaluated using the accuracy score on the test data.

## Results

The accuracy of the trained model on the test set is printed to the console. Feel free to modify the code to include additional evaluation metrics or visualization of the results.

## Contributing

Contributions to this repository are always welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

Feel free to copy and use this README template for your project.
