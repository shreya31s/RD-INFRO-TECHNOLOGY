# RD-INFRO-TECHNOLOGY
Data analysis- internship project

## Project Title: Customer Churn Analysis and Prediction

### Project Overview

The project aims to analyze customer churn in a telecommunications company and develop predictive models to identify at-risk customers. The ultimate goal is to provide actionable insights and recommendations to reduce churn and improve customer retention.

### Data Sources
telecommunications customer churn datasets: The primary dataset used for this analysis is the "telco_churn.csv" file, containing detailed information about the churns in telecommunication customers.

### Tools
- Excel - Data cleaning 
- Python – Core language for analysis and machine learning
- Google Colab – Free cloud-based Jupyter notebooks with GPU support.
- Pandas – Data manipulation and preprocessing.
- NumPy – Numerical computations.
- Matplotlib – Basic plotting and graphs.
- Seaborn – Statistical visualizations.
- Scikit-Learn (sklearn) – Model training, evaluation, and metrics.
- RandomForestClassifier – Churn prediction.
- KMeans – Customer segmentation.
- StandardScaler – Data scaling.
- Confusion Matrix – Performance visualization.
- Classification Report – Accuracy, precision, recall, F1-score.
- GitHub – Store and share project files.

### Data cleaning and preprocessing

In the initial data preparation phase, following tasks were performed:
1. Handle missing values in the dataset
2. Convert categorical variables numerical representations into using techniques like one-hot encoding

### Exploratory Data Analysis(EDA)

- Calculating and visualizing the overall churn rate.
- Exploring customer distribution by various demographics.
- Analyzing tenure distribution.
- Investigating relationships between churn and different contract types/payment methods.

### Customer Segmentation

- Segment customers based on tenure, monthly charges, and contract type.
- Analyze churn rates across these segments.

### Churn Prediction Model

- Develop a churn prediction model using machine learning algorithms like logistic regression.
- Evaluate the model's performance using appropriate metrics

### Customer Retention Strategies

- Propose data-driven strategies to reduce churn. Identify key factors influencing churn and suggest actions.
- Calculate the lifetime value (LTV) of customers.
- Identify high-value customers at risk of churning.

### Results

The analysis results are summerized as follows:
- High churn is observed in month-to-month contracts compared to long-term contracts.
- Customers with higher monthly charges are more likely to churn.
- Short-tenure customers (less than 12 months) show higher churn.
- Customer Segmentation (KMeans Clustering):
     - Segment 0 (High Churn Risk): Short tenure, high monthly charges.
     - Segment 1 (Loyal Customers): Long tenure, stable charges.
     - Segment 2 (Moderate Risk): Medium tenure and charges.
- High Lifetime Value (LTV) customers are at risk, especially in the month-to-month contract group.
-  Model Performance (Random Forest):
     - Accuracy: ~80%
     - Recall (Churn Detection): ~74% – Model effectively detects customers likely to 
        churn.
     - Precision: ~72% – Majority of churn predictions are correct.
- Visual Insights:
    - Tenure vs. Charges Scatter Plot: Clear churn trend among short-tenure, high-charge 
       customers.
    - Box Plot (Monthly Charges): Churners typically have higher monthly charges.

### Recommendations

Based on the analysis, I recommend the following actions:
- Focus on Retention for High-Risk Customers
- Incentivize Long-Term Contracts
- Improve Payment Flexibility
- Engage Early
