## Which steps of the plan were carried out and which steps were omitted (explain why)?

Within the work plan applied to the project, the following steps were developed:

- Identification and handling of null, duplicate, and missing data.
- Graphing and developing conclusions about the data
- Handling of outliers and recorded outliers
- Searching for correlations between all client data
- Definition of categorical and numerical characteristics
- Construction and separation for training and test data of the model
- Establish a target to predict
- Establish measurement metrics to determine the business goal (AUC-ROC, F1, Accuracy, etc.)
- Analyze the comparison of metrics.
- Adjust the hyperparameters of each model in question.
- Interpretation of the results: which variables contribute the most to the model? In order to choose the model in its final version, and better fit the business goal.

New steps were also added during the process:

- Formatting Columns to the correct types
- Correlation Matrix
- Detailing of binary columns
- Analysis of enrollments per month
- Adding LightGBM model

## What difficulties did I encounter and how did I manage to solve them?

The difficulties I encountered were:

- In the data filtering, at first I did not manage to assign a good value for the EndDate column, as I did not know if you wanted to keep the date when the customers unsubscribed the service. And it was not until later that I understood that we needed the column as a binary variable, which helped to clarify the analysis later.
- Another difficulty I encountered was that of not achieving the 88% required to obtain a high score in the LinearRegression model, I investigated what other alternatives I could achieve, and I managed to decipher that perhaps I needed to rely on a Gradient Boosting model such as LightGBM.

## What were some of the key steps in solving the task?

I think some of the key steps to solve the task were:

- Recognize well my feature variables and my target variable.
- Standardize the prices to lower numbers to increase the efficiency of the model
- Identifying the types of my columns and realizing that they could all be numerical, which increased the efficiency of the model
- Change Machine Learning model to achieve higher scores on the needed metrics

## What is your final model and what is its quality level?

My final model is LightGBM, and its quality level is 0.92% in the AUC-ROC score for customer churn predictability.
