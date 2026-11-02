# Big_Mart_Sales_Prediction_using_ML
# Big Mart Sales Prediction Using XGBoost Regression

## 📌 Project Overview

The **Big Mart Sales Prediction** project aims to predict the sales of products across different Big Mart outlets using Machine Learning techniques.

The project analyzes various product and outlet-related attributes to understand sales patterns and build a predictive model using the **XGBoost Regressor**.

The main objective is to develop a Machine Learning model that can estimate product sales based on historical data.

## 🎯 Objectives

- Analyze retail sales data to identify important patterns and trends.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and inconsistent data.
- Perform data preprocessing and feature engineering.
- Convert categorical variables into numerical format.
- Train a regression model using XGBoost.
- Evaluate the model's prediction performance.

## 📂 Dataset Description

The dataset contains information about products and retail outlets.

Important features include:

| Feature | Description |
|---|---|
| Item_Identifier | Unique product identifier |
| Item_Weight | Weight of the product |
| Item_Fat_Content | Fat content of the product |
| Item_Visibility | Visibility of the product in the outlet |
| Item_Type | Category of the product |
| Item_MRP | Maximum Retail Price |
| Outlet_Identifier | Unique outlet identifier |
| Outlet_Establishment_Year | Year the outlet was established |
| Outlet_Size | Size of the outlet |
| Outlet_Location_Type | Location category of the outlet |
| Outlet_Type | Type of retail outlet |
| Item_Outlet_Sales | Target variable representing product sales |

## 🛠️ Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## ⚙️ Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Analyzed dataset structure and dimensions.
- Examined numerical and categorical features.
- Identified missing values.
- Studied data distributions and relationships.
- Visualized important patterns using graphs.

### 2. Data Preprocessing
- Handled missing values in Item_Weight and Outlet_Size.
- Standardized inconsistent values in Item_Fat_Content.
- Converted categorical variables into numerical values using Label Encoding.
- Prepared the dataset for model training.

### 3. Feature Engineering
- Extracted useful information from product identifiers.
- Explored and transformed existing features.
- Prepared relevant features for sales prediction.

### 4. Model Building
- Separated independent and dependent variables.
- Split the dataset into training and testing sets.
- Trained an XGBoost Regressor.
- Used the trained model to predict product sales.

### 5. Model Evaluation
Evaluated the regression model using appropriate performance metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 📊 Target Variable

`Item_Outlet_Sales`

The model predicts the sales of individual products in different retail outlets.

## 🚀 Installation and Setup

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**Step 2: Navigate to the project directory**

```bash
cd Big-Mart-Sales-Prediction
```

**Step 3: Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

**Step 4: Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open the project notebook
