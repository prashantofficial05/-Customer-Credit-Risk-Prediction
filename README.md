# Customer Credit Risk Prediction

  **Introduction:** 

   This project uses demographic and financial data to build a machine learning model to predict 
  customer credit default risk. The objective is to assess the risk profiles of loan applicants, 
  enabling lenders to make more informed and strategic decisions. This project aims to reduce loan 
  defaults and improve lending outcomes by analyzing credit behavior patterns.

   **Goal:**
   
   To predict whether a customer is likely to default on a loan by analyzing their demographic and 
   financial attributes. The model helps financial institutions in risk assessment, thereby improving 
   lending efficiency and reducing bad debts.

   **Description:**
   
   The project uses a public credit risk dataset from Kaggle containing features like age, income, and 
   loan amount, credit score, employment type, and more. It involves:

   **Data Preprocessing:** Handling missing values, encoding categorical features, and normalizing 
                           numerical columns
   **Feature Engineering:** Creating new features like Debt-to-Income Ratio to improve model performance.

   **Model Building:** Training classification models, including Logistic Regression and Random Forest.

   **Evaluation:** Assessing model performance using accuracy, precision, recall, F1-score, and 
                   confusion matrix.
   **Visualization:** Exporting the processed dataset to Power BI for creating dashboards and insights.

   **Skills:**
   
    **Python (Pandas, NumPy, Matplotlib, Seaborn)** – For data processing and visualization
    **Scikit-learn** – For machine learning modeling and evaluation
    **SQL** – For querying and cleaning raw financial data
    **Power BI** – For data visualization and dashboard creation

  **Tools:**
      **Python** (Jupyter Notebook)
      **SQL** (PostgreSQL)
      **Power BI**
      **Libraries:** pandas, scikit-learn, seaborn, matplotlib

**Metrics:**
    **Model Accuracy:** 84% with Logistic Regression, 88% with Random Forest
    **Precision & Recall:** Evaluated to ensure minimal false positives in credit default predictions
    **Feature Importance:** Identified top features influencing credit default, such as Credit Score and 
                Loan Amount
    **Improvement:** Risk prediction accuracy improved by 14% over baseline

**Key Findings:**
   - Credit Score and Debt-to-Income Ratio were the most influential features in default prediction.
   - Customers with irregular employment types showed a higher risk of default.
   - Logistic Regression provided interpretable results, while Random Forest offered better performance.
   - Financial insights helped define thresholds for lending eligibility based on risk scores.

**Next Steps:**
    
  **Deploy Model:** Integrate with a financial institution’s decision-making system for real-time credit 
                 Risk scoring.
  **Expand the Dataset:** Incorporate more variables like transaction history and spending behavior.
  **Automated Alerts:** Develop alert systems for high-risk customer segments.
  **Regulatory Compliance:** Ensure models comply with fair lending regulations and are bias-free.
