### Consignment Pricing Prediction Model

#### Overview:
This project focuses on developing a predictive model to forecast consignment pricing using available dataset variables. By leveraging machine learning techniques, the aim is to empower logistics stakeholders to optimize supply chain processes and enhance operational efficiency through informed decision-making.

#### Model Selection:
After evaluating various regression models including Linear Regression, Decision Tree, Pruned Decision Tree, Random Forest, Adaboost, Gradient Boost, and XGBoost, the Random Forest model emerges as the most suitable choice for this particular dataset. It demonstrates robust performance on both training and testing sets, exhibiting relatively low errors (MSE, RMSE, MAE) and high R-squared values. The Random Forest model strikes a balance between complexity and generalization ability, making it less prone to overfitting compared to some other models.

#### Top 3 Factors from a Business Perspective:
1. **Line Item Quantity_log:** Strong positive correlation (0.873926) with the target variable, indicating significant impact of quantity on consignment value.
2. **Line Item Insurance (USD)_log:** Strong positive correlation (0.956732) with the target variable, highlighting influence of insurance cost on consignment value.
3. **Freight Cost (USD)_robust_log:** Moderate positive correlation (0.460239) with the target variable, suggesting notable role of freight cost in consignment value determination.

#### Conclusion:
The Random Forest model provides reliable and consistent predictive performance, making it the recommended choice for this regression task. By considering the identified key factors, stakeholders can better understand and optimize consignment pricing strategies, leading to improved supply chain efficiency and cost-effectiveness.
