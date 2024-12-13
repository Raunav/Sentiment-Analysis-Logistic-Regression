# Sentiment-Analysis-Logistic-Regression
This project implements a logistic regression model to classify movie reviews as positive or negative using the IMDb dataset. The dataset consists of 50,000 movie reviews labeled as either positive (rated above six stars) or negative (rated below five stars). The model is trained using preprocessed Bag-of-Words (BOW) features and validated with 5-fold cross-validation.

## Dataset
- **Source:** [Stanford Sentiment Analysis Dataset](http://ai.stanford.edu/~amaas/data/sentiment/)
- **Data Characteristics:**
  - 50,000 movie reviews
  - Pre-separated into training and testing sets
  - Preprocessed BOW features available (`labeledBow.feat` file)

## Objectives
- Develop a logistic regression model to classify movie reviews.
- Preprocess the text data for feature engineering.
- Evaluate the model using 5-fold cross-validation.

## Key Features
1. **Text Cleaning:**
   - Removal of unwanted characters and noise.
2. **Tokenization:**
   - Grouping similar words into unified tokens.
3. **Feature Engineering:**
   - Bag-of-Words representation for each review.
   - Down-weighting frequently occurring, non-discriminatory words.
4. **Model Implementation:**
   - Logistic regression with regularization for robustness.
5. **Evaluation:**
   - Performance metrics evaluated via 5-fold cross-validation.

## Tools and Libraries
- **Python**
- **Scikit-learn** for machine learning modeling
- **NLTK** for natural language processing
- **Pandas and NumPy** for data manipulation
- **Matplotlib and Seaborn** for data visualization

## Extra Features
In addition to the standard implementation, an extended preprocessing pipeline was used to enhance the model's performance. Details of these steps are provided in the accompanying annotated file.

## Results
- **5-Fold Cross-Validation Accuracy:** X% (replace with actual results)
- **Model Insights:**
  - Feature weights indicate that frequently occurring adjectives contribute significantly to the sentiment classification.
  - Reviews with a high density of positive/negative sentiment words were classified accurately.

## Acknowledgments
This project is part of the "Principles of Machine Learning" course at Indiana University Bloomington, Spring 2021. Special thanks to the course instructors for their guidance.

## How to Run
1. Download the dataset from the provided link.
2. Run the Python notebook (`Project4.ipynb`) for preprocessing and training.
3. Evaluate the model's predictions on the test set.

## View the Code
The full implementation of the project can be found on GitHub.
