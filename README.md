# Car Price Prediction

## Objective

How do you evaluate the **apt price for a second-hand car**?

The price is determined based on various specifications such as:
- The number of years the car has been used
- The type of fuel it uses (e.g., Petrol, Diesel, CNG)
- The number of kilometers it has run, and much more.

In this case study, the goal is to create a **machine learning model** that can predict the price of a car based on its specifications.

Below, I will walk through the step-by-step approach to building a **Machine Learning predictive model** for this scenario.

---

## Case Study Flow

1. **Reading the Data in Python**  
   The first step is to load the dataset into Python using libraries like pandas.

2. **Defining the Problem Statement**  
   The main objective is to predict the price of second-hand cars based on their specifications like the age, fuel type, kilometers driven, and other features.

3. **Identifying the Target Variable**  
   The target variable is **Price**, which is the value we are trying to predict.

4. **Exploring the Distribution of the Target Variable**  
   We will analyze the distribution of the target variable (Price) to understand its range and check for any skewness.

5. **Basic Data Exploration**  
   Perform an initial exploration of the data to spot any obvious issues or patterns.

6. **Rejecting Useless Columns**  
   Remove columns that do not add value for the prediction of the car price.

7. **Visual Exploratory Data Analysis (EDA)**  
   Use **Histograms** and **Bar charts** to visualize the data and its distribution.

8. **Feature Selection Based on Data Distribution**  
   Select relevant features based on how they are distributed and their relationship to the target variable.

9. **Outlier Treatment**  
   Detect and treat any outliers in the data, as they might skew the model.

10. **Missing Values Treatment**  
    Handle missing data by either imputing the missing values or removing problematic rows/columns.

11. **Visual Correlation Analysis**  
    Use tools like **heatmaps** to visualize the correlation between features and the target variable.

12. **Statistical Correlation Analysis (Feature Selection)**  
    Perform statistical analysis to evaluate how each feature is related to the target variable and select important predictors.

13. **Converting Data to Numeric for Machine Learning**  
    Convert categorical features into numeric values using techniques such as **one-hot encoding** or **label encoding** to make the data suitable for ML models.

14. **Sampling and K-Fold Cross Validation**  
    Split the dataset into training and testing sets, and use **K-fold cross-validation** to evaluate model performance.

15. **Trying Multiple Regression Algorithms**  
    Experiment with different regression algorithms, such as **Linear Regression**, **Random Forest Regressor**, **XGBoost**, etc., to predict car prices.

16. **Selecting the Best Model**  
    Compare the performance of different models and choose the one that performs the best based on accuracy and error metrics.

---

## Data Details

- **Dataset**: The data is stored in the file **"CarPricesData.csv"**, which contains **1435 car price records**.
- You can also download the dataset required for this case study in Readme

### Data Description
Here is the business meaning of each column in the data:

- **Price**: The price of the car in dollars.
- **Age**: The age of the car in months.
- **KM**: The number of kilometers the car has been used.
- **FuelType**: The type of fuel the car uses (e.g., Petrol, Diesel, CNG).
- **HP**: The horsepower of the car.
- **MetColor**: Whether the car has a metallic color or not.
- **Automatic**: Whether the car has automatic transmission or not.
- **CC**: The engine size of the car.
- **Doors**: The number of doors in the car.
- **Weight**: The weight of the car.

----

## About Me

**Vishal Kumar**
- [GitHub](https://github.com/VishalKumar-GitHub/Car-Price-Prediction-)

📫 **Follow me** on [Xing](https://www.xing.com/profile/Vishal_Kumar055381/web_profiles?expandNeffi=true) | [LinkedIn](https://www.linkedin.com/in/vishal-kumar-819585275/)
