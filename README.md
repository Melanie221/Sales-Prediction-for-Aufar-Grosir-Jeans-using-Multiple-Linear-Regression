# Sales-Prediction-for-Aufar-Grosir-Jeans-using-Multiple-Linear-Regression
This project predicts sales at Aufar Grosir Jeans on Shopee using a multiple linear regression model. By analyzing key factors such as sold products and shipping discount incentives, we developed an accurate sales forecast model. The methodology follows the SEMMA process—sampling, exploring, modifying, modeling, and assessing data—to ensure robust predictions and actionable insights.

## Dataset used
-  <a href="https://github.com/Melanie221/Sales-Prediction-for-Aufar-Grosir-Jeans-using-Multiple-Linear-Regression/blob/main/sample%20504.xlsx">Dataset</a>

## Project Objectives
- Develop a predictive sales model using multiple linear regression.
- Identify the impact of sold products and shipping discounts on total sales.
- Provide data-driven recommendations for inventory and marketing strategies.

## Key Questions & KPIs for Analysis
- Total Sales Volume – How many products were sold?
- Impact of Discounts – How do shipping discounts influence sales?
- Revenue Forecasting – What is the projected sales revenue for upcoming months?
- Model Accuracy – How well does the regression model predict sales performance?

## Tools Used
- Python – Data cleaning, preprocessing, and exploratory data analysis (EDA).
- SPSS – Performing multiple linear regression analysis and statistical tests.

 ## Analysis Process
- Data Collection – Gathered sales data from Shopee (May–September 2024).
- Data Cleaning (Python) – Handled missing values, removed duplicates, and formatted variables.
- Exploratory Data Analysis (Python) – Identified key trends and correlations between sales, discounts, and other variables.
- Assumption Tests (SPSS) – Performed statistical tests to ensure data suitability for regression analysis:
 1. Normality Test – Ensured that residuals were normally distributed. 
    ![image](https://github.com/user-attachments/assets/b2617d64-b3a9-4fd6-95c2-b7e9e6d4f932)
    the significance value is 0.18> 0.05, it can be concluded that the residual data is normally distributed.
 3. Multicollinearity Test – Verified that independent variables were not highly correlated (VIF < 10).
    ![image](https://github.com/user-attachments/assets/ff20f783-f3f1-4ee6-93ce-fa1556ad9705)
    The Tolerance value is 0.759 and the VIF value is 1.318, so the conclusion is that there is no multicollinearity. So that the data on products sold and discounted shipping costs are good to use in the regression model. 
 5. Heteroscedasticity Test – Checked for variance consistency in residuals.
    ![image](https://github.com/user-attachments/assets/47775c2c-db8c-484f-9458-20b9e2a028f1)
    The graph does not indicate heteroscedasticity, as the dots are scattered randomly without any particular pattern. However, this interpretation needs to be supported with additional statistical tests such as the Glejser test to confirm the results.
    ![image](https://github.com/user-attachments/assets/fe362b3b-0547-45b9-b1dd-d772aa9272ca)
    Judging from the results of the Glejser test conducted that the significance value of the product sold is 0.156 and the discounted shipping cost (shipping) is 0.167 shows a significance value greater than α, so the conclusion is that there is no heteroscedasticity. 

 7. Autocorrelation Test (Durbin-Watson) – Ensured no correlation in residual errors.
- Regression Modeling (SPSS) – Conducted multiple linear regression to analyze the impact of independent variables on total sales.
- Model Evaluation (SPSS)
  1. F-Test – Showed that the independent variables significantly influenced sales (F = 2832.640, p < 0.05).
  2. T-Test – Confirmed that each independent variable had a significant impact on total sales (p < 0.05).
  3. R² Value – 91.9%, indicating that the model explains most of the variance in sales.
  4. MAPE (Mean Absolute Percentage Error) – 8.99%, proving the model’s high accuracy.
- Insights & Reporting – Interpreted results and provided strategic recommendations.

## Project Insights & Conclusion
- Sales volume is significantly influenced by the number of sold products, while shipping discounts have a smaller but positive effect.
- The regression model achieved high accuracy (MAPE = 8.99%), making it reliable for sales forecasting.
- Business strategies should focus on increasing product sales volume and optimizing discount incentives to boost revenue​
