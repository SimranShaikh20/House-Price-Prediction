# House Price Prediction - Exploratory Data Analysis (EDA) and Model Training

This repository contains code for **Exploratory Data Analysis (EDA)** and **House Price Prediction** using a **Linear Regression** model. The project focuses on analyzing a dataset of house prices based on various features such as area, number of bedrooms, bathrooms, stories, and additional amenities. The aim is to uncover insights through EDA and predict house prices using machine learning.

## Project Overview

This project involves performing **Exploratory Data Analysis (EDA)** on a dataset containing information about houses, followed by training a **Linear Regression** model to predict house prices. The dataset contains a variety of features, including the size of the house, the number of bedrooms, bathrooms, whether the house is near a main road, and whether it has additional amenities such as a guestroom, basement, or air conditioning.

The project demonstrates how to clean and preprocess the data, explore its characteristics, and build a machine learning model for house price prediction.

## Dataset

The dataset used in this project contains the following columns:
- `price`: The price of the house (target variable)
- `area`: Area of the house (in square feet)
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `stories`: Number of stories
- `mainroad`: Whether the house is connected to the main road (yes/no)
- `guestroom`: Whether the house has a guestroom (yes/no)
- `basement`: Whether the house has a basement (yes/no)
- `hotwaterheating`: Whether the house has hot water heating (yes/no)
- `airconditioning`: Whether the house has air conditioning (yes/no)
- `parking`: Number of parking spaces
- `prefarea`: Whether the house is in a preferred area (yes/no)
- `furnishingstatus`: Furnishing status of the house (furnished/semi-furnished/unfurnished)

## Exploratory Data Analysis (EDA)

EDA is an essential step in understanding the dataset. In this project, we perform the following steps:

1. **Data Inspection**: The dataset is first inspected to understand its structure, types of features, and any missing data.
2. **Data Cleaning**: Handling missing values, converting categorical columns to numeric representations, and encoding values such as `yes/no` or `furnished/unfurnished`.
3. **Correlation Analysis**: Visualizing the correlations between numerical features to understand relationships.
4. **Data Visualization**: Using plots such as histograms, boxplots, scatter plots, and heatmaps to uncover insights and patterns in the data.
5. **Feature Engineering**: Creating and modifying features to improve model performance.

## Model Training

Once the data is cleaned and explored, we proceed with building a **Linear Regression** model to predict house prices. The model is trained on the training dataset and evaluated using the test dataset. The following steps are involved:

1. **Feature Selection**: Identifying which features to use for training the model.
2. **Train-Test Split**: Splitting the data into training and testing sets.
3. **Model Training**: Training the Linear Regression model on the training data.
4. **Model Evaluation**: Evaluating the model’s performance using various metrics like Mean Squared Error (MSE) and R-squared.

## Visualizations

In this project, multiple visualizations are used to better understand the data and model:

1. **Correlation Heatmap**: Displays the correlation between numerical features.
2. **Boxplots**: Visualizes the distribution of `price`, `area`, and other features.
3. **Scatter Plots**: Shows relationships between key features, such as `price` vs. `area`.
4. **Pairplots**: Explores the relationships between multiple numerical features.
5. **Count Plots**: Visualizes the frequency of categorical variables such as `mainroad`, `guestroom`, and `furnishingstatus`.

## Technologies Used

- **Python**: The main programming language for data processing and model training.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** & **Seaborn**: For creating visualizations.
- **Scikit-learn**: For building and evaluating the machine learning model.

## Installation

To set up and run this project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
