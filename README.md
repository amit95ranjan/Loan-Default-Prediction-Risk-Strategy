# 🏦 Loan Default Prediction & Risk Strategy

## 📌 Project Overview
Financial institutions incur significant losses when borrowers default on loans. This project analyzes historical loan data to identify patterns associated with high-risk borrowers. By building a predictive machine learning model, the project aims to automate the loan eligibility process and suggest specific risk mitigation strategies to reduce the bank's non-performing assets (NPA).

## 📂 Project Files
* **`Loan Default Prediction & Risk Strategy.ipynb`**: The technical Jupyter Notebook containing data cleaning, EDA, feature engineering, and model training.
* **`Loan Default Prediction & Risk Strategy.pdf`**: A comprehensive report summarizing the findings, visualizations, and business recommendations.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, Random Forest, Decision Trees)
* **Metrics:** Precision, Recall, F1-Score, ROC-AUC (Focus on minimizing False Negatives)

## 📊 Key Workflow

### 1. Data Understanding & Cleaning
* Handled missing values in demographic and financial columns.
* Detected and treated outliers in `Income` and `Loan Amount`.
* Analyzed class imbalance (Defaults vs. Non-Defaults).

### 2. Exploratory Data Analysis (EDA)
* **Financial Health:** Analyzed Debt-to-Income (DTI) ratios and their correlation with default rates.
* **Demographics:** Examined the impact of employment length, home ownership, and education level on repayment behavior.
* **Loan Characteristics:** Investigated interest rates and loan grades assigned by the bank.

### 3. Machine Learning Modeling
Different classification models were tested to predict the binary outcome (Default / No Default):
* **Logistic Regression:** Used as a baseline for interpretability.
* **Random Forest Classifier:** Implemented to capture non-linear relationships and feature importance.
* **Model Optimization:** Tuned hyperparameters to improve Recall (Sensitivity), as missing a defaulter is more costly than flagging a good borrower.

## 💡 Risk Strategy & Business Insights
Based on the analysis, the following strategies are recommended:
1.  **Strict DTI Thresholds:** Applicants with a Debt-to-Income ratio above a certain threshold (e.g., 40%) show a significantly higher probability of default.
2.  **Interest Rate Adjustment:** High-risk profiles identified by the model should be offered loans at adjusted interest rates to cover potential losses (Risk-Based Pricing).
3.  **Enhanced Verification:** employment verification should be mandatory for applicants requesting high loan amounts with short credit histories.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone:  https://github.com/amit95ranjan/Loan-Default-Prediction-Risk-Strategy
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  **Run the Notebook:**
    ```bash
    jupyter notebook "Loan Default Prediction & Risk Strategy.ipynb"
    ```

---
*Created by Amit Ranjan - Data Analyst*
