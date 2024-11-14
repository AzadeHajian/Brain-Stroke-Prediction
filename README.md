# Brain Stroke Prediction

This repository contains Python code for predicting brain strokes using various machine learning models, including Decision Tree, Random Forest, and Logistic Regression. The dataset used for this project is from Kaggle: [Brain Stroke Dataset](https://www.kaggle.com/datasets/zzettrkalpakbal/full-filled-brain-stroke-dataset).

## Table of Contents
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Models Used](#models-used)
  - [Decision Tree](#decision-tree)
  - [Random Forest](#random-forest)
  - [Logistic Regression](#logistic-regression)
- [Cross-Validation](#cross-validation)
  - [K-Fold Cross-Validation](#k-fold-cross-validation)
  - [Leave-One-Out Cross-Validation (LOOCV)](#leave-one-out-cross-validation-loocv)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset used in this project is sourced from Kaggle and contains information about individuals, including various health parameters and whether they have experienced a brain stroke. The goal is to build a predictive model to identify the likelihood of a brain stroke based on these parameters.

## Project Structure
The repository is structured as follows:

brain-stroke-prediction/ │ ├── data/ │ └── brain_stroke.csv # Dataset file ├── scripts/ │ ├── decision_tree.py # Decision Tree implementation │ ├── random_forest.py # Random Forest implementation │ ├── logistic_regression.py # Logistic Regression implementation │ ├── cross_validation.py # Cross-validation implementation │ ├── README.md # Project overview and instructions └── requirements.txt # List of dependencies


## Models Used
### Decision Tree
The Decision Tree model is implemented to classify whether an individual is likely to experience a brain stroke based on their health parameters. The model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

### Random Forest
The Random Forest model is an ensemble method that combines multiple decision trees to improve the predictive performance and robustness. This model is also evaluated using similar metrics.

### Logistic Regression
Logistic Regression is a statistical method for binary classification. It is used in this project to predict the probability of a brain stroke. The model's performance is evaluated using accuracy, precision, recall, and F1-score.

## Cross-Validation
### K-Fold Cross-Validation
K-Fold Cross-Validation (with k=5) is used to evaluate the models' performance more reliably by splitting the data into 5 folds and using each fold for validation while the remaining folds are used for training.

### Leave-One-Out Cross-Validation (LOOCV)
LOOCV is another cross-validation method where each instance in the dataset is used once as a validation while the remaining instances form the training set. This method provides an unbiased evaluation but is computationally expensive.

## Results
The results from the various models and cross-validation methods are summarized and compared to determine the best-performing model for predicting brain strokes.

## Usage
1. **Clone the repository:**
   ```sh
   git clone git@github.com:AzadeHajian/ML-Stroke-predection.git
   


## Install the Required Dependencies

Before you can run the scripts, you'll need to install the necessary Python packages. Follow these steps to set up your environment:

2. **Create a virtual environment** (recommended):
   ```sh
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt

