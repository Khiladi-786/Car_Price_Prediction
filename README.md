# 🚗 Car Price Prediction Model

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

> A machine learning model to predict used car prices based on key vehicle features like brand, year, mileage, and fuel type.

---

## 📌 Project Overview

Buying or selling a used car at the right price is a challenge — prices vary wildly based on brand, age, mileage, and condition. This project builds a **Car Price Prediction System** using machine learning to estimate the fair market value of a used car based on its features.

Developed as part of my **Data Science Internship at Oasis Infobyte**.

---

## 🎯 Key Highlights

- ✅ Built and compared **multiple ML models** for best accuracy
- ✅ Performed **EDA** to understand price distribution and feature importance
- ✅ Handled missing values, outliers, and categorical encoding
- ✅ Identified key factors that drive used car prices
- ✅ Clean **Jupyter Notebook** with step-by-step analysis

---

## 📊 Dataset

| Property | Details |
|---|---|
| Task | Regression — predict car selling price |
| Features | Brand, Year, Selling Price, Present Price, Mileage, Fuel Type, Seller Type, Transmission, Owner |
| Target | Car Selling Price (in ₹ Lakhs) |

---

## 🔍 Key Features Used

| Feature | Description |
|---|---|
| `Car_Name` | Brand and model of the car |
| `Year` | Manufacturing year |
| `Present_Price` | Current showroom price (₹ Lakhs) |
| `Driven_kms` | Total kilometers driven |
| `Fuel_Type` | Petrol / Diesel / CNG |
| `Seller_Type` | Dealer or Individual |
| `Transmission` | Manual or Automatic |
| `Owner` | Number of previous owners |

---

## 🧠 Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed price distribution across brands, fuel types, and transmission
- Found that **year and present price** are the strongest predictors
- Identified outliers in `Driven_kms` and handled them appropriately

### 2. Feature Engineering
- Created `Car_Age` feature from manufacturing year
- Encoded categorical variables (Fuel Type, Seller Type, Transmission)
- Dropped irrelevant columns

### 3. Model Training
- Trained and compared multiple regression models
- Selected best model based on R² score and RMSE

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | ML model training & evaluation |
| Jupyter Notebook | Development environment |

---

## 🏆 Model Results

| Metric | Score |
|---|---|
| R² Score | *0.89* |
| RMSE | *1.23* |

> 💡 Open `sample.ipynb` to see the full results and model comparison.

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Khiladi-786/Car-Price-Prediction.git
cd Car-Price-Prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook sample.ipynb
```

---

## 📁 Project Structure

```
Car-Price-Prediction/
│
├── sample.ipynb          # Main Jupyter Notebook
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 💡 Key Insights

- **Car age** is the strongest predictor — newer cars fetch significantly higher prices
- **Diesel cars** depreciate slower than petrol cars
- **Automatic transmission** cars command a premium over manual
- **Individual sellers** price lower than dealers for the same car
- Cars with **0 previous owners** are priced 30-40% higher on average

---

## 👨‍💻 About the Author

**Nikhil More**
B.Tech CSE (AI/ML) — University of Mumbai (2023–2027)

- 🔗 [LinkedIn](https://www.linkedin.com/in/nikhil-moretech)
- 🐙 [GitHub](https://github.com/Khiladi-786)
- 📧 morenikhil7822@gmail.com

*Data Science Intern @ Oasis Infobyte | C-DAC Ambassador | Google Student Ambassador*

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ **If you found this project useful, please give it a star!**


