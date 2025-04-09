# 💰🏦 Credit Risk Prediction in R

A data-driven approach to predicting loan default probabilities using logistic regression and random forest models, aimed at enhancing creditor decision-making and risk assessment.

## 🚀 Overview

This project explores credit risk through statistical modeling on a dataset of **25,701 observations**. By identifying key features that influence loan default, it challenges traditional assumptions and offers actionable insights for financial institutions.

## 🧠 Methodology

- **Data Cleaning**: Removed outliers, handled missing values, and standardized key variables.
- **Feature Engineering**: Selected relevant features impacting default using domain knowledge and data exploration.
- **Modeling**:
  - Built logistic regression models with stepwise selection to optimize predictors.
  - Used random forest for KPI ranking and cross-validation.
- **Insight Extraction**: Identified loan amount, interest rate, home ownership, and credit history length as top predictors of default.
- **Statistical Analysis**: Found weak significance of prior defaults (p-value > 0.8), questioning traditional credit scoring assumptions.

## 📊 Results

- **Model Accuracy**: Achieved **84.92% accuracy** on test data.
- **Top Predictors**:
  - Loan Amount
  - Interest Rate
  - Home Ownership
  - Length of Credit History
- **Key Insight**: Prior defaults, often relied upon by creditors, showed **insignificant predictive power** — promoting a shift toward data-driven evaluation.

## 🛠️ Tech Stack (R Libraries)

- `caret` – model training & validation  
- `MASS` – stepwise regression  
- `stats` – statistical modeling  
- `randomForest` – feature ranking & classification  
- `knitr` – reporting and summaries  
- `cluster`, `flexclust`, `fpc`, `NbClust`, `mclust` – clustering and evaluation  
- `ROCR` – model performance & ROC analysis  

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/JaySinghvi/Credit-Risk-Prediction.git
   cd Credit-Risk-Prediction

2. Open the R project or R script in RStudio.

3. Install packages:
`install.packages(c("caret", "MASS", "stats", "randomForest", "knitr", 
                   "cluster", "flexclust", "fpc", "NbClust", "mclust", "ROCR"))`
4. Run the main file and check for outputs
