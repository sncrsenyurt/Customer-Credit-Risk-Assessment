# Credit Status Prediction using Machine Learning

## Overview
This project involves building a machine learning model to predict the credit status of customers based on various features. The model is trained on historical data, and once trained, it can be used to predict whether a new customer's credit status is risky or non-risky.

## Dataset Privacy
Please note that due to privacy reasons, the actual CSV data files (`application_record.csv` and `credit_record.csv`) used in this project cannot be shared.

## Model Comparison
During the development of this project, two different machine learning algorithms were experimented with to predict credit status.

### 1. Random Forest Classifier
The initial model was trained using the Random Forest Classifier, achieving an accuracy of approximately 85%.

### 2. XGBoost Classifier
A second attempt was made using the XGBoost Classifier, resulting in an accuracy of around 83%.

After comparing the performance of the two models, it was decided to continue with the Random Forest Classifier due to its higher accuracy.

## Code Structure
The code is divided into several sections:

### 1. Data Preparation
- Import necessary libraries.
- Load the dataset files (`application_record.csv` and `credit_record.csv`).
- Merge the datasets based on the 'ID' column.

### 2. Data Preprocessing
- Define a function to classify credit status as 'Risky' or 'Non-Risky'.
- Apply the classification function to create a new column 'CREDIT_STATUS'.

### 3. Feature Selection
- Select relevant features for training the model.

### 4. Data Encoding
- Use Label Encoding to convert categorical features into numerical format.

### 5. Train-Test Split
- Split the data into training and testing sets.

### 6. Model Training
- Use a Random Forest Classifier for training the model.

### 7. Model Evaluation
- Evaluate the model's accuracy, confusion matrix, and classification report on the test set.

### 8. Prediction for New Customers
- Create a sample new customer data.
- Use the trained model to predict the credit status of the new customer.

## How to Use
1. Ensure that the required libraries are installed (pandas, scikit-learn).
2. Download the dataset files (`application_record.csv` and `credit_record.csv`).
3. Run the provided code in a Python environment.
4. Follow the instructions in the comments for each section of the code.

## Results
The model achieves a certain level of accuracy in predicting credit status based on the provided features. The evaluation metrics, including accuracy, confusion matrix, and classification report, provide insights into the model's performance.

## Prediction for New Customers
The model can be used to predict the credit status of new customers. Provide the required information in the 'new_customer_data' section, run the code, and check the predicted credit status.

Feel free to customize the code or experiment with different machine learning models for potentially improved results.
![testcustomer](https://github.com/sncrsenyurt/Customer-Credit-Risk-Assessment/assets/35157651/2f9d56ad-e1dd-40b3-914f-e70310b1790c)



