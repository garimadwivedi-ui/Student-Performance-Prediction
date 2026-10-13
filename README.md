# Student-Performance-Prediction
Student Performance Prediction using Python and Machine Learning
About the Project

This project uses machine learning to predict students' final grades based on student-related information. It includes data analysis, visualization, model training, and performance evaluation.

Tools and Technologies

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

Dataset

The project uses the Student Performance dataset ("student-mat.csv"), containing 395 student records and 33 columns.

Project Steps

1. Data loading and exploration
2. Missing value and duplicate checking
3. Exploratory Data Analysis (EDA)
4. Data preprocessing and encoding
5. Train-test split
6. Linear Regression model
7. Random Forest Regression model
8. Model evaluation and comparison

Results

Model| MAE| RMSE| R² Score
Linear Regression| 1.6467| 2.3784| 0.7241
Random Forest| 1.1734| 1.9666| 0.8114

Conclusion

Random Forest performed better than Linear Regression on the test dataset. The analysis also showed a strong relationship between previous grades (G1 and G2) and the final grade (G3).

Note

Predictions are estimates based on the available dataset and are not guaranteed outcomes.
