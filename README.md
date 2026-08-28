# Titanic Customer Survival Analytics - Business Analyst Case Study

> From Data to Decision: Turning passenger data into customer insights, retention strategy, and a chatbot-ready service.

### 1. Business Problem
A shipping company wants to understand customer survival patterns to improve emergency planning and VIP prioritization. This case is identical to modern Customer Churn & Risk Analysis in Telecom and Banking.

### 2. My Role as Business Analyst
- Performed full EDA and Customer Segmentation (by Class, Gender, Age)
- Defined KPIs: Survival Rate by Segment
- Identified Key Drivers of survival
- Built a prediction model to support real-time Customer Service decisions

### 3. Key Insights & Business Recommendations
- Female + 1st Class + Child = 97% Survival -> Highest Value Segment, prioritize in VIP service.
- Male + 3rd Class = 14% Survival -> Highest Risk Segment, needs proactive support.
- Recommendation: Use same logic for churn prevention. When high-risk customer contacts support, trigger retention offer via Chatbot.

### 4. Solution & Chatbot Integration
- Model: RandomForestClassifier | Accuracy: 81%
- Deliverable: titanic-survival-prediction-model.pkl ready for API integration
- Chatbot Flow: User asks "What is my chance?" -> Bot asks Age, Gender, Class -> Bot predicts + explains with business reason.

### 5. Tech Stack
Python, Pandas, Scikit-Learn, Seaborn, Matplotlib, Business Analysis, Customer Segmentation

### 6. How to Run
pip install -r requirements.txt
jupyter notebook Notebook/Titanic_Survival_Prediction.ipynb

---
Author: Aspiring Business Analyst | Data Analyst | Customer Service Automation
