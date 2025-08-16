# 🧠 Customer Personality Classification

## 📌 Project Overview
This project applies **Machine Learning Classification** to analyze and predict customer behavior based on demographic and purchase-related features.  
The goal is to classify customers into categories that can help businesses understand and target their audience better.

Dataset used: **Customer Personality Analysis** dataset.

---

## 📂 Dataset Description
The dataset contains customer details such as:
- **ID** → Unique customer identifier  
- **Year_Birth** → Year of birth of customer  
- **Education** → Level of education  
- **Marital_Status** → Marital status  
- **Income** → Annual income of customer  
- **Kidhome** → Number of small children in household  
- **Teenhome** → Number of teenagers in household  
- **Dt_Customer** → Date of enrollment  
- **Recency** → Days since last purchase  
- **MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds** → Spending on various product categories  
- **NumDealsPurchases** → Purchases made with a discount  
- **AcceptedCmp1–Cmp5, Response** → Campaign response indicators  
- **Complain** → 1 if customer complained, 0 otherwise  

---

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy** → Data manipulation  
- **Matplotlib, Seaborn** → Data visualization  
- **Scikit-learn** → Machine learning models  

---

## 🔍 Steps Performed
1. **Data Loading & Cleaning**
   - Checked for null values and handled missing `Income` values.
   - Removed duplicates if any.
   - Converted categorical features into numerical format.

2. **Exploratory Data Analysis (EDA)**
   - Generated summary statistics.
   - Visualized correlations using a heatmap.
   - Plotted feature distributions.

3. **Feature Selection & Scaling**
   - Selected important features based on correlation and model importance.
   - Applied feature scaling using **StandardScaler**.

4. **Model Training**
   - Used **Random Forest Classifier** for prediction.
   - Split data into training and testing sets (80% train / 20% test).

5. **Model Evaluation**
   - Calculated **Accuracy** score.
   - Displayed **Classification Report**.
   - Visualized **Confusion Matrix**.

---

## 📊 Results
- **Accuracy:** 0.89 
- **Top Features:**
  - MntSweetProducts
  - MntWines
  - MntCatalogPurchases 
 

# AUTHOR
VARSHINI R
Email id : varshini3031sjcet@gmail.com

