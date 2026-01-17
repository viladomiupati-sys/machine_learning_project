# 📦 Machine Learning Project
# Amazon Sales Report – Predictive Analysis

### Objective
Predict order profitability, delivery performance using historical Amazon sales data.

### Models Used
- Classification 
- Regression 


---
## 🛠️ Tech Stack & Tools

![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![uv](https://img.shields.io/badge/uv-Environment-4CAF50)



---

## Project Overview

We are a team of data analysts who work with data from start to finish, cleaning it, analyzing it, and presenting insights in a clear and meaningful way. Using an Amazon Sales Dataset to buy utilising machine learning


The presentation is available [here](https://docs.google.com/presentation/d/1pEoHlY-TL9XRBMv-8FPQ0ayIoanmZgWjiAP6bJcH5rA/edit?slide=id.g104f1bc08d3_2_74#slide=id.g104f1bc08d3_2_74).
---

## 💾 Data Sources

The analysis shows day from Amazon India between (2022-03-31 - 2022-06-29):

| Dataset                        | Source                                                    | Purpose                                                                                    |
| :----------------------------- | :-------------------------------------------------------- | :----------------------------------------------------------------------------------------- |
| **Amazon Sales Report**        | Kaggle: `mdsazzatsardar/amazonsalesreport/                | Core data for orders across 20+ Indian states.                                             |

---

## Day 1: Topic Selection & Data Acquisition

- The initial day focused on exploratory data analysis (EDA) and defining the analytical framework.
- Acquired Amazon sales data from Kaggle.
- Performed initial exploratory data analysis (EDA) to understand structure, distributions, and class imbalance.

---

## Day 2: Data Preparation

- Cleaned and standardized column names
- Handled missing values and inconsistent data types
- Begin feature engineering to enhance your model's predictive capabilities.

---

## Day 3: Model Development & Initial Tuning 

- Implemented a K-Nearest Neighbors (KNN) classification model, Linear Regression, Decision Tree, and Random Forest. 
- Applied feature scaling and categorical encoding
- Split data into stratified training and test sets
- Evaluated performance using accuracy, random forest 

---

## Day 4: Model Evaluation & Presentation

- Analyzed model performance:
- Accuracy, Confusion matrix, Precision, recall, and F1-score
- Identified limitations caused by class imbalance
- Created visualizations for presentation
- Prepared final project slides

---

# 📊 Results
## KNN

- Accuracy: ~92%
- Strong performance for Delivered orders
- Lower performance for Cancelled and Returned orders due to class imbalance

## Linear Regression, Decision Tree and Random Forest.

- Three models were evaluated using an 80/20 train–test split: Linear Regression, Decision Tree, and Random Forest.
- Among the tested models, Random Forest achieved the best overall performance.
- Random Forest produced the highest R² score (0.52), explaining the most variance in the target variable.
- It also achieved the lowest MAE (135.6) and lowest RMSE (186.1), indicating more accurate predictions compared to the other models.

---

## ⚠️ Limitations

- Dataset is highly imbalanced
- KNN struggles to identify rare classes
- Performance depends heavily on the quality and scope of the available data.
- Random Forest models are less interpretable than simpler models like Linear Regression.
- Results are based on a single train–test split and may vary with different data partitions.

---

# 🏁 Conclusion

Overall, the machine learning models demonstrated strong predictive performance, with KNN effectively classifying delivery outcomes and Random Forest providing the most accurate regression results.
While high accuracy was achieved, class imbalance and unexplained variance highlight the limitations of the data and models.
These results show the value of machine learning for real world analysis while emphasizing the need for careful evaluation and further model refinement.

---

## 👥 Team

Alan, Pati, Pedro, Charul.