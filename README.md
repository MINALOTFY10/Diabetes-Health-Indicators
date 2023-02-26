# Diabetes-Health-Indicators

This project aims to predict whether a user has prediabetes, diabetes, or no diabetes based on various features such as age, BMI, and blood pressure.

## Dataset

The dataset used for this project is the Pima Indians Diabetes Database, which contains medical information for Pima Indians in Arizona. The dataset includes 768 instances with 8 features.

## Methodology

The following steps were taken to build the prediction model:

1. Data cleaning and preprocessing
2. Feature selection
3. Model selection and hyperparameter tuning
4. Model evaluation

Several machine learning algorithms, such as logistic regression, decision tree, random forest, and support vector machine, were tested for model selection.

## Results

The best performing model was the random forest classifier, which achieved an accuracy of 80% on the test set.

## Usage

To use this project, follow these steps:

1. Clone this repository to your local machine
2. Install the required Python packages listed in `requirements.txt`
3. Run `python3 main.py` to start the program
4. Enter the required user information when prompted
5. View the predicted diagnosis for the user
