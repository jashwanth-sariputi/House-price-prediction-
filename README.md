# House-price-prediction-
House price prediction using linear regression
# 🏠 House Price Prediction using Multiple Linear Regression

##📌 About the Project

This project is a simple machine learning application that predicts the price of a house based on several important factors such as the size of the house, number of bedrooms, bathrooms, location, parking spaces, and the age of the property.

The goal of this project is to understand how **Multiple Linear Regression** works and how it can be used to solve real-world problems like estimating house prices. By analyzing different features of a house, the model learns patterns in the data and provides a predicted price.

This project is mainly created as a **learning project for machine learning and data science beginners** using Python.

## 🎯 Project Goals

The main goals of this project are:

* To understand the basics of **machine learning regression models**
* To learn how to **prepare and process data using Python**
* To train a model using **Scikit-learn**
* To predict house prices based on user input
* To visualize how house size affects house price

## 📊 Dataset Information

The dataset used in this project contains basic information about different houses. Each row represents a house and its features.

The dataset includes the following columns:

* **Area** – Size of the house in square feet
* **Bedrooms** – Number of bedrooms in the house
* **Bathrooms** – Number of bathrooms
* **Location** – Whether the house is located in an Urban, Suburban, or Rural area
* **Parking** – Number of parking spaces available
* **Age** – Age of the house in years
* **Price** – The actual price of the house (target variable)

Example of the dataset:

| Area | Bedrooms | Bathrooms | Location | Parking | Age | Price  |
| ---- | -------- | --------- | -------- | ------- | --- | ------ |
| 1000 | 2        | 1         | Urban    | 1       | 10  | 200000 |
| 1500 | 3        | 2         | Urban    | 1       | 5   | 300000 |
| 2000 | 3        | 2         | Suburban | 2       | 6   | 400000 |
| 2500 | 4        | 3         | Suburban | 2       | 3   | 500000 |
| 3000 | 4        | 3         | Rural    | 3       | 2   | 600000 |

## 🛠 Tools and Libraries Used

This project was built using the following technologies:

* **Python** – Programming language used for the project
* **Pandas** – Used for handling and analyzing the dataset
* **Scikit-learn** – Used to build and train the machine learning model
* **Matplotlib** – Used for creating simple data visualizations

## ⚙️ How the Project Works

### 1. Creating the Dataset

First, the dataset containing house information is created and stored in a **Pandas DataFrame**.

### 2. Data Preprocessing

The **Location** column contains text values (Urban, Suburban, Rural). Since machine learning models work with numbers, the values are converted into numerical form using **Label Encoding**.

For example:

* Rural → 0
* Suburban → 1
* Urban → 2

### 3. Selecting Features

The model uses the following features to predict house prices:

* Area
* Bedrooms
* Bathrooms
* Location
* Parking
* Age

The **Price** column is used as the target variable.

### 4. Training the Model

The model used in this project is **Multiple Linear Regression**.
It learns the relationship between the house features and the house price.

During training, the algorithm calculates coefficients that represent how each feature affects the price.

### 5. Predicting House Prices

After the model is trained, the program asks the user to enter house details such as:

* Area
* Bedrooms
* Bathrooms
* Location
* Parking spaces
* Age of the house

Based on these inputs, the model predicts the **estimated price of the house**.

## 📈 Data Visualization

A scatter plot is used to visualize the relationship between **Area and House Price**.

* The **X-axis** represents the area of the house.
* The **Y-axis** represents the house price.

This visualization helps show how the price generally increases as the area of the house increases.

## ▶️ How to Run the Project

### Step 1: Install Required Libraries
### Step 2: Run the Python File


### Step 3: Enter House Details

The program will ask you to enter information about a house. After entering the values, the program will display the **predicted house price**.

## 💡 Possible Improvements

This is a basic machine learning project, but it can be improved in many ways, such as:

* Using a **larger real-world housing dataset**
* Adding more features like nearby schools, hospitals, or transportation
* Comparing different machine learning models
* Building a **web application using Streamlit or Flask**
* Deploying the project online

## 📚 What I Learned

While building this project, I learned:

* How regression models work in machine learning
* How to preprocess data for machine learning models
* How to train and use models with **Scikit-learn**
* How to visualize data using **Matplotlib**

## 👨‍💻 Author

This project was created as part of my **learning journey in machine learning and data science** using Python.

## 🔑 Keywords

Machine Learning
Python
Data Science
Linear Regression
House Price Prediction

