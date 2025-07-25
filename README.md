# TechLabs Multivariate Linear Regression Project

This repository contains a project focused on understanding and implementing multivariate linear regression using `scikit-learn`, building upon concepts often introduced in beginner-friendly tutorials like those found on DataCamp. Beyond a basic implementation, this project delves into crucial aspects of robust regression modeling and rigorous testing of linear regression assumptions.

## Project Goal

The primary goal of this project is to:
* Demonstrate the application of multivariate linear regression.
* Perform an initial Exploratory Data Analysis (EDA) to understand the dataset characteristics.
* Thoroughly test the key assumptions of linear regression, which are vital for validating model reliability.
* Provide a clear, commented codebase for educational purposes.

## Dataset

This project utilizes the **California Housing Dataset**, a widely-used dataset in machine learning for regression tasks. It contains features describing various aspects of housing districts in California and aims to predict the median house value in those districts.

## Features & Analysis

The project includes the following key components:

1.  **Exploratory Data Analysis (EDA):**
    * Initial data inspection and summary statistics.

2.  **Multivariate Linear Regression:**
    * Implementation of a linear regression model using `sklearn.linear_model.LinearRegression`.
    * Training the model on multiple features to predict the target variable.

3.  **Linear Regression Assumptions Testing:**
    The project includes explicit checks for the fundamental assumptions of linear regression:
    * **Independence of Data Points:** Discussed conceptually, as it relates to data collection.
    * **Linear Dependency between Features and Target:** Verified visually using scatter plots (from EDA) and correlation analysis.
    * **Normality of Residuals:** Checked using:
        * Histogram of residuals with a Kernel Density Estimate (KDE).
    * **Constant Variance of Residuals (Homoscedasticity):** Assessed using:
        * Scatter plot of residuals versus predicted values.

## Technologies Used

* Python 3.x
* `scikit-learn`
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`

## Setup and Installation

To get this project up and running locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/DerMoehre/techlabs-regression.git](https://github.com/DerMoehre/techlabs-regression.git)
    cd techlabs-regression
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    # .\venv\Scripts\activate
    # On macOS/Linux:
    # source venv/bin/activate
    ```
3.  **Install the required packages:**
    Since this project uses `pyproject.toml` for dependency management, you can install all dependencies and the project itself in editable mode:
    ```bash
    pip install -e .
    ```

## Usage

1.  **If using a Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Then, open and run the `regression_analysis.ipynb` (or similar) notebook cell by cell.

The output (plots, test results) will be displayed in your console

## Contributions

Feel free to fork this repository, open issues, or submit pull requests. Any contributions that enhance the analysis, improve code quality, or add further insights are welcome.