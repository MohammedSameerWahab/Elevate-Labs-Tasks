# Titanic Dataset: Data Preprocessing

This repository contains a Jupyter Notebook that demonstrates a comprehensive data preprocessing workflow on the classic Titanic dataset. The goal is to clean and transform the raw data into a format suitable for machine learning modeling.

## 📋 Project Overview

The notebook walks through the essential steps required to handle common data quality issues, ensuring the dataset is robust and reliable for analysis and model training.

## 🚀 Preprocessing Steps Covered

The following data cleaning and preparation techniques are implemented:

1.  **Data Exploration**: Initial loading of the dataset and inspection of its structure, data types, and basic statistics.
2.  **Handling Missing Values**: Imputing missing data for numerical columns (like `age` using the median) and categorical columns (like `embarked` using the mode). The `deck` column is dropped due to a high percentage of missing values.
3.  **Categorical Feature Encoding**: Converting categorical features (e.g., `sex`, `class`, `embarked`) into numerical format using one-hot encoding.
4.  **Feature Scaling**: Standardizing numerical features such as `age` and `fare` to have a mean of 0 and a standard deviation of 1 using `StandardScaler`.
5.  **Outlier Detection and Removal**: Visualizing outliers in `age` and `fare` using boxplots and removing them based on the Interquartile Range (IQR) method.

## 🛠️ How to Run

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3.  Ensure you have the required libraries installed:
    ```bash
    pip install pandas numpy seaborn scikit-learn matplotlib jupyterlab
    ```
4.  Launch Jupyter Lab or Jupyter Notebook and open the `.ipynb` file.
    ```bash
    jupyter lab
    ```

## 📚 Libraries Used

* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Seaborn & Matplotlib**: For data visualization.
* **Scikit-learn**: For feature scaling (`StandardScaler`).
