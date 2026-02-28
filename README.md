# Loss Given Default (LGD) Modeling for Credit Risk

## 📌 Project Overview
This repository contains a comprehensive Jupyter Notebook (`LGD_practice.ipynb`) that demonstrates an end-to-end machine learning workflow for predicting **Loss Given Default (LGD)**. LGD is a key component of credit risk modeling, representing the portion of an asset that is lost when a borrower defaults.

The project follows a structured approach, moving from data ingestion and cleaning to model validation and a simulated deployment.

## 🛠️ Project Workflow
1. **Library Integration**: Loading essential data science libraries (`pandas`, `seaborn`, `sklearn`, etc.).
2. **Data Exploration**: Initial analysis of the dataset to identify target variables and data types.
3. **Outlier Treatment**: Implementation of outlier "capping" (Winsorization) using the IQR method to maintain data integrity while reducing noise.
4. **Multicollinearity Analysis**: Rigorous testing of independent variables using **Variance Inflation Factor (VIF)** to ensure model stability.
5. **Preprocessing**: Scaling and standardizing features for optimal regression performance.
6. **Modeling**: Training a Linear Regression model and evaluating it using metrics like MAE, MSE, and RMSE.
7. **Deployment Simulation**: Scoring a separate deployment dataset to predict LGD values for new observations.

## ⚠️ Methodology & Thresholds
**Note to Reviewers:** Some thresholds and parameters used in this notebook (e.g., specific VIF cut-off points and outlier boundaries) were determined by **specific task requirements** provided during the exercise. While they serve the purpose of this demonstration, they may differ from standard industry "best practices" depending on the specific risk appetite and regulatory requirements of a financial institution.

## 💻 Technologies Used
* **Python 3.x**
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Statistical Analysis:** Statsmodels (VIF calculation)

## 🚀 How to Use
1.  Clone this repository.
2.  Ensure you have the dataset file (`lgd_data.xlsx`) in the same directory.
3.  Install the required dependencies:
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn statsmodels openpyxl
    ```
4.  Run the notebook using Jupyter Lab, Jupyter Notebook, or VS Code.

---
*Created as part of a professional development exercise in Credit Risk Data Science.*
