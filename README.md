

# Heart-Disease-Prediction

This project aims to predict the presence of heart disease based on a dataset containing various medical features. It utilizes the Logistic Regression algorithm for classification.

## Dataset

The dataset used in this project contains information about patients, including features such as age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, the slope of the peak exercise ST segment, number of major vessels colored by flourosopy, and thalassemia. The target variable is the presence or absence of heart disease (0: no heart disease, 1: heart disease).

The dataset consists of 303 instances and 14 input features.

## Requirements

To run the code, you need the following dependencies:

- Python 3.x
- pandas
- numpy
- scikit-learn

You can install the required packages using pip:

```
pip install pandas numpy scikit-learn
```

## Instructions

1. Download the code and dataset files.

2. Open the code in a Python development environment or Jupyter Notebook.

3. The dataset is loaded from the "heart_disease_data.csv" file into a pandas DataFrame.

4. Data exploration and preprocessing steps are performed, including checking for null values and basic statistics.

5. The target column is separated from the rest of the data, creating input features (x) and target variable (y).

6. The data is split into training and test sets using the train_test_split function from scikit-learn.

7. A Logistic Regression model is created and trained using the training data.

8. The model's performance is evaluated using the accuracy score metric on both the training and test datasets.

9. Finally, a prediction system is demonstrated using custom input values.

## Results

The trained model achieves an accuracy of approximately 85% on the training dataset and 82% on the testing dataset.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Feel free to use the code and dataset for research or educational purposes.

If you have any questions or suggestions, please feel free to contact me.

```
