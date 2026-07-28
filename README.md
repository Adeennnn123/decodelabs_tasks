# NLP Sentiment Analysis

## Project Overview

This Data Science project focuses on sentiment analysis using Natural Language Processing (NLP). The project analyzes text reviews and classifies their sentiment as positive or negative.

The project uses data preprocessing and text analysis techniques to prepare reviews for sentiment classification and generate useful insights from textual data.

## Objectives

* Load and explore the dataset
* Understand the dataset structure
* Check and handle missing values
* Analyze sentiment distribution
* Clean and preprocess text reviews
* Convert text to lowercase
* Remove punctuation and special characters
* Tokenize text
* Remove stopwords
* Apply lemmatization
* Convert text into numerical features using TF-IDF
* Analyze positive and negative sentiments
* Evaluate sentiment classification results
* Predict sentiment for new reviews

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* Jupyter Notebook

## Project Workflow

### 1. Dataset Loading

The cleaned dataset is loaded using Pandas.

```python
df = pd.read_csv("IMDB_Dataset_CLEANED.csv")
```

### 2. Data Exploration

The dataset is analyzed using:

* `head()`
* `info()`
* `shape`
* Missing value checking
* Sentiment value counts

### 3. Sentiment Distribution

A bar chart is created to visualize the distribution of positive and negative reviews in the dataset.

### 4. Text Preprocessing

The following NLP preprocessing steps are performed:

* Convert text to lowercase
* Remove special characters
* Tokenize the text
* Remove English stopwords
* Apply WordNet lemmatization

### 5. TF-IDF Vectorization

The cleaned reviews are converted into numerical features using TF-IDF Vectorization.

```python
tfidf = TfidfVectorizer()
X = tfidf.fit_transform(df["Clean_Review"])
```

### 6. Data Analysis

The processed text data is analyzed to identify positive and negative sentiment patterns.

### 7. Sentiment Classification

The project classifies reviews into two sentiment categories:

* Positive
* Negative

### 8. Results Evaluation

The sentiment classification results are evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 9. New Review Analysis

The project can analyze new reviews and identify whether their sentiment is positive or negative.

## Project Structure

```text
Task4
│
├── NLP_Sentiment_Analysis.ipynb
├── IMDB_Dataset_CLEANED.csv
└── README.md
```

## Conclusion

The project successfully applies Natural Language Processing techniques to analyze movie reviews and identify positive and negative sentiments. Text cleaning, tokenization, stopword removal, lemmatization, and TF-IDF Vectorization help prepare the textual data for effective sentiment analysis.

## Author

Adeen Fatima
