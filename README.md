# Elevate-Labs-Final-Project
# HR Analytics - Predict Employee Attrition

## Project Description

Employee attrition is a critical issue for many organizations. This project aims to analyze HR data to identify the main factors influencing employee resignation and build a predictive model to estimate future attrition risks. Interactive visualizations are created using Power BI to uncover key insights.

## Tools and Technologies Used

* **Python:** Pandas, Seaborn, Scikit-Learn, Matplotlib
* **Power BI:** For interactive dashboard visualization
* **Machine Learning Model:** RandomForest Classifier

## Dashboard Insights

* High attrition observed in **Sales Executives** and **Laboratory Technicians**.
* Employees aged **26–35** are at the highest risk of resignation.
* Attrition rates are significant in **Life Sciences** and **Medical** backgrounds.
* Majority of resignations are from the **lower salary band** (Up to 5k).

## Model Performance

* Model Accuracy: **86%**
* High precision for 'No' attrition cases but room for improvement for 'Yes' predictions.

## Future Improvements

* Address class imbalance to improve recall for attrition predictions.
* Integrate SHAP values for better model explainability.
* Expand feature engineering to include employee engagement metrics.
