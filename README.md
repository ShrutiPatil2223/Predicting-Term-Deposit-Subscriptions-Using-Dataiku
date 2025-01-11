# Predicting Term Deposit Subscriptions Using Dataiku

## Project Overview
This project involves building a predictive model to determine whether a client will subscribe to a term deposit based on a Portuguese bank's telemarketing data. Using **Dataiku**, we developed a data pipeline and applied machine learning techniques to achieve high predictive performance.

## Key Features
1. **Dataset**: 
   - 45,211 records with 17 features (10 categorical, 7 numerical).
   - Target variable: `y` (binary - subscription status: "yes" or "no").

2. **Data Preprocessing**:
   - Handled missing values and duplicates.
   - Converted categorical data to numerical using **Label Encoding**.
   - Applied **Standard Scaling** for numerical features.
   - Addressed class imbalance using a **60:40 oversampling and undersampling technique**.

3. **Machine Learning Models**:
   - Implemented **Random Forest**, **Decision Tree**, and **Logistic Regression**.
   - **Random Forest** achieved the best results with:
     - **Recall**: 81.8%
     - **ROC-AUC**: 88.4%

4. **Hyperparameter Optimization**:
   - Used **Grid Search** for optimizing parameters such as the number of trees, depth, and sample leaf size.

## Tools and Technologies
- **Dataiku**: For collaborative workflow development and model deployment.
- **Python**: For data preprocessing and custom scripting.
- **Machine Learning**: Random Forest, Decision Tree, Logistic Regression.

## Challenges
- **SMOTE Technique**: Attempted implementation in Dataiku but faced library installation issues.
- **Cost Sensitivity**: Focused on minimizing the cost of missing potential subscribers while balancing false positives.

## Results
- The **Random Forest model** performed the best in predicting term deposit subscriptions based on recall and ROC-AUC metrics.
- The workflow can be extended for real-time deployment to assist in customer targeting.

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<YourUsername>/<YourRepository>.git
