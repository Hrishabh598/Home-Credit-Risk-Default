# Home Credit Default Risk Model

## Overview

This project aims to predict credit default risk for Home Credit clients using a combination of Principal Component Analysis (PCA) and a Random Forest Classifier. The prediction model is designed to assess the likelihood of default based on various features provided by Home Credit, such as client attributes, previous loan history, and other relevant financial information.

## Methodology

1. **Data Preprocessing**:
   - The dataset is cleaned and preprocessed to handle missing values, outliers, and categorical variables.
   - Feature engineering is performed to create new features or transform existing ones to enhance the predictive power of the model.

2. **Principal Component Analysis (PCA)**:
   - PCA is employed to reduce the dimensionality of the feature space while preserving most of the variability present in the data.
   - Dimensionality reduction helps in mitigating the curse of dimensionality and improving the computational efficiency of the model.

3. **Random Forest Classifier**:
   - Random Forest is chosen as the predictive model due to its ability to handle non-linear relationships and high-dimensional data.
   - The classifier is trained on the PCA-transformed features to learn the patterns and associations within the data.

4. **Model Evaluation**:
   - The performance of the model is evaluated using appropriate metrics such as accuracy.
   

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/home-credit-default-risk-model.git
    ```

2. Navigate to the project directory:

    ```bash
    cd home-credit-default-risk-model
    ```

## Contributors

- [Hrishabh Tiwari](https://github.com/Hrishabh598)

## Acknowledgements

- [Kaggle](https://www.kaggle.com/) for providing the dataset and inspiration for the project.
- Stack Overflow and various online resources for valuable insights and guidance.
