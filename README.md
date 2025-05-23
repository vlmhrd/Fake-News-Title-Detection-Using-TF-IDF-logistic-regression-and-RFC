# Fake-News-Title-Detection-Using-TF-IDF-logistic-regression-and-RFC

# Goal:
The objective of this project is to detect fake news titles using machine learning techniques. The project aims to classify news titles as real or fake based on their text features.
Data taken from [fake-and-real-news-dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

# Steps:

- Data Collection & Preprocessing:
   - Load and clean the dataset containing news titles and labels (real/fake).
Perform text normalization (e.g., lowercasing, removing punctuation and stopwords).
Feature Extraction:

   - Transform the text data into numerical features using TF-IDF (Term Frequency–Inverse Document Frequency) vectorization.
Model Building & Training:

   - Train two machine learning models: Logistic Regression and Random Forest Classifier (RFC) using the TF-IDF features.
  
- Evaluation:

Evaluate both models on a validation/test set using metrics such as accuracy, precision, recall, and F1 score.
Compare model performance to select the best approach.
 
- Prediction & Results:

Use the best-performing model to make predictions on new/unseen news titles.
# Tools Used:

- Programming Language: Python (within Jupyter Notebook)
Libraries:
- pandas & numpy (data manipulation)
- scikit-learn (TF-IDF, Logistic Regression, Random Forest, and evaluation metrics)
