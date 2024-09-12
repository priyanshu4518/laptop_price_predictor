# laptop_price_predictor 
This project aims to predict the prices of laptops based on various features such as company, type, screen size, resolution, CPU, RAM, memory, GPU, operating system, and weight. The dataset used for this project contains information about different laptop models and their prices.

## Table of Content
Usage
Dataset
Preprocessing
Model Training
Deployment
## Usage
To run the project, use the following command:

streamlit run app.py

This will start a Streamlit web application where you can input laptop features and get the predicted price.

## Dataset
The dataset used in this project is laptop.csv, which contains the following columns:

Company: The company that manufactures the laptop.
TypeName: The type of laptop (e.g., Ultrabook, Notebook).
Inches: The screen size of the laptop.
ScreenResolution: The screen resolution of the laptop.
Cpu: The CPU model.
Ram: The amount of RAM in GB.
Memory: The storage capacity and type.
Gpu: The GPU model.
OpSys: The operating system.
Weight: The weight of the laptop in kg.
Price: The price of the laptop.
## Preprocessing
The preprocessing steps include:

Dropping unnecessary columns.
Cleaning and converting data types for Ram and Weight.
Handling missing values and encoding categorical variables.
## Model Training
The model is trained using various machine learning algorithms. The steps include:

Splitting the dataset into training and testing sets.
Training models such as Linear Regression, Random Forest, and Gradient Boosting.
Evaluating the models using metrics like RMSE and R²

## Deployment
The model is deployed using Streamlit to create an interactive web application. The app allows users to input laptop features and get the predicted price
