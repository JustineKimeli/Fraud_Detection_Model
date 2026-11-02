# Banking Transactions Fraud Detection

## Project Overview

This project focuses on analysing banking transaction data to identify potentially fraudulent activities using Python and machine learning.

The goal is to explore transaction patterns, prepare the data for modelling, and develop a classification model that can distinguish between legitimate and potentially fraudulent transactions.

Fraud detection is an important part of financial risk management because identifying suspicious transactions can help reduce financial losses and improve transaction security.

## Objectives

- Explore and understand banking transaction data.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) to identify transaction patterns.
- Prepare features and target variables for machine learning.
- Split the dataset into training and testing sets.
- Build and evaluate a fraud detection classification model.
- Interpret model performance and identify areas for improvement.

## Technologies and Libraries

The project uses the following Python tools:

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualisation.
- **Seaborn** – Statistical data visualisation.
- **Scikit-learn** – Data preprocessing, model training, and evaluation.
- **Jupyter Notebook** – Interactive development and analysis.

## Project Workflow

1. **Data Loading:** Import the banking transactions dataset into Pandas.
2. **Data Exploration:** Examine the dataset structure, columns, data types, and distributions.
3. **Data Cleaning:** Identify and handle missing values, duplicates, and inconsistent records where necessary.
4. **Exploratory Data Analysis:** Investigate transaction characteristics and potential fraud patterns.
5. **Feature Preparation:** Separate predictor variables from the target variable.
6. **Data Splitting:** Divide the dataset into training and testing sets.
7. **Model Development:** Train a classification model to identify potentially fraudulent transactions.
8. **Model Evaluation:** Assess performance using appropriate classification metrics.

## Dataset

The project uses `banking_transactions.csv`.

The dataset contains banking transaction records for analysis and fraud detection. The target variable should identify whether a transaction is fraudulent or legitimate.

## Model Evaluation

Fraud detection datasets can be imbalanced, so accuracy alone may not provide a reliable picture of model performance.

Evaluation may include:

- Precision
- Recall
- F1-score
- Confusion matrix
- ROC-AUC

Recall and precision are particularly useful for understanding how effectively the model identifies fraudulent transactions while limiting false alarms.

## Project Structure

```text
fraud-detection/
│
├── banking_transactions.csv
├── fraud_detection.ipynb
├── README.md
└── requirements.txt
```

## Installation and Setup



Navigate to the project directory:

```bash
cd fraud-detection
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows Git Bash:

```bash
source venv/Scripts/activate
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter:

```bash
jupyter notebook
```

Open `fraud_detection.ipynb` and run the notebook cells.

## Key Learning Outcomes

- Practical application of Python for financial data analysis.
- Data cleaning and exploratory data analysis.
- Preparing datasets for supervised machine learning.
- Understanding classification problems.
- Evaluating machine learning models using appropriate metrics.
- Communicating analytical findings.

