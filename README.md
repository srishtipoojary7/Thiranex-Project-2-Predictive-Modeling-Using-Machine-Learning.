# Predictive Modeling Using Machine Learning

## Project Overview

This project uses machine learning classification algorithms to predict Iris flower species from flower measurements.

## Objectives

* Explore the Iris dataset.
* Prepare features and target labels.
* Train machine learning classification models.
* Evaluate and compare model accuracy.
* Visualize model performance.

## Dataset

The Iris dataset contains 150 samples, four numerical features, and three flower species:

* Setosa
* Versicolor
* Virginica

## Machine Learning Models

1. Decision Tree Classifier
2. Random Forest Classifier

## Results

| Model         | Test Accuracy |
| ------------- | ------------: |
| Decision Tree |        93.33% |
| Random Forest |        90.00% |

The Decision Tree achieved higher accuracy on this particular test split.

## Visualizations

* `model_accuracy_comparison.png` — Compares the accuracy of both models.
* `confusion_matrix.png` — Shows the Decision Tree's classification results.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required libraries if they are not already installed.
3. Open `Predictive_Modeling_ML_Project.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.

## Conclusion

The Decision Tree achieved 93.33% accuracy, while the Random Forest achieved 90.00% accuracy on the test dataset. The Decision Tree performed better in this experiment.

These results are based on one train-test split, so further validation could provide a more reliable comparison.
