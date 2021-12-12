# EDA-Telco-Customer-Churn
Exploratory Data Analysis Project
In this section, i would like to share one of my latest project regarding Exploratory Data Analysis 
using Telco Customer Churn Data from <a href="https://www.kaggle.com/blastchar/telco-customer-churn">Kaggle</a>.<br />
In this project I would like to know :<br />
1. Percentage of the Churn Customer vs No Churn Customer.<br />
2. Outlier or anomaly of the data.<br />
3. Variable that could be used as predictor.

# The Result
1. Percentage of Churn vs no Churn Customer = 26.54% : 73.46%.<br />
Note : I replaced the missing value on variable TotalCharges with 0 due to each customer has 0 tenure.<br />
![Percentage](https://github.com/lailaprakasita/EDA-Telco-Customer-Churn/blob/main/percentage.png)<br />
2. No data outlier nor anomaly in numerical Telco Customer Churn Data.<br />
![Outlier Check](https://github.com/lailaprakasita/EDA-Telco-Customer-Churn/blob/main/outlier_check.png)<br />
3. InternetService and MonthlyCharges are good candidates of predictors refer to Pearson Correlation Heatmap. <br />
They have a very high correlation (0.91) which means we have to choose which one of them will be used as predictor.<br />
![Pearson Correaltion Heatmap](https://github.com/lailaprakasita/EDA-Telco-Customer-Churn/blob/main/pearson_correlation_heatmap.png).<br />
Disclaimer : This is my simply analysist, feel free to correct me <br />
Thank you ^^.
