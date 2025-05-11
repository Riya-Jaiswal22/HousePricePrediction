# 🏡 House Price Prediction App

An interactive **web application** built using **Streamlit** and **scikit-learn** that predicts the price of a house based on user-selected features like **City**, **Area**, **Number of Baths**, **Balcony**, and **BHK**. The model is trained on a custom housing dataset and uses **Linear Regression** for making predictions.

---


## 📌 Features

- 📂 Upload your own housing dataset (CSV format)
- 🔍 Automatic data preprocessing and price normalization
- 🧠 Extracts and imputes missing features like BHK
- 🔧 Built-in feature engineering (location parsing, one-hot encoding)
- 📈 Predicts housing prices using trained Linear Regression model
- 💡 Simple and intuitive UI powered by **Streamlit**

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **pandas**, **NumPy** – data cleaning and manipulation
- **scikit-learn** – model building and encoding
- **Streamlit** – frontend UI
- **re** – text parsing and feature extraction

---

## 🧠 Model Details

- Model: **Linear Regression**
- Preprocessing:
  - Extract `City` and `Area` from `Location`
  - Extract and impute missing `BHK` from `Description`
  - Convert `Price` from string format (₹L/Cr) to numeric
  - Encode categorical variables using `OneHotEncoder`
- 80/20 train-test split
- Input validation to ensure only valid options are passed

---

