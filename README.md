# House Price Prediction

## 📌 Overview
This project aims to predict house prices using various machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and model optimization using **Linear Regression, Ridge Regression, and Lasso Regression**.

## 🗂 Dataset
The dataset used for this project is `Housing.csv`, containing various features related to real estate properties.

### **Features in the Dataset:**
- **Price**: Dependent variable (Target)
- **Area**: Size of the property
- **Bedrooms, Bathrooms, Stories**: Structural details of the house
- **Mainroad, Guestroom, Basement, Hotwaterheating, Airconditioning, Parking, Prefarea, Furnishingstatus**: Additional features

## 🛠 Tech Stack
- **Programming Language**: Python 🐍
- **Libraries Used**: `pandas`, `matplotlib`, `seaborn`, `sklearn`

## 📊 Exploratory Data Analysis (EDA)
- **Descriptive statistics** (`df.describe()`, `df.info()`, `df.isna().sum()`)
- **Correlation Analysis** using a heatmap
- **Distribution Analysis** using histograms

## 🔄 Data Preprocessing
- **Encoding categorical variables** using `LabelEncoder`
- **Feature Scaling** using `StandardScaler`
- **Splitting dataset** into training and test sets

## 🤖 Model Training & Evaluation
### **Linear Regression**
- Trained using `LinearRegression()`
- Evaluated using **R² Score**

### **Regularization Techniques**
- **Ridge Regression (L2 Regularization)**
- **Lasso Regression (L1 Regularization)**
- **Hyperparameter Tuning using GridSearchCV**
- **Cross-validation with `cv=5`**

## 📈 Results
- **Best Alpha Values** for Ridge and Lasso found using `GridSearchCV`
- **Comparison of R² Scores** to select the best model
- **Understanding the effect of L1 & L2 regularization on feature selection and model performance**

## 🏁 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/RNNivash/House-Price-Prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd house-price-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook
   ```

## 🏆 Conclusion
- **Ridge vs. Lasso:** Ridge shrinks coefficients but retains all features, while Lasso performs feature selection.
- **Hyperparameter tuning improves model performance significantly.**
- **Choosing the best model depends on R² scores and interpretability requirements.**

---
**🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/nivash-r-n/)**

