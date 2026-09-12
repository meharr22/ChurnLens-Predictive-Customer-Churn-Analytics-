#  ChurnLens AI – Customer Retention Intelligence Platform

> An end-to-end Customer Churn Analytics, Prediction, and Retention Intelligence solution built using Python, Machine Learning, SQL, and Power BI.


##  Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project helps identify customers who are likely to leave, understand the reasons behind churn, and provide actionable retention strategies.

**ChurnLens AI** combines data analytics, machine learning, and interactive dashboards to transform customer data into business insights.



##  Business Objectives

- Analyze customer churn patterns and behavior.
- Identify key factors driving customer attrition.
- Predict customers at risk of churning.
- Generate retention recommendations.
- Enable decision-making through interactive Power BI dashboards.


##  Tech Stack

| Category | Tools |
|-----------|---------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-Learn |
| Database | SQL |
| Dashboarding | Power BI |
| Model Storage | Joblib |
| Notebook | Jupyter Notebook |



##  Project Structure

```text
ChurnLens-AI/
│
├── dashboard/
│   └── churn_dashboard_final.pbix
│
├── data/
│   ├── Customer_Data.csv
│   ├── Prediction_Data.xlsx
│   ├── Predictions.csv.xlsx
│   └── Retention_Recommendations.csv
│
├── models/
│   └── churn_model.joblib
│
├── notebooks/
│   └── churn_prediction.ipynb
│
├── scripts/
│   ├── generate_full_predictions.py
│   ├── retention_recommendation.py
│   └── validate_metrics.py
│
├── README.md
└── requirements.txt
```


##  Key Features

###  Customer Churn Analytics

- Customer demographic analysis
- Churn distribution tracking
- Geographic churn insights
- Service usage analysis
- Contract and payment behavior analysis

###  Churn Prediction Engine

- Machine learning-based churn prediction
- Churn probability scoring
- High-risk customer identification
- Customer risk segmentation

###  Retention Intelligence

- Personalized retention recommendations
- Customer risk categorization
- Actionable business insights
- Data-driven retention strategies


##  Dashboard Pages

###  Churn Analysis Summary

Provides a comprehensive overview of:

- Total Customers
- Total Churn
- Churn Rate
- New Joiners
- Churn by Gender
- Churn by Age Group
- Churn by State
- Churn by Contract Type
- Churn by Payment Method
- Churn by Services



###  Churn Reason Analysis

Identifies:

- Major churn categories
- Primary churn reasons
- Service dissatisfaction trends
- Pricing-related churn patterns
- Customer experience issues


###  Churn Prediction Dashboard

Highlights:

- Predicted Churn Customers
- Customer Risk Profiles
- Churn Probability Scores
- Contract Risk Analysis
- Service Risk Analysis
- Retention Opportunities



##  Machine Learning Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Prediction Generation
       ↓
Power BI Dashboard
```



##  Business Insights

- Month-to-Month contracts show the highest churn risk.
- Customers without value-added services are more likely to churn.
- Longer-tenure customers demonstrate stronger retention.
- Internet service usage significantly impacts churn behavior.
- Service dissatisfaction and pricing concerns are major churn drivers.



##  How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/churnlens-ai.git
cd churnlens-ai
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Generate Predictions

```bash
python scripts/generate_full_predictions.py
```

### 4. Generate Retention Recommendations

```bash
python scripts/retention_recommendation.py
```

### 5. Open Power BI Dashboard

```text
dashboard/churn_dashboard_final.pbix
```



##  Future Enhancements

- Real-time churn monitoring
- Automated model retraining
- Cloud deployment
- Customer Lifetime Value (CLV) integration
- Explainable AI (XAI)
- Advanced retention campaign optimization



##  Author

**Mehar Arora**



