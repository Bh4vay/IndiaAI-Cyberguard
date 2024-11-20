
# Text Classification Project Using Multinomial Naive Bayes

## Overview

This project focuses on the classification of crime-related text data into specific sub-categories using the Multinomial Naive Bayes algorithm. The dataset comprises textual descriptions of crimes, which are preprocessed, vectorized, and classified into relevant categories.

## Features

- Text preprocessing including normalization, punctuation removal, and number removal.
- Feature extraction using **TF-IDF Vectorization**.
- Model training and hyperparameter tuning with **Multinomial Naive Bayes**.
- Evaluation using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

## Workflow

1. **Data Loading**: Import the dataset into a Pandas DataFrame.
2. **Data Preprocessing**:
   - Handle missing values by replacing them with default values.
   - Normalize text by converting to lowercase, removing punctuation, and removing numbers.
3. **Data Splitting**: Split the dataset into training and testing sets.
4. **Vectorization**: Convert textual data to numerical format using **TfidfVectorizer**.
5. **Model Training**: Train the model using **Multinomial Naive Bayes** with hyperparameter tuning via GridSearchCV.
6. **Evaluation**:
   - Measure performance using metrics like accuracy, precision, recall, and F1-score.
   - Visualize a confusion matrix for better insights.


## Installation and Usage

### Prerequisites

- Python 3.7+
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `joblib`, `matplotlib`, `seaborn`.


## Results

- The model achieved significant accuracy in classifying crime descriptions into sub-categories.
- Insights from the confusion matrix and evaluation metrics highlighted areas for potential improvements.

## Future Improvements

- Incorporate advanced text preprocessing techniques, such as stemming or lemmatization.
- Use more sophisticated models like Logistic Regression, SVM, or Deep Learning approaches for improved classification.
- Explore additional features or external datasets to enhance classification accuracy.

## Contact

For any inquiries, please contact:
- **Name**: Bhavay Kaushal
- **Email**: [bk4125@srmist.edu.in]
- **Name**: Nishtha Dabas
- **Email**: [nd9295@srmist.edu.in]
