# Churn-Prediction-and-Analysis
Project Scope: 
<br/> Customers and employees are always the two big essential factors for a company to be operated and profitable. This project focus on the employee side and forcasts which current employee is more likely to leave in the near future. It can help labor management and strategic plans. 

Data Source:
<br/> The dataset we used in this entire project was obtained from Kaggle website and it was published by IBM data scientists (see Kaggle web link here). In this dataset, there are 1470 employee records and 35 employee features, such as age, daily rate, distance from home, education level, etc. These 35 employee features include both numerical and categorical variables. The  Attrition feature is the target of prediction. There are 2 classes in the target feature, which are “Yes” and “No”. If an attrition is yes, that means the employee  is  a churn. “No” means that the employee prefers to stay in the company.

Exploratory analysis provides following insights:
- How is our data distributed?
- How many employee left or how many stayed in the dataset?
- Would people leave because too long with no promotion?
- People in which department are most likely to leave?
- Is there a geneder discrimination?
- Did people leave because they live far away?
- How many numerical variables correlated with each other?¶

Machine Learning Models:
1. Linear Regression
2. Polynomial regression
3. Decision tree
4. Random Forest
5. Model Ensemble

Model Evaluation:
<br/> ![alt text](https://github.com/cyl7621/Churn-Prediction-and-Analysis/blob/main/Model_Evaluation_Results.PNG)

Logistics regression model beats all other models which have the highest accuracy of 88.43% and it is the less overfitted model which the f1 score is 0.55. Most importantly, it has the least false negative which is only 2.52%. The rest of the model has false negatives all over 12%. In this project, we care about false negatives heavily and weight less on the false positive error. This is because false negatives predict someone who would leave the company as they would stay. Therefore, this error can make the company think they have enough employees to work, but in fact, they did not. Without enough labor, the company cannot operate normally and cannot produce services and products to customers. 
