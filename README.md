Phishing Website Detection Using Machine Learning

1. Project Overview

This project uses machine learning techniques to classify websites as Phishing or Legitimate based on extracted website features.

The objective is to explore how machine learning can help identify potentially fraudulent websites and support cybersecurity applications.

2. Dataset

- Source: UCI Machine Learning Repository
- Dataset: Phishing Websites
- Records: Approximately 11,000
- Features: 30
- Target Labels:
  - "-1" – Phishing
  - "1" – Legitimate

"Dataset Link" (https://archive.ics.uci.edu/dataset/327/phishing+websites)

3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

4. Machine Learning Algorithms

Three classification algorithms were implemented:

1. Decision Tree Classifier
2. Logistic Regression
3. Random Forest Classifier

5. Project Workflow

1. Dataset collection and loading
2. Exploratory Data Analysis (EDA)
3. Data visualisation
4. Training and testing data split
5. Model training
6. Performance evaluation
7. Model comparison
8. Feature importance analysis
9. Decision Tree visualisation
10. Model saving

6. Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual performance results are available in the project notebook.

7. Key Features

- Comparison of three machine learning algorithms.
- Visualisation of phishing and legitimate website records.
- Feature importance analysis.
- Confusion matrix analysis.
- Decision Tree visualisation.
- Saved trained models.

8. Limitations

The project uses pre-extracted website features from the UCI dataset. It does not directly analyse arbitrary URLs entered by users or guarantee that a website is safe.

9. Future Scope

- Develop a URL feature extraction module.
- Build a simple interface for user input.
- Evaluate additional classification algorithms.
- Explore real-time phishing detection.

10. Author

Developed as a Machine Learning and Cybersecurity project.
