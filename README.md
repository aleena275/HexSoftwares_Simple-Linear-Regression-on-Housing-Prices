# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project is part of a Data Science Internship program. The objective is to build a **Linear Regression model** to predict house prices based on various features such as area, number of rooms, and other amenities.

The project demonstrates the complete Data Science workflow including:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model building
* Model evaluation

---

## 📊 Dataset

* Source: Kaggle Housing Prices Dataset
* Total Records: 545
* Features: 13

### 🔑 Key Features:

* `area` – Size of the house
* `bedrooms` – Number of bedrooms
* `bathrooms` – Number of bathrooms
* `stories` – Number of floors
* `parking` – Parking spaces
* `mainroad`, `guestroom`, `basement`, etc. – Binary categorical features
* `furnishingstatus` – Furnishing type

🎯 **Target Variable:** `price`

---

## 🧹 Data Preprocessing

* Converted categorical values (`yes/no`) into binary (1/0)
* Applied One-Hot Encoding on `furnishingstatus`
* Checked for missing values (dataset was clean)

---

## 📈 Exploratory Data Analysis (EDA)

* Distribution plots to understand price variation
* Correlation heatmap to identify relationships
* Scatter plots (e.g., Area vs Price)
* Boxplots for categorical insights

---

## 🤖 Model Building

* Algorithm used: **Linear Regression**
* Data split into training (80%) and testing (20%)
* Applied feature scaling using StandardScaler

---

## 📊 Model Evaluation

| Metric   | Value        |
| -------- | ------------ |
| R² Score | 0.65         |
| MSE      | 1.75e+12     |
| RMSE     | ~1.3 Million |

### 📌 Interpretation:

* The model explains **65% of the variance** in house prices.
* On average, predictions differ from actual values by around **1.3 million**.

---

## 📉 Visualizations

* Price distribution plot
* Correlation heatmap
* Area vs Price scatter plot
* Actual vs Predicted comparison
* Residual error distribution

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/HexSoftwares_Housing_Prediction.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook in Google Colab or Jupyter Notebook

---

## 📁 Project Structure

```
HexSoftwares_Housing_Prediction/
│
├── Housing.csv
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Key Learnings

* Data cleaning and preprocessing techniques
* Visualization using Seaborn and Matplotlib
* Feature engineering for ML models
* Model evaluation using regression metrics

---

## 📌 Conclusion

The Linear Regression model provides a solid baseline for house price prediction. Further improvements can be made using advanced models and feature engineering techniques.

---


## 👨‍💻 Author

Aleena Sohail.

---
