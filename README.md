# Breast-Cancer-Tumor-Prediction
This repository contains a Python script using Scikit-learn library to build a machine learning model that can predict if a tumor is malignant or benign based on a given dataset.

# Description
The script employs the Naive Bayes algorithm, specifically the GaussianNB implementation, to train a predictive model using a breast cancer dataset provided by Scikit-learn. The dataset contains various features of the tumor which the script uses to learn patterns related to the nature of the tumor. It then uses this trained model to predict whether a new tumor is malignant or benign.

# Features
Importing a pre-defined dataset

Splitting data into training and test sets

Training a Gaussian Naive Bayes classifier

Making predictions with the trained model

Evaluating model performance with accuracy score

# Code
The script begins by importing necessary libraries and the dataset. It then organizes the data into labels and features for easier processing. The data is split into training and testing sets, with 33% of the data reserved for testing. The Naive Bayes classifier is initialized and then trained using the training data. The trained model is used to make predictions on the test set, and the accuracy of these predictions is evaluated using the accuracy_score method from Scikit-learn's metrics module.

# Requirements
Python 3.x
Scikit-learn library
NumPy (required by Scikit-learn)
Usage
To use this code, you need to have Python and the required libraries installed. Once you have those, simply clone the repository and run the Python script.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.

# Acknowledgments
The Breast Cancer Wisconsin (Diagnostic) Data Set from Scikit-learn was used for this project.
Thanks to the Scikit-learn team for the useful machine learning library.
This is a simple, but powerful demonstration of how machine learning can be used in medical diagnosis. The hope is to inspire further development and improvement on these tools to help save lives. The current model can certainly be optimized further, and other machine learning algorithms may be used for comparison. Pull requests and contributions are welcome.

Please note that this model is a demonstration and should not be used for actual medical diagnosis. Always consult with a healthcare professional for medical advice.
