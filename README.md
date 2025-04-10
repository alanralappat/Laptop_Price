# 💻 Laptop Price Prediction

Predict laptop prices using machine learning techniques based on various technical specifications such as RAM, CPU, GPU, and more.

## 📂 Overview

This project leverages data analysis and machine learning to build a regression model that predicts the price of a laptop. It covers:

- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)
- Model Building & Evaluation

## 📊 Dataset

The dataset `laptop_price.csv` contains specifications and prices of laptops from various brands.

Key features include:
- `Company`
- `TypeName`
- `Inches`
- `ScreenResolution`
- `Cpu`
- `Ram`
- `Memory`
- `Gpu`
- `OpSys`
- `Weight`
- `Price` (target variable)

## ⚙️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🧪 ML Approach

- Handled categorical and numerical data
- Engineered features like **Pixels Per Inch (PPI)** from resolution
- Trained a **Linear Regression** model
- Evaluated using **R² Score**

## 🔍 Results

The model was evaluated using R² score, giving a good baseline for predicting laptop prices. Further improvements can include:

- Testing more advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Cross-validation

## 📁 How to Run

1. Clone the repository
2. Install required libraries:  
   `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open the Jupyter notebook:  
   `Laptop_Price.ipynb`

## 📌 Future Improvements

- Add model comparison section
- Create a user interface for real-time predictions
- Deploy model using Flask or Streamlit

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

---
