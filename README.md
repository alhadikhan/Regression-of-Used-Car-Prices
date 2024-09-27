# Regression of Used Car Prices

This repository contains a machine learning project aimed at predicting the prices of used cars based on various features. The project leverages data preprocessing, feature engineering, and regression modeling to deliver accurate price predictions.

## Project Overview

The primary goal of this project is to develop a predictive model for used car prices using a variety of regression techniques. The dataset includes various features such as car brand, model, year, mileage, fuel type, and more.

## Models Used

In this project, multiple regression models were implemented and evaluated, including:

1. **Gradient Boosting Regressor (GBR)**: The best-performing model, which outperformed all other regression techniques in predicting used car prices.
2. **Neural Network Regressor (MLPRegressor)**: A feedforward neural network used for regression, with hyperparameter tuning for optimization.
3. **Linear Regression**: Implemented using cuML for GPU acceleration to evaluate its performance on the dataset.
4. **Lasso Regression**: Utilized with hyperparameter tuning to improve performance and assess feature importance.
5. **Random Forest Regressor**: Employed for its ensemble learning capabilities and feature importance analysis.
6. **Support Vector Machine (SVM)**: Applied for regression tasks to explore its predictive power.
7. **K-Nearest Neighbors (KNN)**: Used as a comparison model to evaluate performance against other algorithms.

## Key Findings

- The **Gradient Boosting Regressor (GBR)** consistently outperformed other models, demonstrating superior accuracy in predicting used car prices.
- Hyperparameter tuning was crucial for optimizing model performance, particularly for the neural network and Lasso regression models.

## Getting Started

1. Clone the repository: 
   ```bash
   git clone https://github.com/yourusername/Regression-of-Used-Car-Prices.git

   cd Regression-of-Used-Car-Prices
2. Install the required packages:

pip install -r requirements.txt
## Usage
Prepare your dataset and place it in the specified directory.
Run the Jupyter Notebook (Used_Car_Price_Prediction.ipynb) to execute the data preprocessing, model training, and prediction steps.
The final predictions will be saved in a CSV file for submission.
## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

You can copy and paste this into your `README.md` file in your GitHub repository. Make sure to replace `yourusername` with your actual GitHub username in the installation section.
