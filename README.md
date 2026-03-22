
#  E-commerce Furniture Data Analysis & Sales Prediction

## 📌 Project Overview

This project focuses on analyzing an e-commerce furniture dataset to understand pricing patterns, sales behavior, and the impact of shipping types on product performance.

The project performs end-to-end data analysis including data cleaning, exploratory data analysis (EDA), visualization, and machine learning to derive insights and attempt prediction of product sales.

---

## 🎯 Objectives

- Analyze the distribution of furniture product prices  
- Understand the relationship between price and units sold  
- Study the impact of shipping types on product performance  
- Perform exploratory data analysis (EDA) with visual insights  
- Build and evaluate machine learning models to predict product sales  
- Extract meaningful business insights from the dataset  

---

## 🗂 Dataset

- **Source:** E-commerce Furniture Dataset  
- **Records:** ~2000 products  
- **Features:** Product Title, Price, Units Sold, Shipping Type  
- **Target Variable:** Units Sold  

---

## 🔍 Exploratory Data Analysis (EDA)

### Key insights:

- Most products fall within low to mid price ranges  
- Lower-priced products tend to have higher sales  
- Free shipping products dominate the dataset  
- Price distribution is slightly right-skewed with some high-value outliers  

EDA was supported with visualizations such as histograms, boxplots, scatter plots, and violin plots.

---

## 🤖 Machine Learning Approach

### 📌 Models Implemented

- Random Forest Regressor  
- XGBoost Regressor  

### ⚙️ Key Techniques

- Data cleaning and preprocessing  
- Handling missing values  
- Label Encoding for categorical features  
- Feature scaling using StandardScaler  
- Train-test split for evaluation  

---

## 📊 Model Performance

- Models produced low or negative R² scores  
- High prediction errors (MSE) observed  
- XGBoost did not improve performance despite being an advanced model  

👉 This indicates that the dataset lacks sufficient features for accurate prediction.

---

## 🧠 Business Usage

This project can help e-commerce platforms to:

- Understand pricing strategies and sales trends  
- Analyze the impact of shipping options on product performance  
- Identify popular price ranges for better marketing decisions  
- Support basic forecasting and business insights  

---

## ⚠️ Limitations

- Limited dataset features (only price and shipping type)  
- Missing important variables like ratings, reviews, and product category  
- Weak relationship between features and target variable  
- Low model accuracy due to insufficient data  
- Predictions are not reliable for real-world deployment  

---

## 🛠 Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

---

## 📁 Repository Contents

- `furniture.ipynb` → Complete analysis and ML model  
- `ecommerce_furniture_dataset_2024.csv` → Dataset used  
- `README.md` → Project documentation  

---

## 👤 Author

**Vikas Gowda V**  
Aspiring Data Analyst / Data Scientist  

---

## ⭐ Conclusion

This project presents a complete data analysis and machine learning workflow on an e-commerce furniture dataset. Through exploratory data analysis (EDA), meaningful insights were obtained regarding price distribution, sales patterns, and the impact of shipping types.

Machine learning models such as Random Forest and XGBoost were implemented to predict the number of units sold. However, both models showed poor performance, with low or negative R² scores, indicating that accurate prediction was not achievable with the given data.

The primary reason for this limitation is the lack of sufficient and relevant features in the dataset. Important factors such as product ratings, reviews, category, and customer behavior are missing, which are essential for reliable sales prediction.

### Final takeaway

This project highlights that while model selection is important, the quality and richness of data play a more critical role in achieving accurate machine learning outcomes.
