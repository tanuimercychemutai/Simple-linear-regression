# 📊 Simple Linear Regression: Sales vs Radio Advertising

## Overview
This project applies **simple linear regression** to analyze the relationship between **radio advertising spend** and **sales revenue**. The objective is to determine whether investment in radio promotion is associated with increased sales and to quantify that relationship using a statistical model.

The analysis supports **data-driven marketing decisions** by helping stakeholders understand which advertising channels contribute most effectively to revenue generation.

---

## Problem Statement
Company leadership wants to optimize marketing spend across different channels. Using historical campaign data, this project investigates:

> Does increasing radio advertising spend lead to higher sales? If so, by how much?

---

## Dataset
The dataset contains information about marketing campaigns across multiple channels:
- TV advertising spend
- Radio advertising spend
- Social media advertising spend
- Sales revenue

**Variables used in this analysis:**
- **Independent variable (X):** Radio advertising spend  
- **Dependent variable (Y):** Sales revenue  

---

## Methodology
1. Load and inspect the dataset  
2. Check for missing values  
3. Visualize the relationship between radio spend and sales  
4. Fit a simple linear regression model using Ordinary Least Squares (OLS)  
5. Interpret model parameters:
   - Slope
   - Intercept
   - R² (coefficient of determination)
6. Analyze residuals to assess model fit  

---

## Key Concepts
- Simple Linear Regression  
- Ordinary Least Squares (OLS)  
- Fitted values  
- Residuals  
- Slope and intercept  
- Coefficient of determination (R²)  

---

## Tools & Libraries
- Python  
- pandas  
- seaborn / matplotlib  
- statsmodels or scikit-learn  

---

## Results (Summary)
- The regression line represents the **expected sales value** for a given level of radio advertising spend.
- The **slope** indicates how much sales are expected to change for each additional unit of radio spend.
- **R²** measures how much of the variation in sales is explained by radio advertising.

---

## Business Implications
- Helps evaluate the effectiveness of radio advertising.
- Supports evidence-based marketing budget allocation.
- Serves as a baseline for extending the analysis to multiple advertising channels.

---

## How to Run
1. Clone this repository  
2. Install the required dependencies  
3. Run the notebook or script sequentially to reproduce the analysis  

---

## Next Steps
- Extend the model to **multiple linear regression** using TV and social media spend  
- Compare channel effectiveness  
- Perform deeper diagnostic checks on model assumptions  

