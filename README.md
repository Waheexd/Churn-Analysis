🧠 Customer Churn Analysis Dashboard and Prediction System
📊 Overview

This project focuses on customer churn prediction and analysis using machine learning and interactive data visualization.
The goal is to identify customers likely to churn, understand key churn drivers, and present insights through an interactive Power BI dashboard.

⚙️ Tech Stack

Python Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

Visualization Tool: Power BI

Machine Learning Models: Random Forest, Logistic Regression

Other Tools: DAX (Data Analysis Expressions) for Power BI

🚀 Project Workflow
1. Data Preparation

Imported raw customer data and performed data cleaning, handling missing values, and encoding categorical variables.

Conducted feature engineering to create new variables that improve model performance.

2. Exploratory Data Analysis (EDA)

Used Matplotlib and Seaborn to visualize churn patterns, correlations, and customer behavior trends.

Identified key factors such as tenure, contract type, and monthly charges influencing churn.

3. Model Building and Evaluation

Implemented and compared two ML algorithms:

Random Forest Classifier — Achieved ~86% accuracy with feature importance insights.

Logistic Regression — Provided interpretable results for business decision-making.

Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix.

4. Dashboard Development

Created an interactive Power BI dashboard for churn analysis and customer segmentation.

Integrated DAX formulas for KPIs and automation, reducing manual reporting effort by 40%.

📈 Key Insights

Customers with shorter tenure and month-to-month contracts show higher churn probability.

Automatic payments and long-term contracts significantly reduce churn rate.

🧩 Future Improvements

Integrate real-time churn monitoring using APIs or streaming data.

Experiment with Gradient Boosting and XGBoost for better accuracy.

Deploy model as a web app using Streamlit or Flask for business users.
