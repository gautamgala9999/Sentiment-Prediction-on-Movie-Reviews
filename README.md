# Sentiment Prediction on Movie Reviews

This code is a machine learning project for sentiment prediction on movie reviews. The dataset includes information about movie reviews, such as review text, audience score, and additional details about the movies. The goal is to build and evaluate several classification models to predict the sentiment of the reviews.

### Files Included

- **Code File:** `notebook.ipynb`
- **Input Data Files:**
  - `train.csv` : Training dataset containing movie reviews and associated details.
  - `test.csv` : Testing dataset for making predictions.
  - `movies.csv` : Additional information about movies.

### Getting Started

1. **Libraries and Merging:**
   - The code begins by importing necessary libraries and merging the training and testing datasets with movie details.

2. **Exploratory Data Analysis (EDA):**
   - Basic exploratory data analysis is performed on the merged dataset, including visualizations of the target variable distribution, feature distributions, correlation heatmap, and feature relationships.

3. **Data Preprocessing:**
   - Missing values are handled, and feature selection is performed based on the analysis.
   - Data types and missing values are displayed in a table for reference.

4. **Imputation:**
   - Missing values in the `audienceScore` column are imputed using the most frequent value.

5. **Data Transformation:**
   - The text data is transformed using TF-IDF vectorization, and numerical features are prepared for model training.

6. **Model Training:**
   - Three classification models are trained: SGDClassifier, LinearSVC, and Logistic Regression, along with hyperparameter tuning for SGDClassifier.

7. **Model Comparison:**
   - The training and validation scores for each model are compared, and a bar chart is generated to visualize the results.

8. **Output:**
   - Predictions are made on the test dataset using the best-performing model, and the results are saved in CSV files.

### How to Run the Code

1. Ensure that you have the required libraries installed, including `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, and `numpy`.
2. Provide the correct file paths for the training, testing, and movie details datasets.
3. Run the code step by step or as a whole.

### Note

- The code assumes that the dataset structure remains the same, and modifications may be required for different datasets.

### Author

Gautam Gala
