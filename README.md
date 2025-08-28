# project3_wildfire-ml-algeria
Data analysis and ML models for Algerian Forest Fires dataset — includes preprocessing, regression modeling, and reproducible Jupyter notebooks.
# Algerian Forest Fires ML Project

This repository contains an end-to-end machine learning workflow on the **Algerian Forest Fires dataset**.  
The main objective is to study wildfire behavior, clean and prepare the data, and build predictive models to understand the factors that influence fire occurrence.

---

## Contents
- `Algerian_forest_fires_dataset_updated.csv` → Original dataset  
- `Algerian_forest_fires_cleaned_dataset.csv` → Preprocessed dataset  
- `data_cleaning_eda.ipynb` → Data exploration and preprocessing (EDA).
- `Model Training.ipynb` → Training baseline ML models .Applying Ridge, Lasso and ElasticNet regression.  Along with cross validations.

---

## Dataset
The dataset includes meteorological conditions and fire indicators from two Algerian regions during summer 2012.  
Some key variables are:  
- Temperature  
- Humidity  
- Wind  
- Rain  
- Fire Weather Index codes (FFMC, DMC, DC, ISI)  
- Target: Fire vs No Fire  

---

## Steps Followed
1. **Data preprocessing** → Cleaning, handling missing values, encoding, and scaling  
2. **Exploratory Data Analysis** → Visualizing patterns and relationships  
3. **Model training** → Building baseline machine learning models  
4. **Regularized regression** → Using Ridge and Lasso for better generalization  
5. **Evaluation** → Comparing model accuracy and performance metrics  

---
## Tools & Technologies Used

### Languages & Environment
- Python  
- Jupyter Notebook  

### Libraries
- **Data Handling** → Pandas, NumPy  
- **Visualization** → Matplotlib, Seaborn  
- **Modeling** → Scikit-learn  

### Visualizations
- Histograms and bar plots  
- Boxplots and violin plots (for outlier and distribution analysis)  
- Correlation heatmaps  
- Line plots (for trends across regions and months)  
- Pair plots (to study relationships between features)  
- Scatter plots with regression lines  

### Machine Learning Models
- **Ridge Regression**  
- **Lasso Regression**  
- **ElasticNet Regression**  

### Cross Validation
- RidgeCV  
- LassoCV  
- ElasticNetCV  

---

## License
This project is under the **MIT License**.  

---

## Acknowledgement
Dataset reference: UCI Machine Learning Repository.
Link to Dataset : https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset


