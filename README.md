# Housing-Price-Prediction-Model

# 🏡 Housing Price Prediction (King County)

A modular machine learning pipeline to predict housing prices in King County, WA using data-driven techniques and regression models.

## 🔍 Overview
- Performed end-to-end data analysis and modeling using a structured 12-step notebook workflow.
- Cleaned and prepared housing data using pandas and NumPy.
- Conducted exploratory data analysis (EDA) with Matplotlib and Seaborn to uncover patterns and correlations.
- Engineered new features and applied transformations for model optimization.
- Trained and evaluated Linear, Ridge, and Polynomial Regression models using scikit-learn.
- Achieved 70% R² score with a Polynomial Regression model (degree=2).
- Designed a scalable pipeline for reproducible machine learning workflows.

## 📊 Technologies Used
- Python, Jupyter Notebooks  
- pandas, NumPy  
- scikit-learn (Linear, Ridge, Polynomial Regression, Pipeline APIs)  
- Matplotlib, Seaborn  

## 🧱 Project Structure
Housing-Price-Prediction/
│
├── data/                      # Raw and cleaned datasets
│
├── notebooks/                 # 12 modular Jupyter notebooks, each covering a pipeline stage
│   ├── 01_data_loading.ipynb
│   ├── 02_data_inspection.ipynb
│   ├── 03_data_cleaning.ipynb
│   ├── 04_missing_values.ipynb
│   ├── 05_feature_engineering.ipynb
│   ├── 06_outlier_treatment.ipynb
│   ├── 07_exploratory_analysis.ipynb
│   ├── 08_linear_regression.ipynb
│   ├── 09_polynomial_regression.ipynb
│   ├── 10_ridge_regression.ipynb
│   ├── 11_pipeline_construction.ipynb
│   └── 12_model_evaluation.ipynb
│
├── visuals/                   # Saved plots and visualizations
│
├── requirements.txt           # Python package dependencies
│
└── README.md                  # Project overview and documentation
