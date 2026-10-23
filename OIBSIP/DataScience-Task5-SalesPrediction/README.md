# Task 5: Sales Prediction Using Machine Learning

## Project Overview
This project builds regression models to predict product sales based on advertising expenditure across TV, Radio, and Newspaper channels.

## Objective
To explore the relationship between advertising expenditure and sales, train regression models, and compare their predictive performance.

## Dataset
The dataset contains advertising expenditure for TV, Radio, and Newspaper, along with the corresponding Sales values.

**Dataset source:** [Advertising Dataset — Kaggle](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded and inspected the dataset.
2. Checked missing values and duplicate records.
3. Performed exploratory data analysis using descriptive statistics and pairplots.
4. Created scatter plots to examine each advertising channel's relationship with sales.
5. Visualized feature correlations using a heatmap.
6. Split the data into training and testing sets.
7. Trained Linear Regression and Random Forest Regression models.
8. Evaluated both models using MAE, RMSE, and R² score.
9. Analyzed residuals, regression coefficients, and feature importance.

## Model Evaluation Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.461 | 1.782 | 0.899 |
| Random Forest | 0.620 | 0.769 | 0.981 |

Random Forest performed better than Linear Regression on the selected test split, producing lower prediction errors and a higher R² score.

## Screenshots
The model evaluation table, feature-importance chart, correlation heatmap, and residual plot are available in the `screenshots/` folder.

## Conclusion
This project demonstrates how regression models can be used to predict sales from advertising expenditure. Comparing model metrics and analyzing feature importance helps assess predictive performance and understand the contribution of different advertising channels.
