# Bangalore House Price Prediction

This project aims to predict house prices in Bangalore using machine learning regression models. The goal is to estimate the price of a house based on various features such as square footage, number of bedrooms (BHK), number of bathrooms, and location.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Dataset](#dataset)
4. [How to Run the Project](#how-to-run-the-project)
5. [Model Evaluation](#model-evaluation)
6. [UI](#ui)
7. [Future Work](#future-work)

## Project Overview
In this project, multiple regression models were applied to predict real estate prices in Bangalore. The model was trained on historical data, and features like area (in square feet), location, number of bedrooms (BHK), and number of bathrooms were used to make predictions.

We built a Flask API to serve predictions, and a simple frontend interface was developed to provide an interactive way to estimate house prices based on user inputs.

## Technologies Used
- Python 3.x
- Flask
- HTML, CSS, JavaScript
- Pandas, Numpy
- Scikit-Learn for regression models
- Matplotlib/Seaborn for data visualization
- Bootstrap for frontend
- AWS (for deployment and hosting)
  
## Dataset
The dataset used in this project contains details of various houses in Bangalore, including:
- Area (in square feet)
- Location
- Number of bedrooms (BHK)
- Number of bathrooms
- Price (the target variable)

The dataset was cleaned and preprocessed to handle outliers and missing values. The final data was used to train multiple regression models, including Linear Regression, Ridge Regression, and Lasso Regression.

## How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/username/bangalore-house-price-prediction.git
cd bangalore-house-price-prediction
```
### 2. Install the required dependencies

```bash
pip install -r requirements.txt

```
### 3. Start the Flask server

```bash
python server/server.py
```
### 4. Run the UI

Open client/app.html in your browser to access the frontend UI.

### 5. Predict the house price
Fill in the details (Square feet, BHK, Bathroom, Location) and click "Estimate Price" to get the estimated house price.


## Model Evaluation
The models were evaluated based on their accuracy and performance. Several regression techniques were applied, including:
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**

The following key metrics were used for evaluation:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-Squared Value**

Based on these metrics, the final chosen model demonstrated high accuracy in predicting house prices in Bangalore.

## UI
The frontend interface allows users to input the following property details:
- Area (in square feet)
- Number of Bedrooms (BHK)
- Number of Bathrooms
- Location

Once the user clicks the "Estimate Price" button, the system calculates and displays the estimated house price in Lakhs.

![UI Preview](https://github.com/Adhoni/Real-Estate-Price-Prediction-Website/blob/master/BHP_website.PNG)

## Future Work
To further enhance the model, the following improvements can be made:
- **Adding more features** such as property age, amenities, etc., to improve prediction accuracy.
- **Expanding the dataset** to include more recent and diverse data points.
- **Deployment** of the project on cloud platforms like AWS or GCP for broader accessibility.
