# Data-cleaning
Titanic Survival Prediction  This project implements a machine learning workflow to predict Titanic survival. It covers data loading, cleaning (handling missing values and outliers), and feature scaling, focusing on passenger features like class, sex, age, and fare to build a survival prediction model.



# Titanic Survival Prediction

This repository contains code for a machine learning project focused on predicting passenger survival on the Titanic. The goal is to demonstrate a basic data science workflow, including data loading, cleaning, and preparation for model training.

## Project Overview

The project utilizes the well-known Titanic dataset to predict whether a passenger survived the disaster based on features such as passenger class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, and embarkation point.

## Getting Started

### Prerequisites

*   Python 3.6+
*   Jupyter Notebook or Google Colab
*   Required Python libraries: pandas, numpy, scikit-learn, matplotlib

### Installation

1.  Clone this repository:
    ```bash
    git clone <repository_url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd titanic-survival-prediction
    ```
3.  Install the required libraries:
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```

### Usage

1.  Download the `Titanic-Dataset.csv` file and place it in the project directory.
2.  Open the notebook in Jupyter Notebook or Google Colab.
3.  Run the cells sequentially to perform data loading, cleaning, and preparation.

## Code Description

The notebook covers the following steps:

1.  **Data Loading:** Loading the `Titanic-Dataset.csv` into a pandas DataFrame.
2.  **Data Exploration:** Checking for duplicated data, examining data types and non-null counts.
3.  **Data Cleaning:**
    *   Dropping irrelevant columns (`Name`, `Ticket`, `Cabin`).
    *   Handling missing values by dropping rows with missing 'Embarked' data and imputing 'Age' with the mean.
4.  **Outlier Handling:** Identifying and removing outliers in the 'Age' column using the standard deviation method.
5.  **Feature Scaling:** Applying `MinMaxScaler` to numerical features.
6.  **Data Preparation:** Separating features (`X`) and the target variable (`Y`).

## Dataset

The dataset used is the classic Titanic dataset, available on platforms like Kaggle. It contains information about Titanic passengers and whether they survived.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

*   Kaggle for providing the dataset.
*   The open-source community for the powerful libraries used in this project.
