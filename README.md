Gender Identification Classification
This repository contains a Jupyter Notebook (gender_classification.ipynb) that implements a gender identification classification problem using supervised machine learning, as part of an Artificial Intelligence assignment. The project trains and compares two classification algorithms—Logistic Regression and Random Forest—on a synthetic dataset to predict gender (male/female) based on features like height, weight, and voice pitch. The performance is evaluated using accuracy.
Project Overview
The goal is to build, train, and evaluate two machine learning models to classify individuals as male or female using physical attributes. The dataset is synthetic, and the models are compared based on their accuracy scores.
Dataset

Source: Synthetic dataset (created due to no specific dataset provided).
Features:
Height (cm): Males ~ N(175, 8), Females ~ N(162, 7)
Weight (kg): Males ~ N(80, 10), Females ~ N(60, 8)
Voice Pitch (Hz): Males ~ N(120, 20), Females ~ N(200, 25)


Target: Gender (0 for male, 1 for female)
Size: 1000 samples (500 male, 500 female)
Split: 80% training, 20% testing

Algorithms

Logistic Regression: A linear model for binary classification.
Random Forest: An ensemble model using multiple decision trees for robust predictions.

Results

Logistic Regression Accuracy: 0.94
Random Forest Accuracy: 0.96
Conclusion: Random Forest performs slightly better, likely due to its ability to capture non-linear relationships and reduce overfitting.

Prerequisites
To run the Jupyter Notebook, you need:

Python 3.x
Jupyter Notebook
Required libraries: numpy, pandas, scikit-learnYou can install the dependencies using:

pip install numpy pandas scikit-learn jupyter

How to Run

Clone this repository:git clone https://github.com/[your-username]/gender-classification.git
cd gender-classification


Launch Jupyter Notebook:jupyter notebook


Open gender_classification.ipynb in the Jupyter interface.
Run all cells to execute the code and view the results.
The notebook includes Markdown cells explaining each step and code cells for data creation, model training, and evaluation.

File Structure

gender_classification.ipynb: Jupyter Notebook with the complete code and explanations.
README.md: This file.

Assumptions

A synthetic dataset was used since no specific dataset was provided.
Features were standardized (mean 0, variance 1) for better model performance.
Random seed (42) ensures reproducibility of results.

Usage

Run the notebook to see the data creation, model training, and accuracy comparison.
Modify the dataset loading section if using a different dataset (e.g., from Kaggle or UCI).
The notebook prints accuracy scores and a comparison of the two models.

Sample Output
Logistic Regression Accuracy: 0.94
Random Forest Accuracy: 0.96
Random Forest performed better.

License
This project is licensed under the MIT License.
Acknowledgments

Built for an Artificial Intelligence course assignment.
Uses scikit-learn for machine learning models.

