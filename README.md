# Brazilian Retail Logistics & Marketplace Fulfillment Analysis


### AICTE - BharatCares Analytics with AI Internship Program
- **Student Researcher:** Kunal Saini
- **Submission Date:** October 2026


---


## 1. Project Overview & Scope
This project analyzes operational order records, customer satisfaction distributions, and regional shipping lead times using the Brazilian E-Commerce public dataset (Olist). Through descriptive analytics and machine learning modeling via Gradient Boosting, the project examines key fulfillment bottlenecks and delivers an interactive monitoring application.


---


## 2. Dataset Attribution
- **Dataset Source:** [Kaggle - Brazilian E-Commerce Public Dataset by Olist]( https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce )
- **Primary Attributes:** Customer_State, Product_Category, Payment_Type, Order_Price, Freight_Value, Delivery_Days, Review_Score


---


## 3. Core Findings
- **Geographic Lead Time Disparities:** Delivery timelines to northern and northeastern states average nearly double the transit times of shipments within the southern economic corridors.
- **Freight Cost Sensitivity:** Orders with disproportionately high freight charges relative to the order price correlate with lower review scores, regardless of arrival speed.
- **Predictive Regression:** The Gradient Boosting model effectively captures transit time variances using freight fees, merchandise value, and destination geographic parameters.


---


## 4. Technology Stack
- **Programming Language:** Python 3.9+
- **Data Manipulation:** Pandas, NumPy
- **Visual Diagnostics:** Matplotlib, Seaborn
- **User Interface:** Streamlit
- **Machine Learning Engine:** Scikit-Learn (Gradient Boosting Regressor)


---


## 5. Execution Steps
1. Install project dependencies:
   pip install -r requirements.txt


2. Run the analytics dashboard:
   streamlit run KunalSaini_Ecommerce_Analytics.py