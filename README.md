                                            Hyperparameter Tuning for NLP using GridSearchCV & RandomizedSearchCV
Project Overview

This project demonstrates how to improve the performance of a Natural Language Processing (NLP) model using Hyperparameter Tuning techniques. The goal is to optimize machine learning models for better text classification accuracy.

The project uses a text dataset (Spam Detection / Email Classification) and applies preprocessing, TF-IDF vectorization, baseline model training, and parameter optimization using:

GridSearchCV (Exhaustive Search)
RandomizedSearchCV (Efficient Search)

Objectives
Train a baseline NLP model.
Apply hyperparameter tuning techniques.
Compare model performance before and after tuning.
Use multiple machine learning models.
Visualize accuracy comparison.
Save the best trained model.


Technologies Used
Python
Pandas
NumPy
Scikit-learn
NLTK
Matplotlib
Joblib


Accuracy Comparison Graph

The project also generates a bar chart comparing accuracy of:

Naive Bayes
Logistic Regression
SVM


Model Saving

Best trained model is saved using:
joblib.dump(best_model, "best_model.pkl")

Key Learnings
NLP Text Preprocessing
TF-IDF Vectorization
Model Training
Hyperparameter Optimization
Cross Validation
Accuracy Comparison
Model Deployment Basics

Future Improvements
Use larger real-world datasets
Deploy using Flask / Streamlit
Add Deep Learning Models
Improve UI for prediction system
