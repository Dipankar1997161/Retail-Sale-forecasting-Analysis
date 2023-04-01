# Store_sales_prediction

Sales forecasting is a crucial business exercise. Accurate sales forecasts allow business leaders to make smarter decisions about things like goal-setting, budgeting, hiring, and other things that affect cash flow. Sales forecasts are usually based on historical data, industry trends, and the status of the current sales pipeline. Businesses use the sales forecast to estimate weekly, monthly, quarterly, and annual sales totals.
<p align="center">
    <img alt="SalesPredict" title="Sales Prediction" src="https://www.entrepreneurshipinabox.com/wp-content/uploads/sales-forecast-template-for-your-business.jpg" width="600" height="400">
</p>

In this project, the prediction of sales is done using forecasting procedure fbprophet developed by Facebook's core Data Science team. Prophet forecasts time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

## Project Files: 
"Sales Forecast" folder consists of my older and basic sales forecasting using FbProphet (2 Weeks Back). I did that to learn more on FbProphet and Forecasting problems.
The remaining files are the new and detailed Sales Forecasting on another dataset with proper EDA and Sales Forecasting

## Results

**few EDA**

![new count](https://user-images.githubusercontent.com/85514219/229319693-9d5cc847-b1c4-49c2-a649-66b7e23c88e4.png)
![count](https://user-images.githubusercontent.com/85514219/229319694-dabf04d0-0c6e-426f-93e0-466e46a658a9.png)


**Normal Forecasting:**

![store_10_forecast](https://user-images.githubusercontent.com/85514219/229319380-3e446f3d-e896-429b-9266-f7fac8a6629d.png)
![store_10_components](https://user-images.githubusercontent.com/85514219/229319379-55cff2cc-55d4-4a01-a2a1-b725b2eb291d.png)

**Holiday-Based Forecasting:**

![store_6_forecast_holiday](https://user-images.githubusercontent.com/85514219/229319437-9ca01249-5942-4453-8d1c-762cfa683a67.png)
![store_6_components_holiday](https://user-images.githubusercontent.com/85514219/229319434-d9527c71-c77d-49b3-bf40-4c5bb06a9320.png)


## Conclusion
Forecasting is indeed one of the major business necessity. Although, these models might not give you an accurate results, but it can provide an estimate which can help business /sales
