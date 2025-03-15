# House Price Prediction

## Overview
This project aims to predict house prices based on various features using machine learning techniques. It involves data preprocessing, exploratory data analysis, feature scaling, model training, and optimization using Ridge and Lasso regression.

## Dataset
The dataset contains multiple features related to house pricing, such as area, number of bedrooms, furnishing status, and more. It is preprocessed to handle categorical variables and scaled for better model performance.

## Implementation Steps
1. **Data Preprocessing**
   - Load the dataset
   - Handle missing values (if any)
   - Encode categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Correlation matrix visualization
   - Distribution of features using histograms

3. **Model Training**
   - Split the dataset into training and testing sets
   - Train a Linear Regression model
   - Evaluate using R² score

4. **Model Optimization**
   - Use Ridge and Lasso regression with hyperparameter tuning (GridSearchCV)
   - Compare models based on performance metrics

## Key Takeaways
- Ridge Regression (L2 regularization) and Lasso Regression (L1 regularization) help optimize models by reducing overfitting.
- GridSearchCV helps find the best hyperparameters for improved accuracy.
- Feature scaling enhances the performance of machine learning models.

## Results
- The best alpha values for Ridge and Lasso regression were determined using cross-validation.
- Final model comparison based on R² scores provides insights into the best approach for house price prediction.

## Repository
[GitHub Repository](https://github.com/RNNivash/House-Price-Prediction.git)

## Requirements
Install the necessary dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Run the Project
To execute the project, run the Python script:
```bash
python house_price_prediction.py
```

## Contact
For any queries, feel free to reach out:
- LinkedIn: [Nivash R N](https://www.linkedin.com/in/nivash-r-n/)
- Email: hello.nivashinsights@gmail.com

