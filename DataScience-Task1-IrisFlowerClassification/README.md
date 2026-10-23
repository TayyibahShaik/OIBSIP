# Task 1: Iris Flower Classification

## Project Overview
This project uses machine learning classification algorithms to predict the species of an iris flower based on its sepal and petal measurements.

## Objective
To explore the Iris dataset, visualize the relationships between flower measurements, and build classification models to predict flower species.

## Dataset
The Iris dataset contains 150 samples, four numerical features, and three flower species: Setosa, Versicolor, and Virginica.

**Dataset source:** [Scikit-learn Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded and inspected the Iris dataset.
2. Checked data types and missing values.
3. Performed exploratory data analysis (EDA).
4. Visualized species distributions and feature relationships.
5. Split the data into training and testing sets.
6. Standardized the features.
7. Trained Logistic Regression and K-Nearest Neighbors (KNN) models.
8. Evaluated model performance using classification metrics and confusion matrices.

## Models and Results
Both Logistic Regression and KNN achieved **100% accuracy on the selected test split**. Precision, recall, and F1-score were also 1.00 for both models.

These results apply to this particular train-test split and do not guarantee the same performance on every dataset.

## Screenshots
Project visualizations and model evaluation screenshots are available in the `screenshots/` folder.

## Conclusion
This project demonstrates how classification algorithms can be used to predict iris flower species from numerical measurements and how visualization and evaluation metrics help assess model performance.
