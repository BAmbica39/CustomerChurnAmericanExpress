Customer Churn Prediction using ANN (American Express)
This project involves predicting customer churn using an Artificial Neural Network (ANN) model built with TensorFlow and Keras. The dataset contains anonymized records from American Express customers, and the model predicts whether a customer is likely to leave the company.

Problem Statement
Customer churn significantly affects the profitability of companies like American Express. Predicting churn allows the business to proactively retain at-risk customers through personalized interventions.

Dataset
The dataset is a structured Excel file containing features such as:
- Customer ID
- Location (city)
- Gender
- Age
- Credit score
- Spending pattern
- Credit balance and more...

Target variable: `Churn` (0 = Stay, 1 = Leave)

Data Preprocessing
- Encoded `Gender` using Label Encoding
- Applied One-Hot Encoding to the `City` column
- Scaled numerical features using `StandardScaler`
- Split data into training and testing sets (80:20)

Model Architecture
Implemented using TensorFlow/Keras:
- Input layer: 11 features
- Hidden Layers: 2 Dense layers with ReLU activation
- Output Layer: 1 neuron with Sigmoid activation (for binary classification)

