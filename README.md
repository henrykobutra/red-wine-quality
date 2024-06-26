# Wine Quality Prediction

## Description

This project aims to predict the quality of wine based on various chemical properties using supervised learning techniques. The dataset used for this analysis is the Wine Quality dataset from the UCI Machine Learning Repository. Two machine learning models, Random Forest Regressor and Gradient Boosting Regressor, are applied to the dataset to compare their performance.

## Dataset

The dataset used in this project is the Wine Quality dataset, which includes the following features:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Installation

To run this project locally, you need to have Python installed. Follow the steps below to set up your environment:

1. Clone this repository:

   ```sh
   git clone https://github.com/henrykobutra/red-wine-quality.git
   cd wine-quality-prediction

    ```

2. Create and activate a virtual environment (optional but recommended):

    ```sh
    python3 -m venv venv
    source venv/bin/activate

    ```

3. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    
    ```

## Usage

1. Start Jupyter Notebook:

   ```sh
   jupyter notebook

   ```

2. Open the `Redwine ML Model.ipynb` notebook and run the cells to execute the analysis.

## Acknowledgements

- The dataset used in this project is from the UCI Machine Learning Repository.
- This project was inspired by the need to explore and compare different regression models for predictive analysis.
