# Medical-Condition-Classifier
This project develops a Medical Condition Classifier using NLP and machine learning to predict conditions like Birth Control, Depression, High Blood Pressure, and Diabetes Type 2 from patient reviews. It utilizes TfidfVectorizer for text feature extraction and a PassiveAggressiveClassifier for accurate classification.


Project Overview
The Medical Condition Classifier analyzes patient reviews to predict associated medical conditions. It uses a supervised learning approach with a Passive Aggressive Classifier trained on TF-IDF-transformed text data. The project includes feature importance analysis and sample predictions to demonstrate its capabilities.

Features
Text preprocessing and TF-IDF vectorization using TfidfVectorizer.
Classification of medical conditions with a PassiveAggressiveClassifier.
Identification of the most informative features for each condition.
Sample predictions for new patient reviews.
Model and vectorizer persistence using joblib.
Requirements
To run this project, you'll need the following Python libraries:

scikit-learn (for TfidfVectorizer, PassiveAggressiveClassifier, and train_test_split)
pandas (for data handling)
numpy (for numerical operations)
joblib (for model persistence)
