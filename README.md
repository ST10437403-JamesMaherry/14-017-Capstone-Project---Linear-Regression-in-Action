# 🏠 Linear Regression in Action – Capstone Project

## Overview

This project applies Multiple Linear Regression to the `boston.csv` dataset in order to predict median house values in the Boston area.  
The objective is to explore the relationships between housing features and property values, build a predictive model, and generate insights that support real estate pricing and investment decisions.

---

## Problem Statement

The `boston.csv` dataset provides insight into housing market characteristics such as:

- Crime rates
- Residential land zoning proportions
- Average number of rooms per dwelling
- Socioeconomic indicators
- Median value of houses per suburb or town

The goal of this project is to predict the median value of houses (`medv`) using selected independent variables and evaluate the performance of a multiple linear regression model.

By completing this analysis, we aim to:

- Understand key factors influencing house prices
- Quantify relationships between housing features and property values
- Provide actionable insights for pricing strategies and investment decisions

---

## Project Workflow

### 1️⃣ Data Preparation
- Load the dataset into `Capstone Linear Regression.ipynb`
- Inspect the dataset structure
- Clean data if necessary
- Handle missing values (if applicable)
- Confirm correct data types

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualise the distribution of the dependent variable (`medv`)
- Visualise distributions of independent variables
- Identify correlations, trends, and patterns
- Generate scatter plots to explore feature relationships

### 3️⃣ Feature Selection

**Independent Variables:**
- `rm` – Average number of rooms per dwelling
- `lstat` – Percentage of lower-status population

**Dependent Variable:**
- `medv` – Median value of owner-occupied homes

### 4️⃣ Model Development
- Split the dataset into independent variables (X) and dependent variable (y)
- Apply a 75:25 train-test split
- Train a Multiple Linear Regression model using the training set
- Print and interpret model intercept and coefficients

### 5️⃣ Model Evaluation
Evaluate model performance using:
- Mean Squared Error (MSE), or
- Root Mean Squared Error (RMSE)

Generate predictions on the test set and compare them with actual values.

### 6️⃣ Error Analysis
Generate an error plot (Predicted vs Actual values) to:
- Visualise prediction accuracy
- Detect bias or variance issues
- Identify patterns in residuals

---

## Key Outputs

- Regression intercept and coefficients
- Interpretation of feature impacts on median house values
- MSE / RMSE evaluation metrics
- Scatter plots of feature relationships
- Error plot comparing predicted vs actual values
- Summary of findings and insights

<img width="866" height="643" alt="HISTOGRAMS" src="https://github.com/user-attachments/assets/186b7164-653e-45f9-80a6-cd8b8a7fd845" />

<img width="845" height="625" alt="CORRELATION MATRIX" src="https://github.com/user-attachments/assets/10182e20-f3b8-4fe7-b675-f4341189ffdd" />

<img width="1181" height="645" alt="HISTPLOT" src="https://github.com/user-attachments/assets/4098d278-c8f9-492e-882d-fb1fa0aa5976" />

<img width="1485" height="610" alt="ACTUAL VS PREDICTED" src="https://github.com/user-attachments/assets/b83700ed-3202-4402-a023-192eb11c042f" />

---

## Technologies Used

| Tool | Version |
|------|---------|
| Python | 3.12 |
| Jupyter Notebook | Latest |
| pandas | See requirements.txt |
| numpy | See requirements.txt |
| matplotlib / seaborn | See requirements.txt |
| scikit-learn | See requirements.txt |

---

## ⚙️ Setup & Installation

### Prerequisites
- Python 3.12 installed ([python.org](https://www.python.org/downloads/))
- Git installed ([git-scm.com](https://git-scm.com))

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/ST10437403-JamesMaherry/14-017-Capstone-Project---Linear-Regression-in-Action.git
```

**2. Create a virtual environment**
```bash
python -m venv .venv
```

**3. Activate the virtual environment**

Windows:
```bash
.venv\Scripts\activate
```
Mac/Linux:
```bash
source .venv/bin/activate
```

**4. Install dependencies**
```bash
pip install -r requirements.txt
```

**5. Launch Jupyter Notebook**
```bash
jupyter notebook
```

**6. Open and run the notebook**
- Open `Capstone Linear Regression.ipynb`
- Run all cells in order via **Kernel → Restart & Run All**

---

## 📁 Project Structure
```
├── Capstone Linear Regression.ipynb   # Main analysis notebook
├── boston.csv                          # Dataset
├── requirements.txt                    # Python dependencies
├── .gitignore                          # Files excluded from version control
└── README.md                           # Project documentation
```

---

## Conclusion

This capstone project demonstrates how multiple linear regression can be applied to real-world housing data to uncover meaningful relationships and support data-driven decision-making in the residential property market.

Through data preparation, exploratory analysis, model building, and evaluation, this project delivers both predictive insight and practical interpretation relevant to the property industry.
