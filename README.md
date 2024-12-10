# **UK Used Car Pricing Analysis and Predictive Model Building**

**By:**
- Muhammad Sultan Pasya
- Muhammad Fareza Duta Pradana

## **Project Overview**

This project analyzes the UK used car market with the goal of understanding the factors that influence used car prices. By leveraging regression modeling techniques, we aim to predict resale prices based on various car attributes like mileage, age, fuel type, engine size, and more. This model can assist dealerships in setting competitive pricing strategies to optimize inventory turnover, avoid underpricing, and increase profitability.

---

## **Context**

The used car market is a crucial component of the automotive industry, offering affordable alternatives for buyers and significant opportunities for sellers. The challenge lies in determining an optimal pricing strategy that balances competitiveness with profitability. This project uses real-world data to understand the depreciation trends of used cars, which lose substantial value over time. Factors such as mileage, car condition, and model influence the pricing decisions, and by accurately predicting these factors, sellers can avoid common pricing pitfalls.

---

## **Problem Statement**

The central question this project seeks to address is:  
**How can we predict the resale value of used cars and identify key factors that influence their marketability to improve pricing strategies and attract more buyers?**

---

## **Goals**

1. **Market Analysis:** To identify key car attributes that correlate with higher resale prices.
2. **Predictive Modeling:** To build a model that estimates the resale value of used cars based on their attributes.
3. **Actionable Recommendations:** To help dealerships optimize pricing strategies and inventory management for higher profitability.

---

## **Approach**

We use a **regression-based approach** to predict used car prices. The main steps are as follows:

1. **Data Exploration and Cleaning:** Preprocess the dataset, handling missing values and anomalies.
2. **Exploratory Data Analysis (EDA):** Investigate the relationships between various car features and their impact on pricing.
3. **Model Building:** Apply regression models to predict the car prices based on features such as mileage, age, fuel type, and engine size.
4. **Model Evaluation:** Use metrics like RMSE, MAE, and MAPE to assess model performance.
5. **Insights and Recommendations:** Provide recommendations based on model results to optimize pricing strategies.

---

## **Model Evaluation**

### **Key Metrics Used:**
- **Root Mean Squared Error (RMSE):** Measures the square root of the mean of squared differences between predicted and actual values.
- **Mean Absolute Error (MAE):** The average of the absolute differences between predicted and actual values.
- **Mean Absolute Percentage Error (MAPE):** Percentage-based error measurement for predictions.

### **Model Performance:**
The model achieved an **RMSE** of £4,157.48, **MAE** of £2,693.93, and **MAPE** of 16.6%, indicating a "good forecast."

### **Limitations:**
- **Limited Features:** Missing factors like vehicle condition and ownership history that may impact pricing.
- **External Factors:** The model doesn’t account for economic or seasonal changes in the market.
- **Static Data:** Based on a snapshot of the market; may not capture real-time fluctuations.

---

## **Conclusion and Recommendations**

### **Key Insights:**
1. **Mileage and Age:** Cars with lower mileage and younger age have higher resale value.
2. **Fuel Type and Transmission:** Hybrid and electric cars, as well as automatic transmissions, hold higher resale values.
3. **Depreciation Trends:** Cars lose significant value within the first 3 years, with depreciation slowing as the vehicle ages.

### **Recommendations for Dealerships:**
1. **Optimize Listings:** Highlight low-mileage, hybrid, and premium brand vehicles.
2. **Feature High-Demand Cars:** Focus on automatic transmission and hybrid models.
3. **Offer Trade-in Programs:** To combat rapid depreciation and attract customers.
4. **Promote Eco-Friendly Cars:** Leverage the growing demand for hybrid and electric vehicles.

### **Future Work:**
- **Incorporating Additional Data:** Expand the dataset by including features such as vehicle condition, insurance costs, and ownership history, which could significantly enhance the model's predictive accuracy.  
- **Real-time Model Updates:** Implement a system to periodically update the model using recent market data, ensuring it remains accurate and relevant as market conditions evolve.  
- **Enhanced Feature Set:** Introduce additional factors like accident history and detailed vehicle condition reports to capture nuances in pricing and further improve model performance.  
- **Leveraging GridSearchCV:** Utilize GridSearchCV for hyperparameter optimization to systematically explore combinations of parameters and get the best result.

---

## **Datasets**
The following datasets were used in this project:  

- **Primary Datasets**:  
  - `UK Used Car_cleaned.csv`  
  - `UK Used Car.csv`  

- **Brand-Specific Datasets**:  
  - `audi.csv`  
  - `bmw.csv`  
  - `cclass.csv`  
  - `focus.csv`  
  - `ford.csv`  
  - `hyundi.csv`  
  - `merc.csv`  
  - `skoda.csv`  
  - `toyota.csv`  
  - `vauxhall.csv`  
  - `vw.csv`  

---

## **Miscellaneous**

### **Deployment Assets**
- **Model**: `model_xgb_regressor_for_uk_used_car.sav`  
- **Encoder**: `encoder.pkl` 

### **Interactive Dashboard**
An interactive dashboard for exploring the dataset and predictions is available. Accessible via [this link](https://public.tableau.com/app/profile/sultan.pasya/viz/UKUsedCarDashboard/Home).
