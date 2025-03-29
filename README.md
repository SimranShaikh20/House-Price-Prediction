# 🏡 House Price Prediction - Exploratory Data Analysis (EDA) and Model Training

This repository contains code for **Exploratory Data Analysis (EDA)** and **House Price Prediction** using a **Linear Regression** model. The project focuses on analyzing a dataset of house prices based on various features such as area, number of bedrooms, bathrooms, stories, and additional amenities. The aim is to uncover insights through EDA and predict house prices using machine learning.

---

## 📌 Project Overview

This project involves performing **Exploratory Data Analysis (EDA)** on a dataset containing information about houses, followed by training a **Linear Regression** model to predict house prices. The dataset contains a variety of features, including:
✅ Size of the house (area)
✅ Number of bedrooms & bathrooms
✅ Presence of amenities like a basement, guestroom, or air conditioning
✅ Proximity to the main road
✅ Parking availability
✅ Preferred area classification

The project demonstrates how to clean and preprocess the data, explore its characteristics, and build a machine learning model for house price prediction.

---

## 📂 Dataset

The dataset used in this project contains the following columns:
- **`price`** 💰 - House price (target variable)
- **`area`** 📏 - House size (in square feet)
- **`bedrooms`** 🛏 - Number of bedrooms
- **`bathrooms`** 🚿 - Number of bathrooms
- **`stories`** 🏢 - Number of stories
- **`mainroad`** 🛣 - Connected to the main road? (yes/no)
- **`guestroom`** 🏠 - Has a guestroom? (yes/no)
- **`basement`** 🔽 - Has a basement? (yes/no)
- **`hotwaterheating`** 🔥 - Hot water heating? (yes/no)
- **`airconditioning`** ❄ - Air conditioning? (yes/no)
- **`parking`** 🚗 - Number of parking spaces
- **`prefarea`** 📍 - Located in a preferred area? (yes/no)
- **`furnishingstatus`** 🛋 - Furnishing status (furnished/semi-furnished/unfurnished)

---

## 📊 Exploratory Data Analysis (EDA)

EDA is an essential step in understanding the dataset. The following steps are performed:

1️⃣ **Data Inspection** - Checking dataset structure, missing values, and data types.
2️⃣ **Data Cleaning** - Handling missing values, encoding categorical variables.
3️⃣ **Correlation Analysis** - Understanding feature relationships via a correlation heatmap.
4️⃣ **Data Visualization** - Using plots like histograms, boxplots, scatter plots, and heatmaps.
5️⃣ **Feature Engineering** - Creating/modifying features for better model performance.

---

## 🤖 Model Training

After data cleaning and exploration, a **Linear Regression** model is trained to predict house prices. The steps include:

🔹 **Feature Selection** - Identifying key features for model training.
🔹 **Train-Test Split** - Dividing data into training and testing sets.
🔹 **Model Training** - Training a Linear Regression model using Scikit-learn.
🔹 **Model Evaluation** - Evaluating model performance with Mean Squared Error (MSE) & R-squared.

---

## 📈 Visualizations

Several visualizations are used to gain insights into the dataset and model performance:

📌 **Correlation Heatmap** - Displays correlations between numerical features.
📌 **Boxplots** - Shows data distributions for `price`, `area`, and other features.
📌 **Scatter Plots** - Highlights relationships between key features.
📌 **Pairplots** - Explores multiple feature relationships.
📌 **Count Plots** - Analyzes categorical feature distributions.

---

## 🛠 Technologies Used

- 🐍 **Python** - Main programming language
- 📊 **Pandas** - Data manipulation and analysis
- 🔢 **NumPy** - Numerical operations
- 📉 **Matplotlib & Seaborn** - Data visualization
- 🤖 **Scikit-learn** - Machine learning model training

---

## 🚀 Installation

To set up and run this project on your local machine, follow these steps:

1️⃣ Clone the repository:

```bash
 git clone https://github.com/SimranShaikh20/house-price-prediction.git
 cd house-price-prediction
```

2️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

3️⃣ Run the analysis script:

```bash
python house_price_analysis.py
```

---

## 🎯 Future Enhancements

🚀 Add more advanced models like **Random Forest** or **XGBoost**.
🚀 Perform **Hyperparameter tuning** to improve model accuracy.
🚀 Deploy the model using **Flask** or **Streamlit** for a web-based UI.

---

## 📬 Contact

💡 Feel free to contribute or reach out for collaboration!


---

📌 *Star ⭐ this repository if you find it useful!* 🚀

