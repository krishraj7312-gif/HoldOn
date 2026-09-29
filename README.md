# Customer Churn Analysis

An exploratory data analysis project focused on understanding customer churn patterns using customer, subscription, and support data. The project uses Python, Pandas, SQLite, and data visualization to identify factors associated with customer churn and generate actionable business insights.

## 📌 Project Overview

Customer churn is an important business problem because losing customers can directly impact revenue.

This project analyzes customer behavior, subscription details, complaints, customer satisfaction, tenure, and revenue-related information to understand:

- Which customer segments have higher churn
- How subscription and contract types affect churn
- The relationship between complaints, CSAT, tenure, and churn
- Monthly churn trends
- Potential revenue impact of customer churn

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **SQLite**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## 📂 Dataset

The dataset contains customer, subscription, cancellation, and customer-support related information.

Important fields include:

- Customer ID
- Subscription Start Date
- Subscription Type
- Plan Type
- Contract Type
- Renewal Date
- Cancellation Date
- Cancellation Reason
- Monthly Charges
- CLTV
- Churn Score
- Customer Country/State
- Gender
- Complaint Date
- Escalations
- CSAT Score
- Complaint Count

## 🔧 Data Preparation

The project performs data preparation and feature engineering before analysis.

### Data Cleaning

- Handled missing values
- Standardized data formats
- Processed date columns
- Removed/handled unnecessary data
- Combined relevant customer, subscription, and support information

### Feature Engineering

Several useful analytical features were created:

- **Churn Flag** – identifies whether a customer churned
- **Tenure Days** – calculates customer tenure based on subscription and cancellation/current dates
- **Complaint Count** – represents the number of complaints associated with customers
- **Churn Risk** – categorizes customers based on their churn score
- **Cancellation Month** – used for monthly churn trend analysis

## 📊 Analysis Performed

The project analyzes churn across different dimensions, including:

- Subscription plans
- Contract types
- Customer tenure
- States
- Complaint frequency
- Customer satisfaction (CSAT)
- Monthly charges and revenue
- Monthly churn trends

Visualizations and aggregated analysis were used to identify important patterns in the customer base.

## 📈 Key Findings

The analysis identified the following major insights:

- **28.6%** of customers were identified as churned.
- **71.4%** of customers were retained.
- Churn was higher among **monthly-plan customers**.
- **Basic plans** showed notable churn concentration.
- **Karnataka** showed notable customer churn.
- **September 2024** showed a notable concentration of churn.
- Estimated revenue loss associated with churn was approximately **18%**.

## 💡 Business Insights

The analysis suggests that customer retention efforts can focus on:

- Monitoring customers with higher churn-risk scores
- Investigating churn among monthly-plan customers
- Understanding issues affecting Basic-plan customers
- Monitoring customers with frequent complaints
- Tracking customer satisfaction and support interactions
- Monitoring monthly churn trends to identify emerging problems

## 📁 Project Structure

```text
├── Customer_Churn_Analysis.ipynb
├── README.md
└── customer_data.csv
