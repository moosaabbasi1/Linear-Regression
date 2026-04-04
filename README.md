#Linear Regression Analysis Project

This repository contains a collection of Jupyter notebooks demonstrating the application of Linear Regression using Python. The projects cover various real-world scenarios, ranging from simple salary predictions to complex multi-feature insurance cost estimations.

**Project Structure**

The project is divided into three main notebooks, each focusing on a different dataset and regression complexity:

**1. Simple Linear Regression (Salary Prediction)**

File: linear Regression 1.ipynb

Objective: Predict an employee's salary based on their years of experience.

Dataset: salary_data.csv.

Key Tasks:

Exploratory Data Analysis (EDA) and data visualization.

Implementation of StandardScaler for feature scaling.

Model training using sklearn.linear_model.LinearRegression.

Evaluation using Mean Squared Error (MSE) and R² Score.

2. Multiple Linear Regression (Petrol Consumption)
File: Linear Regression 2.ipynb

Objective: Analyze factors affecting petrol consumption, such as petrol tax, average income, and the percentage of the population with driver's licenses.

Dataset: petrol_consumption.csv.

Key Tasks:

Multivariate data analysis.

Feature selection and correlation checks.

Model performance tracking using MAE (Mean Absolute Error) and R².

3. Advanced Feature Engineering (Insurance Cost Prediction)
File: Linear Regression 3.ipynb

Objective: Predict medical insurance charges based on patient attributes like age, sex, BMI, smoking status, and region.

Dataset: insurance.csv.

Key Tasks:

Comprehensive EDA with Seaborn and Matplotlib.

Feature Engineering: Categorizing BMI into specific classifications (e.g., obese) and handling categorical variables.

Data cleaning (handling nulls and duplicates).

Exporting the finalized engineered dataset for modeling.

Requirements
To run these notebooks, you will need the following Python libraries:

Pandas: Data manipulation and analysis.

NumPy: Numerical computing.

Scikit-Learn: Machine learning model implementation and evaluation.

Matplotlib / Seaborn: Data visualization.

You can install the dependencies using pip:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn
How to Use
Clone this repository.

Ensure the required .csv files mentioned in each notebook are in the same directory (or update the file paths within the notebooks).

Open the notebooks in Jupyter Lab or VS Code to step through the analysis.

Evaluation Metrics
The models in this repository are primarily evaluated using:

R-Squared (R²): To determine the goodness of fit.

Mean Squared Error (MSE): To measure the average squared difference between estimated values and the actual value.

Mean Absolute Error (MAE): To understand the average magnitude of errors in predictions.
