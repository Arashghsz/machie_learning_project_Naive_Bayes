# Machine Learning Project - Naive Bayes

This repository contains a project for income classification using the Naive Bayes algorithm.

## Required Libraries

The following libraries are required for this project:

- pathlib
- pandas
- numpy
- nltk
- sklearn
- seaborn
- ipywidgets
- imblearn

## Dataset

The dataset used in this project is located on Google Drive. Update the `dsPath` variable in the script with the path to your dataset.

## Steps

1. **Data Loading**: Load the dataset using pandas.
2. **Data Visualization**: Use ipywidgets to visualize the dataset size and the first few rows.
3. **Data Preprocessing**:
   - Remove stopwords
   - Lemmatize and stem words
   - Normalize and scale data
   - Handle imbalanced data using Random Under Sampling
4. **Model Training**: Train a Naive Bayes classifier on the training set.
5. **Model Evaluation**: Evaluate the classifier using confusion matrix and accuracy score.

## Usage
Run in google colab (**Reccommender**)
Run the `income_classification_with_naive_bayes.py` script to execute the project steps.

## Results

After running the script, you will get:
- The dataset size
- The first few rows of the dataset
- A count plot of the target variable
- The confusion matrix and accuracy score of the Naive Bayes classifier
- Interpretation of the confusion matrix

## Interpretation

- **True Positive (TP)**: Correctly predicted positive class.
- **True Negative (TN)**: Correctly predicted negative class.
- **False Positive (FP)**: Incorrectly predicted positive class.
- **False Negative (FN)**: Incorrectly predicted negative class.

## Example

To run the script:

```bash
python income_classification
