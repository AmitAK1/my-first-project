# Car Price Prediction 🚗💰

This machine learning project predicts the resale price of used cars based on features like car name, company, year, kilometers driven, and fuel type. It is built using Python and linear regression, and aims to provide a simple and intuitive way to estimate car prices.

# Live Demo : https://car-price-predictor-dst2q7rnylbxz63dnb2zsz.streamlit.app/ 
---

## 📦 Features Used
- **Car Name**
- **Company**
- **Year of Manufacture**
- **Kilometers Driven**
- **Fuel Type**

The target variable is the **Price** of the car.

---

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas, NumPy
- Scikit-learn (Linear Regression)
- Jupyter Notebook
- Render (for deployment)

---

## 🧹 Preprocessing
Basic preprocessing steps were applied:
- Handled categorical variables with encoding
- Converted text-based numeric data (like kms) to proper format
- Removed outliers and inconsistent entries

---

## 🧠 Model
A simple **Linear Regression** model was trained on the cleaned dataset. Due to limited data, a lightweight approach was preferred for faster experimentation and deployment.

---

## 💻 Usage
- A user interface with dropdowns is provided to select:
  - Car Name
  - Fuel Type
  - Company
  - Year
  - Kilometers Driven
- After selection, the model returns the **predicted price** of the car.

---

## 📊 Dataset
- Source: [Kaggle]

---

## 🚀 Deployment
This project is deployed using **Render**, allowing users to access the prediction tool directly from their browser.

---

## 🔗 Future Improvements
- Add more advanced models (Random Forest, XGBoost)
- Include feature importance visualizations
- Improve UI/UX with better styling

