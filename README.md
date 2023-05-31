# Advertising vs Sales Prediction

This repository contains code for predicting sales based on advertising data using various regression models. The goal is to analyze the relationship between advertising expenditures and sales and build models that can accurately predict sales based on the given advertising data.

## Dataset

The dataset used in this project consists of records of advertising expenditures and corresponding sales. It includes features such as TV advertising budget, radio advertising budget, newspaper advertising budget, and the resulting sales. The dataset is provided in CSV format, with each row representing a specific observation of advertising and sales data.

Ensure that your CSV file follows the required format with labeled advertising and sales data. Perform any necessary data cleaning, preprocessing, and feature scaling before training the regression models.

## Regression Models

This repository includes implementations of several regression models to predict sales based on the advertising data. The following regression models are available:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression

Feel free to explore and compare the performance of these models to find the best fit for your data.

## Usage

To use the advertising vs sales prediction models, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/Advertising-Vs-Sales-Prediction.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Prepare your data:

   - Place your CSV file with advertising and sales data in the repository.
   - Ensure that your CSV file has the necessary columns for advertising features (e.g., TV budget, radio budget, newspaper budget) and the target variable (sales).
   - Perform any necessary data preprocessing, cleaning, and feature scaling.

4. Run the Jupyter Notebook:

   - Open the Jupyter Notebook `advertising_sales_prediction.ipynb` in your preferred environment (Jupyter Notebook, JupyterLab, Google Colab, etc.).
   - Update the notebook with the necessary path to your data CSV file.
   - Follow the instructions and comments provided in the notebook to explore the data, train the regression models, and evaluate their performance.
   - The notebook will guide you through the process of training and evaluating each regression model using the advertising and sales data.

5. Predicting Sales:

   - Use the trained models to make sales predictions based on new advertising data.
   - Update the input data with the advertising budgets for the new scenario you want to predict sales for.
   - The notebook provides code to load the trained models, preprocess the input data, and output the predicted sales.

## Contributing

Contributions to improve the advertising vs sales prediction models or explore additional regression models are welcome. If you encounter any issues or have suggestions, please open an issue or submit a pull request.
