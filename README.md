\# 📊 Telco Customer Churn Prediction \& Retention Analytics



\*\*Predictive analytics project identifying $1.2M+ in annual revenue leakage and developing data-driven retention strategies.\*\*



---



\## 🎯 Project Overview



Analyzed 7,043 customer records from a telecommunications company to:

\- Predict customer churn with 82% accuracy using machine learning

\- Identify key drivers of customer attrition

\- Develop targeted retention strategies for high-value accounts

\- Quantify revenue impact and ROI of interventions



\*\*Tools Used:\*\* Python | Pandas | Scikit-learn | Seaborn | Matplotlib | Jupyter Notebook



---



\## 📈 Key Findings



\### Business Impact

\- \*\*Churn Rate:\*\* 26.5% (1,869 customers churned)

\- \*\*Annual Revenue at Risk:\*\* $1.2M from churned customers

\- \*\*High-Value Customers:\*\* Top 10% have 37% churn risk

\- \*\*Contract Impact:\*\* Month-to-month customers churn at \*\*10x higher rate\*\* than 2-year contracts



\### Top Churn Drivers

1\. \*\*Contract Type\*\* - Month-to-month contracts show 42.7% churn vs 2.8% for 2-year

2\. \*\*Tenure\*\* - Customers with <12 months tenure at highest risk

3\. \*\*Monthly Charges\*\* - Higher charges correlate with increased churn

4\. \*\*Service Bundling\*\* - Customers without OnlineSecurity/TechSupport show 41% churn

5\. \*\*Payment Method\*\* - Electronic check users have 45% churn rate



---



\## 🤖 Machine Learning Model



\*\*Algorithm:\*\* Random Forest Classifier (100 estimators)

\- \*\*Accuracy:\*\* 82%

\- \*\*Precision:\*\* 80% (churn prediction)

\- \*\*Recall:\*\* 78% (correctly identified at-risk customers)

\- \*\*Features Engineered:\*\* 15+ variables including tenure groups, service bundles, and CLV



Feature importance analysis revealed contract type and tenure as the strongest predictors of churn.



---



\## 💡 Data-Driven Recommendations



\### 1. Contract Optimization Strategy

\- \*\*Finding:\*\* Month-to-month contracts have 39.9% higher churn

\- \*\*Action:\*\* Offer 15% discount for customers upgrading to 1-year+ contracts

\- \*\*Projected Impact:\*\* $450K annual revenue retention



\### 2. Service Bundle Campaign

\- \*\*Finding:\*\* Customers without security services show 41% churn

\- \*\*Action:\*\* Create "Security Bundle" (OnlineSecurity + TechSupport) at $10/month discount

\- \*\*Target:\*\* 3,000 at-risk customers



\### 3. High-Value Account Management

\- \*\*Finding:\*\* Top 10% revenue customers (703 accounts) have 37% churn risk

\- \*\*Action:\*\* Assign dedicated account managers, quarterly business reviews

\- \*\*Protected Revenue:\*\* $380K annually



\### 4. Early Intervention Program

\- \*\*Finding:\*\* 47% of churn occurs within first 12 months

\- \*\*Action:\*\* Implement 30-day, 90-day check-in calls for new customers

\- \*\*Target:\*\* 1,200 new customers/year



---



\## 📁 Project Structure



```

churn-analytics/

│

├── churn\_analysis.ipynb          # Main analysis notebook

├── WA\_Fn-UseC\_-Telco-Customer-Churn.csv  # Dataset (7,043 rows)

├── at\_risk\_customers\_top100.csv  # Export of highest-risk accounts

├── README.md                      # This file

│

└── visualizations/

&nbsp;   ├── churn\_demographics.png

&nbsp;   ├── tenure\_charges\_scatter.png

&nbsp;   ├── feature\_importance.png

&nbsp;   ├── service\_churn\_drivers.png

&nbsp;   ├── high\_value\_churn.png

&nbsp;   └── executive\_dashboard.png

```



---



\## 🚀 How to Run



```bash

\# Clone repository

git clone https://github.com/Ihshana05/churn-analytics.git

cd churn-analytics



\# Install dependencies

pip install pandas numpy matplotlib seaborn scikit-learn



\# Launch Jupyter Notebook

jupyter notebook churn\_analysis.ipynb

```



\*\*Dataset Source:\*\* \[Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)



---



\## 📊 Sample Visualizations



\### Executive Dashboard

!\[Dashboard](visualizations/executive\_dashboard.png)



\### Feature Importance Ranking

!\[Features](visualizations/feature\_importance.png)



\### Tenure vs Monthly Charges (Churn Overlay)

!\[Scatter](visualizations/tenure\_charges\_scatter.png)



---



\## 🎓 Skills Demonstrated



\- \*\*Data Wrangling:\*\* Cleaned 7K+ records, handled missing values, feature engineering

\- \*\*Exploratory Data Analysis:\*\* Identified patterns across 20+ customer attributes

\- \*\*Machine Learning:\*\* Trained Random Forest model with 82% accuracy

\- \*\*Business Analytics:\*\* Translated technical findings into $1.2M revenue impact

\- \*\*Data Visualization:\*\* Created executive dashboards and compelling insights

\- \*\*Statistical Analysis:\*\* Segmentation, correlation analysis, predictive modeling



---



\## 📫 Connect



\*\*Your Name\*\* | \[LinkedIn](https://linkedin.com/in/yourprofile) | \[Portfolio](https://yourportfolio.com)



\*This project showcases end-to-end data analytics capabilities for business decision-making, customer analytics, and predictive modeling—core skills for data analyst roles in consulting.\*



---



\## 📄 License



This project uses publicly available data for educational purposes. Dataset credit: IBM Sample Data Sets via Kaggle.

