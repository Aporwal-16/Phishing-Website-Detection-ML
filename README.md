Phishing Website Detection Using Machine Learning
Project Overview

This project uses machine learning techniques to classify websites as phishing or legitimate based on extracted website features.

The objective is to explore how machine learning can help identify potentially fraudulent websites and support cybersecurity applications.

Dataset
Source: UCI Machine Learning Repository
Dataset: Phishing Websites
Approximately 11,000 website records
30 input features
Target labels:
-1: Phishing
1: Legitimate

Dataset: https://archive.ics.uci.edu/dataset/327/phishing+websites

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
Machine Learning Algorithms

Three classification algorithms were implemented:

Decision Tree Classifier
Logistic Regression
Random Forest Classifier
Project Workflow
Dataset collection and loading
Exploratory Data Analysis
Data visualisation
Training and testing data split
Model training
Performance evaluation
Model comparison
Feature importance analysis
Decision Tree visualisation
Model saving
Evaluation Metrics

The models are evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix

Actual performance results are available in the project notebook.

Key Features
Comparison of three machine learning algorithms.
Visualisation of phishing and legitimate website records.
Feature importance analysis.
Confusion matrix analysis.
Decision Tree visualisation.
Saved trained models.
Limitations

The project uses pre-extracted website features from the UCI dataset. It does not directly analyse arbitrary URLs entered by users or guarantee that a website is safe.

Future Scope
Develop a URL feature extraction module.
Build a simple interface for user input.
Evaluate additional classification algorithms.
Explore real-time phishing detection.
Author

Developed as a beginner-level Machine Learning and Cybersecurity project.
