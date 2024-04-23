# Credit Card Churn Prediction

This repository contains a project that demonstrates how to predict customer churn in a credit card company using a machine learning model. The project uses the "Churn_Modeling" dataset from Kaggle and is implemented in a Jupyter notebook.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Exploration and Preprocessing](#data-exploration-and-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project uses machine learning models to predict whether a customer will churn (leave the company) based on their historical data. The project involves exploring the dataset, preprocessing the data, training and evaluating models, and visualizing the results. This is a great opportunity to learn about customer retention strategies and how machine learning can be used to inform business decisions.

## Dataset

The "Churn_Modeling" dataset used in this project is available from [Kaggle](https://www.kaggle.com/adammaus/predicting-churn). The dataset contains information about customers such as:

- Credit score
- Geography
- Gender
- Age
- Balance
- Number of products
- Tenure
- Estimated salary
- Churn status (target variable)

## Data Exploration and Preprocessing

The project includes:

- Data exploration to understand the features and their distributions.
- Data preprocessing such as handling missing values, encoding categorical variables, and feature scaling.

## Model Training and Evaluation

The project uses machine learning models such as logistic regression, decision trees, random forest, or support vector machines to train on the dataset and predict customer churn.

- The notebook contains code to train and tune the models using cross-validation and hyperparameter tuning.
- The models are evaluated using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.

## Usage

To run this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/DipeshK47/Creditcard_Churn_Prediction.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd creditcard-churn-prediction
    ```

3. **Install the required dependencies**:

    You can create a virtual environment and install the dependencies using the provided `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Open the Jupyter notebook**:

    Use a Jupyter notebook environment to open and run the provided notebook.

## Results

The notebook includes visualizations and metrics to showcase the model's performance in predicting customer churn. The results provide insights into which features are most important for predicting churn and how well the model performs.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a branch for your feature or bug fix.
3. Commit your changes.
4. Push the branch and open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
