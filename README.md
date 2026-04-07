# Ecommerce-returns-analysis
End‑to‑end analysis of e‑commerce orders: from EDA and segmentation to predictive modeling of product returns.

# Project Summary
This project analyzes an e commerce dataset containing customer, order, and delivery information to understand what drives product returns and whether they can be predicted using machine learning.
The workflow includes data cleaning, exploratory analysis, segment insights, behavioral correlations, and predictive modeling.

## 1. Exploratory Data Analysis (EDA)
An initial overview examined customer demographics, product categories, payment methods, delivery times, and ratings. 
Main findings:
•	The highest purchase volumes came from Fashion, Beauty, and Groceries categories. 
•	Female customers were more active in Beauty, Home & Living, and Groceries, while male customers dominated Sports and Electronics. 
•	Return rates changed notably across categories and genders, confirming that product type and customer segment strongly influence returns.
## 2. Segment Level Analysis
Heatmaps comparing orders, returns, and return percentages by category and gender highlighted patterns of customer behavior.
Returns were most frequent in lifestyle related categories (Beauty, Groceries, Home & Living), while Electronics showed the lowest return percentage.
## 3. Behavioral Insights
Further analysis explored logistics and satisfaction variables:
- **Delivery Time vs Returns:** Returned orders had slightly longer delivery times (7.5 vs 7.4 days).  
  → Delivery speed may have a mild but not decisive effect.  
- **Customer Rating vs Returns:** Ratings remain almost identical or slightly higher for returned items.  
  → Ratings likely reflect the shopping experience rather than the return itself.  
- **Order Value vs Returns:** No meaningful difference between returned and non‑returned orders.  
  → Price alone does not explain returns.  
- **Payment Method vs Returns:** UPI and Cash on Delivery show the highest return rates.  
  → Easier payment types may encourage impulsive purchases.  
## 4. Predictive Modeling
A Random Forest Classifier was trained to predict whether an order would be returned (1) or not (0). 
Model results
•	Accuracy ≈ 51% → slightly better than random guessing; the dataset lacks strong predictive signals. 
•	Recall (1) = 0.62 → the model successfully identifies many actual returns, though with false positives. 
•	Feature importance shows the top drivers: Order value, Customer rating, Customer age, and Delivery time.
Demographic and categorical features (gender, payment, product category) have limited impact.
## 5. Conclusions
•	Customer returns are not easily predictable from the available features — behavioral and logistical aspects matter more than demographics. 
•	High return rates concentrate in everyday lifestyle categories and under certain payment methods (UPI, COD). 
•	The project demonstrates the complete data science workflow — from cleaning and visualization to modeling and interpretation — producing actionable insights despite limited predictability.
<img width="482" height="707" alt="image" src="https://github.com/user-attachments/assets/f5a98279-18be-4598-8584-8ab6dfb27d83" />
