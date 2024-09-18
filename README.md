# Salary Prediction Using Linear Regression

## Description

This project implements a simple linear regression model to predict employee salaries based on their years of experience. The dataset used is the popular **Salary_Data.csv**, which contains two features: years of experience and salary. The goal of this project is to train a machine learning model that can predict an individual's salary given their years of experience.

## Features

- Load and preprocess data from CSV
- Train a linear regression model
- Evaluate model performance using Mean Squared Error (MSE) and R² score
- Visualize the training and test set results
- Make predictions for specific years of experience (e.g., 12 and 20 years)
- Save the trained model using Python's `pickle` library for later use

## Requirements

The following Python libraries are required:

```bash
numpy
pandas
scikit-learn
matplotlib
```

You can install the necessary libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Dataset

The dataset `Salary_Data.csv` should have two columns:

1. `YearsExperience` - Number of years of work experience.
2. `Salary` - Salary in dollars.

Place this dataset in the root directory of the project.

## Project Structure

```
salary-prediction/
│
├── Salary_Data.csv          # Dataset file
├── salary_prediction.py     # Python script for salary prediction
├── linear_regression_model.pkl # Pickled model after training
├── README.md                # Project documentation
```

## Usage

1. Clone the repository or download the project.
2. Ensure that the `Salary_Data.csv` file is in the same directory as the script.
3. Run the Python script to train the model and make predictions:

```bash
python salary_prediction.py
```

The script will:
- Train the linear regression model on 80% of the data.
- Evaluate it on 20% of the test data.
- Print a comparison of actual and predicted salaries.
- Show visualizations for both training and test sets.
- Save the trained model as `linear_regression_model.pkl` using `pickle`.

You can also see salary predictions for 12 and 20 years of experience as an example.

## Results

Once the script is executed, it will print the following details:

- Comparison of actual vs predicted salaries for the test set
- Visualizations for both training and test sets
- Predicted salaries for 12 and 20 years of experience
- Model performance in terms of R² and MSE

## Example Output

```
![Screenshot (83)](https://github.com/user-attachments/assets/cad369cc-ea36-403c-b218-e8c304f11050)
