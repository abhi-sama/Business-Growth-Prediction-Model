# Business Growth Prediction Model Readme

## Overview

This project aims to help an e-commerce company based in New York City make an informed decision about where to focus its efforts for business growth. The company offers both a mobile app and a website for customers to purchase clothing online. In addition to online sales, the company also provides in-store style and clothing advice sessions. The objective is to determine whether the company should prioritize improving the mobile app experience or the website to maximize profitability.

## Dataset

The dataset used for this analysis contains information about customers, including their spending habits and interactions with the company's platforms. The key variables in the dataset are as follows:

- Dependent Variable: 'Yearly Amount Spent' - This represents the total amount spent by each customer in a year.
- Independent Variables: The rest of the variables in the dataset, such as 'Time on App,' 'Time on Website,' 'Length of Membership,' and 'Avg. Session Length.'

## Methodology

To make this decision, we used a Linear Regression model. The dataset was divided into a training set (70%) and a test set (30%). The training data was used to train the model, while the test data was used to evaluate its performance.

The accuracy of the model:
- Training Subset Accuracy: 98.2%
- Test Subset Accuracy: 98.9%

## Results

The results of the Linear Regression model suggest that the 'Time on App' variable has a stronger positive correlation with 'Yearly Amount Spent' compared to other variables. In other words, customers who spend more time on the mobile app tend to spend more money with the company. Therefore, the prediction from the model indicates that the company should invest more in improving the mobile app experience to drive higher profits.

## Conclusion

Based on the analysis and prediction of the Linear Regression model, it is recommended that the company should focus its efforts and resources on enhancing the mobile app. This should involve improvements in user experience, features, and marketing efforts aimed at encouraging more customers to use the app. By doing so, the company can potentially increase its yearly revenue and overall profitability.

This recommendation is subject to further market analysis and business strategy considerations. The company should also continue to monitor customer preferences and adapt its strategies accordingly to ensure sustained growth and success.
