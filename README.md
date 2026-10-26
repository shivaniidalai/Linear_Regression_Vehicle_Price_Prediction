# Vehicle Selling Price Prediction Using Linear Regression

## Project Overview

This project predicts the selling price of vehicles using Machine Learning.

A **Linear Regression** model is used to learn the relationship between vehicle features and their selling price.

## Dataset

The dataset contains vehicle information such as:

* Year
* Make
* Model
* Trim
* Body
* Transmission
* Condition
* Odometer
* Color
* Interior
* Seller
* MMR
* Selling Price

The target variable is **sellingprice**.

## Data Preprocessing

The project includes:

* Handling missing values
* Selecting useful features
* Removing unnecessary columns
* Preparing categorical and numerical data
* Splitting the data for machine learning

Some columns such as `vin`, `saledate`, and `state` are removed during preprocessing.

## Machine Learning Model

The main algorithm used in this project is:

**Linear Regression**

The model is trained to predict the selling price of a vehicle based on its available features.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Feature-engine
* Jupyter Notebook / Google Colab

## Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Train/Test Split
   ↓
Linear Regression
   ↓
Price Prediction
   ↓
Model Evaluation
```

## How to Run

1. Download or obtain the required vehicle dataset.
2. Open the Jupyter Notebook or Google Colab.
3. Upload the dataset.
4. Run the notebook cells from beginning to end.

## Future Improvements

* Try advanced regression algorithms
* Perform better feature engineering
* Compare multiple machine learning models
* Improve prediction accuracy
* Deploy the model as a web application

## Project Type

**Machine Learning | Regression | Vehicle Price Prediction**
