# Airbnb Price Prediction & Customer Churn Prediction

Project Overview

This repository contains two **Machine Learning Projects**:  
**Airbnb Price Prediction** — A regression project predicting the price of Airbnb listings based on features like property type, room type, location, amenities, and host details.  
**Customer Churn Prediction** — A classification project predicting whether a customer will churn based on demographic, account, and service-related data.

---

##Project Structure

```
Airbnb-and-Customer-Churn-ML-Project/
├── Airbnb/
│   ├── Airbnb.ipynb                # Jupyter Notebook for Airbnb Analysis & Model
│   ├── Airbnb.pdf                    # PDF Report for Airbnb Analysis
│   ├── Airbnb_data.csv               # Dataset for Airbnb
├── CustomerChurn/
│   ├── Customer Churn Prediction.ipynb  # Jupyter Notebook for Churn Analysis
│   ├── Customer Churn Prediction.pdf    # PDF Report for Churn Analysis
│   ├── customer_data.csv                 # Dataset for Churn Prediction
├── README.md
```

---

## Project 1: Airbnb Price Prediction
### Goal  
Build a **regression model** to predict the price of Airbnb listings and provide insights to hosts for better pricing strategies.

### Methods Applied  
- Data Cleaning & Preprocessing
- Feature Engineering (e.g., neighborhood popularity score, amenities count)
- Regression Models: Linear Regression, Random Forest, XGBoost
- Evaluation Metrics: RMSE, MAE, R²
- Visualization using Matplotlib & Seaborn

### Key Insights  
- Amenities, room type, and location heavily influence price.
- XGBoost performed the best with **R² = 0.56**.
- Popular neighborhoods command higher prices.

---

##Project 2: Customer Churn Prediction
### Goal  
Build a **classification model** to predict whether a telecom customer will churn based on their account, service, and demographic data.

### Methods Applied  
- Data Cleaning & Preprocessing
- Feature Engineering & Encoding
- Classification Model: Random Forest (with GridSearch Tuning)
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score
- Visualization using Seaborn & Matplotlib

### Key Insights  
- High monthly charges and low tenure are strong churn indicators.
- Fiber optic users churn more than DSL users.
- Customers paying via **Electronic Check** have higher churn rates.

---

##Model Performance Summary

| Project | Model | Key Metric | Score |
|---|---|---|---|
| Airbnb Price Prediction | XGBoost | R² | 0.56 |
| Customer Churn Prediction | Tuned Random Forest | F1-Score | 0.58 |

---

## Libraries & Tools
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn, XGBoost
- Jupyter Notebook


## Recommendations (Key Takeaways for Businesses)

### For Airbnb Hosts
- Focus on **amenities, location, and host responsiveness** to increase price.
- Improve reviews to enhance neighborhood reputation.

### For Telecom Companies
- Target customers with high monthly charges and low tenure for loyalty offers.
- Encourage automatic payments to reduce churn risk.
- Focus retention campaigns on fiber optic users who are more likely to churn.
