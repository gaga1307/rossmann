# Rossmann Store Sales Prediction

This project transforms the retail sales forecasting problem into a binary classification task. The goal is to predict whether a specific store's daily sales will be higher (1) or lower (0) than its average sales from the previous 30 days.

## Project Overview
**Technologies and tools used:**
- Libraries: Pandas, Seaborn, NumPy, Scikit-learn, Imbalanced-learn
- Machine Learning Models: Decision Tree, Random Forest, AdaBoost
- Validation Technique: TimeSeriesSplit used within GridSearchCV to optimize model parameters chronologically

**Workflow**
- Data Integration: Merged historical sales records with store attributes.
- Exploratory Data Analysis and Data Cleaning
- Modeling via Pipeline: Implemented an automated pipeline using *ColumnTransformer* to handle preprocessing and model training simultaneously

**Key Insights**
- Main Drivers: Promotional activity (Promo) and the Day of the Week are the most critical factors influencing sales performance.
- Seasonality: All stores experience a significant sales peak during December.
- Random Forest achieved the best results with an F1-score of 0.883.

You can find the dataset on Kaggle - [Rossman store sales](https://www.kaggle.com/c/rossmann-store-sales)

A detailed description of the project, methodology, and results is available in the PDF report:

📄 [Project Report (PDF)](Doc_Rossman_Store_Sales.pdf)
