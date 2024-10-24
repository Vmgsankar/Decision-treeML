
# Decision Tree Classification - Bank Loans Dataset

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Process](#modeling-process)
- [Results](#results)

## Overview
This project implements a **Decision Tree Classification** model to predict whether a person will default on a loan based on various features such as age, income, employment status, and other relevant financial indicators.

## Dataset
The dataset contains various customer attributes and their corresponding loan status (default or not). The key features include:
- `age`: Age of the applicant.
- `ed`: Level of education.
- `employ`: Number of years employed.
- `address`: Number of years at the current address.
- `income`: Yearly income of the applicant.
- `debtinc`: Debt-to-income ratio.
- `creddebt`: Credit card debt.
- `othdebt`: Other debts.
- `default`: Whether the applicant has defaulted on the loan (1 = default, 0 = no default).

## Dependencies
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

You can install the required dependencies by running:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Vmgsankar/Decision-treeML
   ```
2. Navigate to the project directory:
   ```bash
   cd Decision-treeML
   ```

## Usage
1. Load the dataset using `pandas`.
2. Preprocess the data (handle missing values, encode categorical variables).
3. Split the data into training and testing sets.
4. Train the Decision Tree model using `scikit-learn`'s `DecisionTreeClassifier`.
5. Evaluate the model using metrics such as accuracy, precision, recall, F1-score, and plot the confusion matrix.
6. Visualize the decision tree and interpret the results.

## Modeling Process
The following steps were followed:
1. Data exploration and preprocessing.
2. Splitting the data into training and testing sets.
3. Building the decision tree model.
4. Model evaluation using confusion matrix and classification report.

## Results
- The model achieved an accuracy of 0.7800313992215401 on the test data.
- Further results and analysis are provided in the project notebook.
