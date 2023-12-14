# Iris Flower Classification 

This project builds and compares machine learning models for iris flower classification based on petal and sepal dimensions.

## Problem Statement

We have a dataset containing measurements of different iris flower species (setosa, versicolor, and virginica). Our goal is to create a model that can accurately predict the species of a new iris flower based on its sepal length, sepal width, petal length, and petal width.

## Methods

This project employs two popular machine learning algorithms for classification :

* **Logistic Regression :** A linear model that estimates the probability of a data point belonging to a specific class.
* **K-Nearest Neighbors (KNN) :** A non-parametric algorithm that predicts the class of a new data point based on the majority vote of its K nearest neighbors in the training data. Different values of K (from 2 to 14) were tested to find the optimal performance.

## Evaluation

Model performance is evaluated using the following metrics :

* **Accuracy :** The percentage of correctly classified flower species.
* **ROC Curve & AUC :** Visualizes the trade-off between true positive rate and false positive rate, with higher AUC indicating better performance.

## Tools & Framework

This project leverages the following libraries :

* NumPy : Multi-dimensional array manipulation for data processing.
* Scikit-learn (SKLearn) : Machine learning algorithms and utilities.
* Pandas : Data analysis and manipulation.
* Matplotlib & Seaborn : Data visualization libraries.

## Results

* Logistic Regression achieved 95.5% accuracy.
* KNN with K=3 achieved 93.7% accuracy, demonstrating the impact of parameter tuning.
* ROC curves and AUC values provided insights into the strengths and weaknesses of each algorithm under different scenarios.

## Key Takeaways

* Logistic Regression provides a simple and interpretable model but may not capture complex relationships in the data.
* KNN can be effective with appropriate parameter tuning but can be sensitive to noise and outliers.
* Model selection and parameter tuning are crucial for optimal performance.

## Repository Contents

* 2020CHB1036_MA515.ipynb : Script containing code for data preprocessing, model building, evaluation, and visualization.
* IRIS.csv : CSV File containing the iris dataset.
* IRIS ML PROJECT : Documentation File for the project.
* ROC.png : ROC Curve for Logistic Regression and KNN models.
* README.md : This file (you're reading it now..!).

## Next Steps

* Explore feature engineering techniques to potentially improve accuracy.
* Perform hyperparameter tuning for further optimization of both models.
* Investigate other machine learning algorithms and compare their performance.
* Consider deploying the model in a real-world application.

## Contact

Feel free to reach out for any questions, feedback, or suggestions regarding this project.

## Enjoy exploring the code and experimenting with your own ideas..!
