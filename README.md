# Bulldozer Price Prediction

This project is an end-to-end machine learning workflow for predicting the auction sale prices of bulldozers using data from the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/c/bluebook-for-bulldozers). The goal of the project is to demonstrate key steps in a machine learning pipeline: from data cleaning and feature engineering to model training and evaluation.

## Project Overview

The project follows these key steps:

1. **Problem Definition**:

    - How well can we predict the future sale price of bulldozers, given its features and historical data?

2. **Data**:
   Data can be dowloaded from [Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

    - The dataset contains information about bulldozer sales from 1989 to 2012. The data is provided by the Kaggle Bluebook for Bulldozers competition.
    - The datasets used:
        - `Train.csv`: Training data, covering sales through the end of 2011.
        - `Valid.csv`: Validation data, covering sales from January 1, 2012, to April 30, 2012.

3. **Evaluation**:

    - The model is evaluated using the **Root Mean Squared Log Error (RMSLE)** metric, which penalizes large differences between the actual and predicted sale prices.

4. **Features**:

    - The dataset contains various features such as machine configuration, auctioneer ID, sales date, and product size, which are used for training the model.

5. **Steps**:
    - Data loading and exploration.
    - Handling missing data.
    - Feature engineering, including date-time feature extraction and handling categorical variables.
    - Model training using various regression algorithms.
    - Model evaluation and improvement using hyperparameter tuning.

## Requirements

To run this project, you need the following Python packages:

-   `pandas`
-   `numpy`
-   `scikit-learn`
-   `matplotlib`
-   `seaborn`
-   `jupyter`
-   `joblib`

You can install the dependencies by running the following command:

````bash
pip install -r requirements.txt

---

### Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/aiwkz/bulldozer-price-prediction.git
    cd bulldozer-price-prediction
    ```

2. **Install the required libraries**:
   You can use the `requirements.txt` file to install the necessary Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook**:
   Run the following command to start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

4. **Run the Notebook**:
   Open the `end-to-end-bulldozer-price-prediction.ipynb` notebook in Jupyter and run the cells to reproduce the analysis.

---

### Usage

To use the project, you can interact with the data, models, and visualizations directly from the Jupyter Notebook. The notebook is well-documented, and explanations for each code block are provided.

---
````
