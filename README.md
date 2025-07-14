# BCG-Churn-Analysis-and-Prediction

This project was completed as a part of Boston Consultancy Group (BCG) Data Science Job Simulation. Task for this project was to assist client PowerCo in churn analysis and modeling and analyze whether Price Senstivity is a major contributing factor for Customer Churn. Price Senstivity is defined as Change in Demand/Change in Price for this project. 

Throughout the project we followed BCGX guidance and completed steps as a Data Scientist would during the job at BCG. Besides that, we have performed our own additional EDA and Churn Modeling, with our best model better than BCGX Model Answer by several times, five time better in F1 Score and 10
times better in recall performance as BCGX used a simple Random Forest while we used Gradient
Boosting algorithm with hyper parameter tuning, Dense Neueral Network, and a BiDirectional
LSTM-CNN models. Among them XGBoost model performed best and this corresponds to the
industry norm where gradient boosting and other boosting algorithms worked better in structured
tabular dataset, provided that we have limited data.

For the Price Senstivity we found that customers were quite price flexible and some sales channel and promotional campaigns were the cause of higher than average churn rate for PowerCo as some subgroups witnessed higher churn rate than average.

XG Boost model got highest ROC score at 68% and 50% recall with BiLSTM-CNN model coming second even if it had highest F1 Score at 0.28 but with recall as low as 20%. Overall, we got five times better result in our model compared to the Model Answer from BCGX for this project.
