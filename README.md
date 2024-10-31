# HotelBookingCancellationPredictionModel
## Project Overview
### Executive Summary: 
The EDA reveals insights into a collection of data aimed at predicting hotel booking cancellations. It provides some meaningful insights into the dataset's characteristics, including class imbalances, seasonal booking patterns, and factors influencing cancellation status. By leveraging these findings, stakeholders can develop informed strategies to optimize revenue and mitigate hotel booking cancellations effectively.

**Author**: Ellyn Ngo

**Date**: February 2024 - June 2024

**Goal**: This EDA aims to provide valuable insights into factors influencing hotel booking cancellations. This includes understanding customer behavior, preferences, and potential reasons for cancellations, which can inform business decisions and strategies to mitigate cancellations.

### Dataset Description:
The dataset comprises 119,390 entries and encompasses 36 attributes. The target variable is is_canceled, representing the class labels for the classification task, which indicates whether a booking was canceled (coded as 1) or not (coded as 0). The features include various aspects such as hotel categorizations, lead time (number of days before arrival), and weekday booking counts, among others, which will be thoroughly investigated. Of these features, 16 are categorized as objects, 16 as integers, and 4 as floating-point numbers.

## Process
1. Data Preprocessing: Address missing values through imputation or deletion.
2. Exploratory Data Analysis (EDA)
3. Feature Engineering:
Explore potential interactions and transformations of features to enhance predictive power.
Select relevant features based on domain knowledge and statistical significance.
4. Modeling Strategy:
Using Decision Tree and Random Forests for the predictive algorithms, then using Receiver Operator Characteristic (ROC) curves and the Area Under the Curve (AUC) to check the model accuracy.
Implement cross-validation techniques to assess model performance and mitigate overfitting.
Evaluate model interpretability and scalability for deployment in production environments.
