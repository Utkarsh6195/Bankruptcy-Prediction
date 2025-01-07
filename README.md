# Bankruptcy-Prediction Project

## 📚 Overview
- This project leverages machine learning techniques to predict bankruptcy based on financial data. The dataset consists of 96 financial metrics, such as
profitability, liquidity, and leverage ratios, providing a comprehensive view of companies' financial health. The analysis focuses on preprocessing, feature engineering, and building predictive models to generate actionable insights for stakeholders.

## 🛠️ Key Features
Data Preprocessing: Cleaned the dataset by handling missing values, removing duplicates, and addressing outliers using IQR.

### Exploratory Data Analysis (EDA):
- Visualized data distributions using histograms and boxplots.
- Identified and handled skewed distributions.
### Feature Engineering: Constructed and selected features based on financial and business relevance.
### Imbalanced Data Handling: Used SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
### Model Development: Built and evaluated multiple classification models, including:
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
### Model Evaluation: Assessed model performance using accuracy, precision, recall, F1-score, and ROC AUC metrics.
### Visualization: Used Seaborn and Matplotlib for data exploration and result presentation.

## ⚙️ Tools and Technologies
- Python: Data manipulation and modeling
- Pandas & NumPy: Data preprocessing and analysis
- Scikit-learn: Machine learning and model evaluation
- Seaborn & Matplotlib: Data visualization
- Imbalanced-learn: Handling class imbalance with SMOTE

## 📈 Results
- Identified key features influencing bankruptcy prediction.
- Achieved [96% accuracy, 97% precision, and 97% F1-score] with the [Random Forest].
