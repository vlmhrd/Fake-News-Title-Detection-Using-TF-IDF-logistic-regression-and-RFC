# Fake-News-Title-Detection-Using-TF-IDF-logistic-regression-and-RFC

# Goal:
The objective of this project is to detect fake news titles using machine learning techniques. The project aims to classify news titles as real or fake based on their text features.

# Tools Used:

- Dataset: [fake-and-real-news-dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
Libraries:
- pandas & numpy (data manipulation)
- scikit-learn (TF-IDF, Logistic Regression, Random Forest, and evaluation metrics)


# Conclusions: 
After evaluating both models:
- Logistic Regression performed very well, achieving high accuracy (about 94.4%) and strong precision, recall, and F1 scores.
- Random Forest Classifier did not perform as well as Logistic Regression, with lower accuracy (about 82.9%) and lower recall and F1 scores, even after fine-tuning with grid search.
- The best parameters found for the Random Forest model were: max_depth=15 and n_estimators=100.
- Overall, the Logistic Regression model was more effective for this fake news title classification task based on the dataset and approach used in the notebook.
