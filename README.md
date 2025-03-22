# Holiday Package Prediction

## Problem Statement
"Trips & Travel.Com" company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering: Basic, Standard, Deluxe, Super Deluxe, and King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information.

The company is now planning to launch a new product, the Wellness Tourism Package. Wellness Tourism is defined as travel that allows the traveler to maintain, enhance, or kick-start a healthy lifestyle, and support or increase one's sense of well-being. This time, the company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

## Data Collection
The dataset is collected from [Kaggle](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction). The data consists of 20 columns and 4888 rows.

## Project Description
- Developed a machine learning model to predict holiday package purchases.
- Performed data cleaning and handled missing values.
- Conducted feature engineering to enhance model performance.
- Preprocessed data using `StandardScaler` and `OneHotEncoder`.
- Addressed class imbalance using ensemble techniques.
- Implemented and evaluated models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, XGBoost.
- Achieved optimal performance with Random Forest and XGBoost classifiers.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- XGBoost

## How to Run
1. Clone the repository.
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook Holiday_Package_Prediction.ipynb
    ```
