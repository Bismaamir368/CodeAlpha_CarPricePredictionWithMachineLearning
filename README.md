# Car Price Prediction باستخدام Machine Learning

This project predicts the selling price of a car using a Linear Regression model. The model is trained on historical car data and allows users to input car details to estimate its price.

---

## Project Overview

The objective of this project is to:
- Build a machine learning model to predict car prices
- Perform data cleaning and preprocessing
- Encode categorical variables
- Evaluate model performance
- Allow user input for real-time price prediction

---

## Dataset

- File Name: `car data.csv`
- The dataset includes features such as:
  - Car name or brand
  - Year of purchase
  - Selling price
  - Present price
  - Kilometers driven
  - Fuel type
  - Transmission type
  - Number of previous owners

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Steps Performed

### 1. Import Libraries
Essential libraries for data processing, modeling, and visualization were imported.

### 2. Load Dataset
The dataset was loaded using Pandas and inspected using basic functions.

### 3. Data Cleaning
- Column names were standardized (lowercase and stripped)
- Missing values were identified and removed

### 4. Encoding Categorical Data
- Label Encoding was applied to all categorical columns
- Encoders were stored for later use during prediction

### 5. Feature Selection
- Target variable (`selling_price`) was selected
- Remaining columns were used as features

### 6. Train-Test Split
- Data was split into training and testing sets (80/20 ratio)

### 7. Model Training
- A Linear Regression model was trained on the dataset

### 8. Prediction
- Predictions were made on test data

### 9. Evaluation
The model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 10. Visualization
- Scatter plot comparing actual vs predicted prices
- A reference line showing perfect predictions

### 11. User Input Prediction
- Users can input car details manually
- Categorical inputs are selected via options
- Numerical inputs are entered directly or via ranges
- The model predicts the car price based on input

---

## Output

- Model performance metrics printed in console
- Graph comparing actual vs predicted values
- Final predicted car price displayed in lakhs (formatted to two decimal places)

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
