# Document Classifier using Machine Learning

## Project Overview

This project implements a document classification system using Machine Learning. The classifier automatically categorizes text documents into predefined categories based on their content.

The model is trained using the TF-IDF feature extraction technique and the Multinomial Naive Bayes algorithm.

---

## Objective

The objective of this project is to build a machine learning model that can classify text documents into different categories such as:

* Sports
* Politics
* Technology

---

## Features

* Text document classification
* TF-IDF feature extraction
* Multinomial Naive Bayes classifier
* Model evaluation using Accuracy, Precision, Recall, and F1-Score
* Prediction of new text documents

---

## Technologies Used

* Python
* Google Colab
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Multinomial Naive Bayes

---

## Project Structure

```
Document_Classifier/
│── Document_Classifier.ipynb
│── document_classifier.pkl
│── README.md
```

---

## Dataset

The project uses a sample dataset containing 30 text documents divided equally into three categories:

* Sports
* Politics
* Technology

The dataset is created within the notebook for demonstration purposes.

---

## Machine Learning Workflow

1. Import required libraries
2. Create the dataset
3. Split the dataset into training and testing sets
4. Convert text into numerical features using TF-IDF
5. Train the Multinomial Naive Bayes classifier
6. Evaluate the model
7. Predict the category of new documents

---

## Model Used

* TF-IDF Vectorizer
* Multinomial Naive Bayes Classifier

---

## Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

---

## Sample Prediction

**Input:**

```
Artificial Intelligence is changing healthcare.
```

**Predicted Category:**

```
Technology
```

---

## How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries.
3. Run all cells in order.
4. View the evaluation metrics.
5. Test the classifier with your own text.

---

## Future Enhancements

* Use a larger real-world dataset.
* Add more document categories.
* Improve accuracy using advanced models such as Support Vector Machine (SVM) or BERT.
* Build a web application for document classification.

---

## Conclusion

This project demonstrates the complete workflow of building a document classifier using Machine Learning. It showcases text preprocessing, feature extraction, model training, evaluation, and prediction. The project provides a simple yet effective introduction to Natural Language Processing (NLP) and text classification.

---

## Author

**Name:** Siri Amara

**Internship:** ScholarX Internship

**Project:** Document Classifier using Machine Learning
