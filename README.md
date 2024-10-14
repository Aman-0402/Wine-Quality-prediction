# Wine-Quality-prediction
Developed a wine quality prediction model using machine learning techniques like Logistic Regression, SVM, and Random Forest, with ensemble methods (AdaBoost, Gradient Boosting). The model, built with Python, Pandas, Scikit-learn, and Flask, was deployed as a web app allowing users to input wine characteristics for quality predictions.

# Wine Quality Prediction Project

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Development](#model-development)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Feature Engineering](#feature-engineering)
- [Ensemble Methods](#ensemble-methods)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to predict the quality of wine based on various chemical properties. By utilizing machine learning techniques, we can create a model that accurately predicts wine quality ratings, which can be valuable for winemakers and enthusiasts alike.

## Data Description
The dataset used for this project consists of various chemical properties of red and white wine, along with their respective quality ratings. The key features include:
- Alcohol
- Sulphates
- Total Acidity
- Fixed Acidity
- Density
- pH
- Citric Acid
- Residual Sugar

## Project Structure

wine_quality_prediction/ │ ├── data/ # Directory for datasets │ └── wine_quality.csv # Wine quality dataset │ ├── notebooks/ # Jupyter notebooks for exploratory analysis │ └── wine_quality_analysis.ipynb │ ├── src/ # Source code for model training and evaluation │ ├── feature_engineering.py │ ├── model_training.py │ ├── hyperparameter_tuning.py │ └── ensemble_methods.py │ ├── requirements.txt # Required packages └── README.md # Project documentation


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/wine_quality_prediction.git
   cd wine_quality_prediction
2. Install the required packages:
   pip install -r requirements.txt

## Usage
Run the Jupyter notebook for exploratory data analysis:

jupyter notebook notebooks/wine_quality_analysis.ipynb

Train the model by executing the relevant Python scripts in the src/ directory.

## Model Development
The project follows several steps for model development:

1. Data preprocessing
2. Feature scaling
3. Model training with various algorithms (Logistic Regression, SVM, Random Forest)
4. Model evaluation using metrics like accuracy, precision, recall, and F1 score.

## Hyperparameter Tuning
Hyperparameter tuning is performed using methods like Randomized Search and Grid Search to optimize model performance.

## Feature Engineering
Feature engineering is crucial in improving model predictions. We created new features such as:

 * Alcohol-to-Sulphates Ratio
 * Acidity Difference
 * Density-Alcohol Interaction

## Ensemble Methods
Ensemble methods such as Bagging, Boosting, and XGBoost are implemented to enhance predictive performance by combining multiple models.

## Deployment
Once a satisfactory model is achieved, it will be deployed as a web application using Flask. Users can input wine characteristics and receive quality predictions.

## Contributing
   Aman Raj
Contributions are welcome! Please open an issue or submit a pull request.
