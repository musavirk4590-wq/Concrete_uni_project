# Concrete_uni_project
My Machine learning project done in university 
# Concrete Compressive Strength Prediction

A machine learning project to predict the compressive strength of concrete based on its constituent ingredients. This was completed as part of university coursework.

## About The Project

Concrete is a crucial material in construction, and its compressive strength is a key indicator of its quality and durability. This project aims to build a machine learning model that can accurately predict the final compressive strength of concrete based on the quantities of its components (cement, slag, ash, water, etc.) used in the mixture.

Predicting strength accurately can help optimize concrete mixtures, reduce waste, and ensure structural integrity.

This project demonstrates the standard workflow of a regression problem in data science:
* Data loading and exploration using Pandas.
* Splitting data into training and testing sets using Scikit-learn.
* Training and comparing different regression models (Linear Regression, Random Forest Regressor).
* Evaluating model performance using metrics like R-squared.

## Skills Showcased

* **Python**
* **Pandas**
* **Scikit-learn**
* **Machine Learning (Regression)**
* **Model Evaluation**
* **Jupyter Notebook**

## Key Findings

* Both Linear Regression and Random Forest models were trained to predict concrete compressive strength.
* The Random Forest Regressor achieved a significantly higher R-squared score on the test set, indicating it provided a better fit to the data compared to the Linear Regression model in this case.
* *(Optional: Add specific R-squared scores here)*

## How to Run

1.  Clone this repository.
2.  Install the required libraries:
    ```bash
    pip install pandas scikit-learn jupyter
    ```
3.  Launch Jupyter Notebook and open the `.ipynb` file.
    ```bash
    jupyter notebook
    ```
